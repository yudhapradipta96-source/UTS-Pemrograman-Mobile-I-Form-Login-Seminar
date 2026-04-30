# UTS-Pemrograman-Mobile-I-Form-Login-Seminar
# UTS Pendaftaran Seminar (Pradipta Yudha)

Aplikasi ini adalah sistem pendaftaran seminar mahasiswa yang dikembangkan sebagai proyek UTS. Aplikasi ini mencakup alur lengkap dari pendaftaran akun, login, pengisian formulir seminar, hingga penampilan hasil pendaftaran.

## ✨ Fitur Utama

1.  **Sistem Login & Register**:
    *   **Register**: Membuat akun baru (Nama, Email, Password). Data disimpan secara lokal menggunakan `SharedPreferences`.
    *   **Auto-Login**: Setelah mendaftar, user otomatis masuk ke halaman utama tanpa perlu login manual.
    *   **Login**: Validasi kredensial (mendukung akun yang baru didaftarkan atau akun default: `admin@utb.ac.id` / `12345`).

2.  **Halaman Utama**:
    *   Menampilkan ucapan selamat datang yang dipersonalisasi dengan nama user.
    *   Navigasi cepat ke formulir pendaftaran seminar.

3.  **Form Pendaftaran Seminar**:
    *   Input: Nama, Email, Nomor HP.
    *   Pilihan: Jenis Kelamin (RadioGroup) dan Pilihan Seminar (Spinner - 5 Pilihan).
    *   Persetujuan: Checkbox persyaratan data benar.

4.  **Validasi Input & Error Handling**:
    *   **Real-time Validation**: Pesan error muncul seketika saat user mengetik jika format salah (Email tanpa '@', No HP bukan '08...', dsb).
    *   **Submit Validation**: Memastikan semua field terisi dan checkbox dicentang sebelum diproses.

5.  **Dialog Konfirmasi**:
    *   Menampilkan `AlertDialog` untuk mengonfirmasi kebenaran data sebelum dikirim ke halaman hasil.

6.  **Halaman Hasil**:
    *   Menampilkan ringkasan data yang telah diinput user.
    *   Menampilkan status "Pendaftaran Berhasil".
    *   Tombol navigasi kembali ke Beranda.

## 🎨 UI/UX Design

*   **Material Design 3**: Menggunakan komponen Material seperti `CardView`, `TextInputLayout` (Outlined), dan `Button`.
*   **Visual**: Background bertema seminar kustom (`bg_seminar.xml`) yang memberikan tampilan profesional dan tidak polos.
*   **Responsif**: Menggunakan `ScrollView` untuk memastikan form tetap nyaman diakses di berbagai ukuran layar.

## 🛠️ Teknologi yang Digunakan

*   **Bahasa**: Kotlin
*   **Platform**: Android
*   **Penyimpanan**: SharedPreferences (Local Storage)
*   **Library**: Material Components, ConstraintLayout, Android KTX.

---

## 📺 Video Penjelasan (Demo & Kode)

Silakan klik link di bawah ini untuk melihat penjelasan detail mengenai alur aplikasi dan penjelasan potongan kode:

👉 **[LINK VIDEO PENJELASAN DI SINI]([MASUKKAN_LINK_VIDEO_ANDA_DI_SINI])**

*Video berisi: Penjelasan Login, Register, Halaman Utama, Form Pendaftaran, Validasi Real-time, Dialog Konfirmasi, dan Halaman Hasil.*

---

**Disusun Oleh:**  
**Nama:** Pradipta Yudha  
**Proyek:** UTS Pemrograman Mobile - Pendaftaran Seminar (UTB)
