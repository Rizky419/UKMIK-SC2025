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

1. **Pilih folder topik yang sesuai**

   - Frontend → `FRONTEND/`
   - Backend → `BACKEND/`
   - Game Development → `GAME-DEV/`
   - Cybersecurity → `CYBERSECURITY/`

2. **Masuk ke folder pertemuan yang sesuai**

   - Contoh: `FRONTEND/PERTEMUAN-1/`

3. **Buat folder dengan nama Anda**

   - Format: `NAMA-ANDA/` atau `NIM-NAMA/`

4. **Upload tugas Anda ke dalam folder tersebut**
   - Pastikan file terorganisir dengan baik
   - Sertakan README jika diperlukan

### Contoh Struktur Pengumpulan:

```
FRONTEND/
└── PERTEMUAN-1/
    └── 123456-JOHN-DOE/
        ├── index.html
        ├── style.css
        └── README.md
```

## 🚀 Langkah-Langkah Pengumpulan Tugas

### A. Setup Awal (Hanya Sekali)

1. **Clone repository** ini ke komputer Anda

   ```bash
   git clone https://github.com/UKM-IK/UKMIK-SC2025.git
   ```

2. **Masuk ke folder repository**

   ```bash
   cd UKMIK-SC2025
   ```

3. **Konfigurasi Git** (jika belum)
   ```bash
   git config user.name "Nama Anda"
   git config user.email "email@anda.com"
   ```

### B. Mengumpulkan Tugas (Setiap Tugas)

1. **Update repository** ke versi terbaru

   ```bash
   git checkout main
   git pull origin main
   ```

2. **Buat branch baru** untuk tugas Anda

   ```bash
   git checkout -b tugas/topik-pertemuan-nama
   ```

   📝 **Contoh**: `git checkout -b tugas/frontend-1-johndoe`

3. **Buat folder tugas** Anda di lokasi yang sesuai

   ```
   TOPIK/PERTEMUAN-N/NIM-NAMA/
   ```

   📝 **Contoh**: `FRONTEND/PERTEMUAN-1/123456-JOHN-DOE/`

4. **Tambahkan file tugas** Anda ke dalam folder tersebut

   - Kerjakan tugas Anda
   - Pastikan file terorganisir dengan baik

5. **Cek status file**

   ```bash
   git status
   ```

6. **Add file** yang akan di-commit

   ```bash
   git add .
   ```

   Atau spesifik: `git add FRONTEND/PERTEMUAN-1/123456-JOHN-DOE/`

7. **Commit perubahan** dengan pesan yang jelas

   ```bash
   git commit -m "Tambah tugas [TOPIK] pertemuan [N] - [NAMA]"
   ```

   📝 **Contoh**: `git commit -m "Tambah tugas Frontend pertemuan 1 - John Doe"`

8. **Push branch** ke repository

   ```bash
   git push origin tugas/topik-pertemuan-nama
   ```

9. **Buat Pull Request** di GitHub:

   - Buka [github.com/UKM-IK/UKMIK-SC2025](https://github.com/UKM-IK/UKMIK-SC2025)
   - Akan muncul banner **"Compare & pull request"** → klik
   - Isi judul: `[TOPIK] Pertemuan N - Nama Anda`
   - Isi deskripsi tugas Anda (opsional)
   - Klik **"Create pull request"**

10. **Tunggu review** dari mentor/admin
    - Mentor akan review tugas Anda
    - Jika ada revisi, lakukan perubahan dan push lagi ke branch yang sama
    - Setelah approved, PR akan di-merge

### C. Setelah PR Di-merge

Setelah PR Anda di-merge, kembali ke branch main:

```bash
git checkout main
git pull origin main
```

Untuk tugas berikutnya, ulangi dari **Langkah B**.

## ⚠️ Peraturan Pengumpulan

- ✅ Kumpulkan tugas sesuai deadline yang ditentukan
- ✅ Gunakan nama folder yang jelas dan konsisten (NIM-NAMA)
- ✅ Pastikan code Anda bersih dan terdokumentasi
- ✅ **WAJIB** gunakan branch baru untuk setiap tugas (jangan langsung ke main)
- ✅ Jangan mengubah atau menghapus tugas orang lain
- ✅ Sertakan komentar pada kode Anda
- ✅ Test code Anda sebelum push
- ❌ Dilarang melakukan plagiarisme
- ❌ Dilarang push langsung ke branch `main`

## 💡 Tips & Troubleshooting

### Tips Pengumpulan:

- 📌 Selalu `git pull origin main` sebelum mulai mengerjakan tugas baru
- 📌 Gunakan branch terpisah untuk setiap tugas
- 📌 Commit dengan pesan yang jelas dan deskriptif
- 📌 Push sesering mungkin untuk backup
- 📌 Jangan menunggu deadline untuk mengumpulkan

### Troubleshooting:

**❓ Tidak bisa push (Permission denied)**

- Pastikan Anda sudah menjadi member organisasi UKM-IK
- Cek apakah invitation sudah diterima

**❓ Ada conflict saat pull/push**

```bash
# Simpan perubahan Anda sementara
git stash

# Pull perubahan terbaru
git pull origin main

# Kembalikan perubahan Anda
git stash pop

# Resolve conflict jika ada, lalu commit
```

**❓ Salah commit/push**

```bash
# Undo commit terakhir (tapi file tetap ada)
git reset --soft HEAD~1

# Atau undo commit dan buang perubahan
git reset --hard HEAD~1
```

**❓ Lupa nama branch**

```bash
# Lihat semua branch
git branch -a
```

**❓ Ingin ganti branch**

```bash
git checkout nama-branch
```

## 📞 Kontak

Jika ada pertanyaan atau kendala, silakan hubungi:

- **Instagram**: [@ukmik](https://www.instagram.com/ukmik/)
- **Email**: ukmik@utdi.ac.id

## 📜 Lisensi

Repository ini dikelola oleh UKM Ilmu Komputer untuk keperluan pembelajaran Study Club 2025.

---

**Happy Coding! 🚀💻**

_UKM Ilmu Komputer - Study Club 2025_
