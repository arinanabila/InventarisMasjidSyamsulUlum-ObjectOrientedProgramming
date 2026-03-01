<img width="1920" height="1080" alt="Inventory MSU" src="https://github.com/user-attachments/assets/1f383fcc-4a9c-4b1e-956c-53b29cb2fdd8" />

# Inventory MSU

**Sistem Informasi Inventaris & Peminjaman MSU** adalah aplikasi berbasis web yang dikembangkan untuk mendigitalisasi proses manajemen aset dan fasilitas di lingkungan Masjid Syamsul 'Ulum.

Aplikasi ini dirancang untuk menggantikan pencatatan manual, mempermudah pelacakan kondisi inventaris, serta mengelola jadwal peminjaman ruangan dan barang secara efisien, transparan, dan terstruktur.

---

## 🚀 Fitur Utama

- **Manajemen Inventaris (Asset Management):**
  - Mencatat data barang masuk dan kondisi barang.
  - Pembaruan status ketersediaan aset secara *real-time*.

- **Sistem Peminjaman (Booking & Loan):**
  - Pengajuan peminjaman barang atau ruangan oleh pengguna.
  - Validasi tanggal dan waktu agar tidak bentrok.
  - Persetujuan (*Approval*) oleh admin/pengelola.

- **Manajemen Pengguna (User Roles):**
  - **Admin / Pengelola:** Mengelola seluruh data aset, data persetujuan, dan sistem.
  - **Pengurus:** Mengakses fitur pemantauan dan laporan.
  - **Guest / User:** Melihat ketersediaan dan mengajukan peminjaman.

- **Riwayat & Laporan:**
  - Memantau sejarah peminjaman dan pengembalian aset.
  - Membuat laporan peminjaman yang dapat diunduh (terintegrasi dengan Apache POI & iText).

---

## 🏗️ Arsitektur & Teknologi

Aplikasi ini dibangun menggunakan pola arsitektur **MVC (Model-View-Controller)** untuk memisahkan logika bisnis, antarmuka pengguna, dan data, sehingga kode lebih rapi dan mudah dikembangkan.

**Tech Stack:**

| Komponen | Teknologi |
| :--- | :--- |
| **Framework Backend** | Spring Boot (Java 17) |
| **Database** | MySQL / MariaDB (Spring Data JPA) |
| **Frontend** | Thymeleaf, HTML/CSS/JS |
| **Server Environment** | Embedded Tomcat, Docker (Docker Compose) |
| **Security** | Spring Security |
