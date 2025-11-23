# FRONTEND - Study Club UKM IK 2025

Panduan khusus untuk peserta Study Club Topik Frontend. File ini menjelaskan cara mengumpulkan tugas dengan sistem **submit link repository**.

## 🎯 Tujuan

Folder `FRONTEND/` adalah tempat pengumpulan link repository tugas terkait frontend.

## 📝 Cara Pengumpulan Tugas

Pengumpulan tugas dilakukan dengan **menambahkan link repository GitHub Anda** ke file `README.md` di folder pertemuan yang sesuai.

### Langkah-langkah:

1. **Buat repository public** di GitHub untuk tugas Anda

   - Nama: `frontend-pertemuan-[N]`
   - Contoh: `frontend-pertemuan-1`
   - Set **Public** ✅

2. **Kerjakan tugas** di repository tersebut

   - Struktur folder yang rapi
   - Sertakan `README.md` lengkap (cara install, run, test)
   - Commit dan push secara berkala

3. **Clone repository Study Club**

   ```bash
   git clone https://github.com/UKM-IK/UKMIK-SC2025.git
   cd UKMIK-SC2025
   ```

4. **Update dan buat branch**

   ```bash
   git checkout main
   git pull origin main
   git checkout -b submit/frontend-pertemuan-nama
   ```

5. **Edit file README.md** di folder pertemuan

   - Buka: `FRONTEND/PERTEMUAN-[N]/README.md`
   - Tambahkan baris baru di tabel:

   ```markdown
   | Nama Lengkap | NIM | [repo-name](link-repository) |
   ```

6. **Commit dan push**

   ```bash
   git add .
   git commit -m "Submit tugas frontend pertemuan [N] - [NAMA]"
   git push origin submit/frontend-pertemuan-nama
   ```

7. **Buat Pull Request** di GitHub

### Format Tabel:

```markdown
| Nama     | NIM    | Repository                                                              |
| -------- | ------ | ----------------------------------------------------------------------- |
| John Doe | 123456 | [frontend-pertemuan-1](https://github.com/johndoe/frontend-pertemuan-1) |
```

Terima kasih, semoga tugasnya lancar! 🚀
