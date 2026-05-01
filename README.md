## Belajar Perintah Git  

### 1. Create / Setup  
- `git init` → inisialisasi repository Git  
- `git clone <link>` → cloning repository dari remote ke lokal  

### 2. Make a Change  
- `git add <namafile/folder>` → tambahkan ke staging area  
- `git add .` → tambahkan semua perubahan  
- `git commit -m "pesan"` → simpan snapshot perubahan  
- `git reset <namafile>` → batalkan perubahan di staging area  
- `git reset .` → batalkan semua perubahan di staging area  
- `git reset --hard <hash>` → kembalikan repo ke commit tertentu  
- `git restore <namafile>` → batalkan perubahan di working directory  
- `git restore --staged <namafile>` → batalkan file di staging area  
- `git revert <hash>` → buat commit baru yang membatalkan commit lama  

### 3. Observe  
- `git status` → cek kondisi repo  
- `git diff` → lihat perbedaan antar versi file  
- `git show <hash>` → detail commit tertentu  
- `git log` → riwayat commit  
- `git log --oneline` → riwayat singkat  

### 4. Sync  
- `git push origin <namabranch>` → kirim commit ke remote  
- `git pull origin <namabranch>` → ambil commit dari remote  
- `git remote add origin <link>` → hubungkan repo lokal ke remote  
- `git remote -v` → cek remote yang terhubung  
- `git fetch` → ambil commit terbaru tanpa merge  

### 5. Branching  
- `git branch <namabranch>` → buat branch baru  
- `git branch -D <namabranch>` → hapus branch  
- `git branch` → lihat daftar branch  
- `git checkout <namabranch>` → pindah branch  
- `git merge <namabranch>` → gabungkan branch  
- `git tag -a "namatag"` → buat tag versi  
- `git push origin master --tags` → kirim tag ke remote  
