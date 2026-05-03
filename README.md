# Penjelasan GIT 💡
<p align="justify">
Git merupakan sistem kontrol versi terdistribusi yang digunakan untuk melacak perubahan dalam kode sumber selama pengembangan perangkat lunak. Dengan Git, beberapa pengembang dapat bekerja secara bersamaan pada proyek yang sama tanpa konflik, serta memungkinkan kolaborasi yang lebih efisien untuk pengelolaan versi kode yang lebih baik. Git sendiri diciptakan oleh **Linus Torvalds**.
</p>

---

## Macam-macam Perintah Git 📌

### 1. Create / Setup 📎
```
- git init → inisialisasi repository Git  
- git clone " LinkGithub " → cloning repository dari remote ke lokal
```

---

### 2. Make a Change 📎
```
- git add " NamaFile/Folder " → tambahkan ke staging area  
- git add . → tambahkan semua perubahan  
- git commit -m " PesanCommit " → simpan snapshot perubahan  
- git reset " NamaFile " → batalkan perubahan di staging area  
- git reset . → batalkan semua perubahan di staging area  
- git reset --hard " KodeHash " → kembalikan repo ke commit tertentu  
- git restore " NamaFile " → batalkan perubahan di working directory  
- git restore --staged " NamaFile " → batalkan file di staging area  
- git revert " KodeHash " → buat commit baru yang membatalkan commit lama  
```
---

### 3. Observe 📎
```
- git status → cek kondisi repo  
- git diff → lihat perbedaan antar versi file  
- git show " KodeHash " → detail commit tertentu  
- git log → riwayat commit  
- git log --oneline → riwayat singkat  
```
---

### 4. Sync 📎
```
- git push origin " NamaBranch " → kirim commit ke remote  
- git pull origin " NamaBranch " → ambil commit dari remote  
- git remote add origin " LinkRepoGit " → hubungkan repo lokal ke remote  
- git remote -v → cek remote yang terhubung  
- git fetch → ambil commit terbaru tanpa merge  
```
---

### 5. Branching 📎
```
- git branch " NamaBranch " → buat branch baru  
- git branch -D " NamaBranch " → hapus branch  
- git branch → lihat daftar branch  
- git checkout " NamaBranch " → pindah branch  
- git merge " NamaBranch " → gabungkan branch  
- git tag -a " NamaTag" → buat tag versi  
- git push origin master --tags → kirim tag ke remote  
```
