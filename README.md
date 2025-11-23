# 📚 Study Club UKM IK 2025

Selamat datang di repository **Study Club UKM IK 2025**! Repository ini merupakan platform pengumpulan tugas untuk semua peserta Study Club UKM Informatika & Komputer tahun 2025.

## 📋 Deskripsi

Repository ini dirancang sebagai tempat pengumpulan tugas untuk berbagai topik yang diajarkan dalam Study Club UKM IK. Setiap peserta dapat mengumpulkan tugas mereka di folder yang sesuai dengan topik yang mereka ikuti.

## 🎯 Topik Study Club

Study Club UKM IK 2025 menyediakan 4 topik pembelajaran:

### 1. 🎨 Frontend Development (`FRONTEND/`)

Materi dan tugas terkait pengembangan antarmuka pengguna (UI/UX) dan teknologi frontend modern.

### 2. ⚙️ Backend Development (`BACKEND/`)

Materi dan tugas terkait pengembangan server-side, API, database, dan arsitektur backend.

### 3. 🎮 Game Development (`GAME-DEV/`)

Materi dan tugas terkait pengembangan game, game engine, dan mekanika permainan.

### 4. 🔐 Cybersecurity (`CYBERSECURITY/`)

Materi dan tugas terkait keamanan siber, ethical hacking, dan praktik keamanan informasi.

## 📝 Cara Pengumpulan Tugas

Pengumpulan tugas dilakukan dengan **menambahkan link repository GitHub Anda** ke file `README.md` di folder pertemuan yang sesuai.

### Format Pengumpulan:

1. Buat repository **public** di GitHub untuk tugas Anda
2. Kerjakan tugas di repository tersebut
3. Tambahkan informasi Anda ke file `README.md` di folder pertemuan dengan format:

```markdown
| Nama         | NIM    | Repository                                               |
| ------------ | ------ | -------------------------------------------------------- |
| Nama Lengkap | 123456 | [Link Repository](https://github.com/username/repo-name) |
```

### Contoh:

Jika Anda mengikuti **Backend** pertemuan 1, edit file `BACKEND/PERTEMUAN-1/README.md` dan tambahkan baris baru:

```markdown
| John Doe | 123456 | [backend-pertemuan-1](https://github.com/johndoe/backend-pertemuan-1) |
```

## 🚀 Langkah-Langkah Pengumpulan Tugas

### A. Persiapan Repository Tugas Anda

1. **Buat repository baru** di GitHub untuk tugas Anda

   - Buka [github.com/new](https://github.com/new)
   - Nama repository: `[topik]-pertemuan-[N]`
   - Contoh: `backend-pertemuan-1`, `frontend-pertemuan-2`
   - Set visibility: **Public** ✅
   - Centang "Add a README file"
   - Klik "Create repository"

2. **Clone repository tugas Anda** ke komputer

   ```bash
   git clone https://github.com/USERNAME-ANDA/nama-repo-tugas.git
   cd nama-repo-tugas
   ```

3. **Kerjakan tugas Anda** di repository tersebut
   - Buat struktur folder yang rapi
   - Tambahkan README.md yang menjelaskan cara menjalankan project
   - Commit dan push secara berkala

### B. Submit Link Repository Anda

1. **Clone repository Study Club** (jika belum)

   ```bash
   git clone https://github.com/UKM-IK/UKMIK-SC2025.git
   cd UKMIK-SC2025
   ```

2. **Update ke versi terbaru**

   ```bash
   git checkout main
   git pull origin main
   ```

3. **Buat branch baru**

   ```bash
   git checkout -b submit/topik-pertemuan-nama
   ```

   📝 **Contoh**: `git checkout -b submit/backend-1-johndoe`

4. **Edit file README.md** di folder pertemuan yang sesuai

   - Buka file: `TOPIK/PERTEMUAN-N/README.md`
   - Contoh: `BACKEND/PERTEMUAN-1/README.md`
   - Tambahkan baris baru ke tabel dengan format:
     ```markdown
     | Nama Lengkap | NIM | [repo-name](link-repository) |
     ```

5. **Commit perubahan**

   ```bash
   git add .
   git commit -m "Submit tugas [TOPIK] pertemuan [N] - [NAMA]"
   ```

   📝 **Contoh**: `git commit -m "Submit tugas Backend pertemuan 1 - John Doe"`

6. **Push branch**

   ```bash
   git push origin submit/topik-pertemuan-nama
   ```

7. **Buat Pull Request**

   - Buka [github.com/UKM-IK/UKMIK-SC2025](https://github.com/UKM-IK/UKMIK-SC2025)
   - Klik "Compare & pull request"
   - Judul: `Submit [TOPIK] Pertemuan N - Nama Anda`
   - Klik "Create pull request"

8. **Tunggu approval** dari mentor

### C. Setelah PR Di-merge

```bash
git checkout main
git pull origin main
```

Untuk tugas berikutnya, ulangi dari **Langkah A**.

## ⚠️ Peraturan Pengumpulan

- ✅ Repository tugas **WAJIB public**
- ✅ Kumpulkan tugas sesuai deadline yang ditentukan
- ✅ Repository tugas harus memiliki **README.md** yang jelas (cara install, run, dan deskripsi)
- ✅ Pastikan code Anda bersih dan terdokumentasi
- ✅ **WAJIB** gunakan branch baru saat submit link (jangan langsung ke main)
- ✅ Jangan mengubah atau menghapus entry orang lain di tabel
- ✅ Sertakan komentar pada kode Anda
- ✅ Test code Anda sebelum submit
- ❌ Dilarang melakukan plagiarisme
- ❌ Dilarang push langsung ke branch `main`

## 💡 Tips

### Tips Pengumpulan:

- 📌 Buat repository tugas dengan nama yang jelas dan deskriptif
- 📌 Pastikan repository tugas Anda **public** agar mentor bisa review
- 📌 Sertakan **README.md lengkap** di repository tugas (cara install, run, screenshot/demo)
- 📌 Commit dengan pesan yang jelas dan deskriptif
- 📌 Push ke repository tugas Anda sesering mungkin untuk backup
- 📌 Submit link repository sebelum deadline
- 📌 Selalu `git pull origin main` sebelum submit link tugas baru

## 📞 Kontak

Jika ada pertanyaan atau kendala, silakan hubungi:

- **Instagram**: [@ukmik](https://www.instagram.com/ukmik/)
- **Email**: ukmik@utdi.ac.id

## 📜 Lisensi

Repository ini dikelola oleh UKM Informatika & Komputer untuk keperluan pembelajaran Study Club 2025.

---

**Happy Coding! 🚀💻**

_UKM Informatika & Komputer - Study Club 2025_
