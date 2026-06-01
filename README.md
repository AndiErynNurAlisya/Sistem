# Besar Sistem

Dokumentasi ini menjelaskan struktur dan fungsi dari tiga halaman utama dalam sistem aplikasi.

---

## Daftar Isi

1. [Halaman Login](#1-halaman-login)
2. [Halaman Register](#2-halaman-register)
3. [Halaman Utama](#3-halaman-utama)

---

## 1. Halaman Login

Halaman Login adalah halaman pertama yang ditemui pengguna saat membuka aplikasi. Halaman ini berfungsi untuk memverifikasi identitas pengguna sebelum mengakses sistem.

### Fitur
- Input email/username
- Input password
- Tombol Login
- Link menuju halaman Register (bagi pengguna baru)
- Opsi lupa password

### Alur
1. Pengguna memasukkan email dan password
2. Sistem memvalidasi data
3. Jika valid → diarahkan ke Halaman Utama
4. Jika tidak valid → menampilkan pesan error

---

## 2. Halaman Register

Halaman Register digunakan oleh pengguna baru untuk membuat akun dan mendaftarkan diri ke dalam sistem.

### Fitur
- Input nama lengkap
- Input email
- Input password
- Input konfirmasi password
- Tombol Daftar
- Link kembali ke halaman Login

### Alur
1. Pengguna mengisi formulir pendaftaran
2. Sistem memvalidasi data (email unik, password cocok, dll.)
3. Jika valid → akun dibuat, pengguna diarahkan ke Halaman Login
4. Jika tidak valid → menampilkan pesan error

---

## 3. Halaman Utama

Halaman Utama adalah halaman yang ditampilkan setelah pengguna berhasil login. Halaman ini merupakan pusat navigasi utama dari aplikasi.

### Fitur
- Menampilkan informasi/konten utama aplikasi
- Navigasi ke fitur-fitur lainnya
- Informasi profil pengguna
- Tombol Logout

### Alur
1. Pengguna berhasil login
2. Sistem memuat data dan konten yang relevan
3. Pengguna dapat bernavigasi ke fitur lain dari halaman ini

---

## Teknologi yang Digunakan

> Sesuaikan bagian ini dengan teknologi yang digunakan dalam proyek Anda.

- **Frontend:** (contoh: Android / Flutter / React Native)
- **Backend:** (contoh: Node.js / Laravel / Firebase)
- **Database:** (contoh: MySQL / Firestore)

---

## Cara Menjalankan

```bash
# Clone repositori
git clone https://github.com/username/nama-repo.git

# Masuk ke direktori proyek
cd nama-repo

# Install dependensi
npm install

# Jalankan aplikasi
npm start
```

---

## Kontribusi

Pull request sangat diterima. Untuk perubahan besar, harap buka issue terlebih dahulu untuk mendiskusikan perubahan yang ingin dilakukan.

---

## Lisensi

[MIT](LICENSE)



##Dokumentasi
1.Halaman Login
<img width="2880" height="1704" alt="image" src="https://github.com/user-attachments/assets/1645f197-61fc-413d-8ed4-36f5c2aa5d6b" />
2.Halaman Register
<img width="2880" height="1705" alt="image" src="https://github.com/user-attachments/assets/741b07d6-f785-4efd-8192-9b26893d3f62" />
3. Halaman utama
<img width="2880" height="1704" alt="image" src="https://github.com/user-attachments/assets/48573aef-108e-4d82-8e0a-f17285b78906" />

