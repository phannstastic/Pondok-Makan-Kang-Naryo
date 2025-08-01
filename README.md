# Pondok Makan Kang Naryo

![Screenshot Website](https://raw.githubusercontent.com/phannstastic/Pondok-Makan-Kang-Naryo/main/deployment/Screenshot%202025-07-27%20112153.png)
**Kunjungi Website:** [https://pondokmakankangnaryo.store/](https://pondokmakankangnaryo.store/)

Selamat datang di repositori resmi **Pondok Makan Kang Naryo**! Ini adalah aplikasi web inovatif yang dirancang untuk mengoptimalkan manajemen operasional harian sebuah pondok makan, mulai dari pemesanan hingga pelaporan.

## 🍽️ Tentang Proyek Ini

Pondok Makan Kang Naryo adalah sebuah sistem manajemen berbasis web yang dibangun untuk memfasilitasi pemilik dan staf pondok makan dalam mengelola berbagai aspek bisnis mereka secara efisien. Aplikasi ini bertujuan untuk menyederhanakan proses-proses kompleks dan meningkatkan produktivitas.

**Fungsionalitas utama meliputi:**

* **Manajemen Menu Komprehensif**: Mengelola daftar menu makanan dan minuman dengan mudah, termasuk detail harga, deskripsi, dan ketersediaan.
* **Sistem Pemesanan Terintegrasi**: Mencatat dan melacak pesanan pelanggan, baik untuk makan di tempat (dine-in) maupun dibawa pulang (take-away).
* **Pelaporan Penjualan Akurat**: Menghasilkan laporan penjualan yang detail (harian, mingguan, bulanan) untuk analisis kinerja bisnis.
* **Manajemen Pengguna Fleksibel**: Mengatur peran dan hak akses pengguna (misalnya, administrator, kasir, pelayan) untuk menjaga keamanan dan efisiensi operasional.

## ✨ Fitur Unggulan

* **Antarmuka Pengguna (UI) Intuitif**: Dirancang untuk kemudahan penggunaan oleh semua tingkatan staf.
* **Sistem Otentikasi & Otorisasi**: Keamanan data terjamin dengan sistem login dan hak akses berbasis peran.
* **CRUD (Create, Read, Update, Delete) Dinamis**: Kontrol penuh atas data menu, pesanan, dan pengguna.
* **Pelacakan Pesanan Real-time**: Memantau status pesanan dari awal hingga selesai.
* **Struktur Database Efisien**: Optimalisasi penyimpanan dan pengambilan data untuk performa terbaik.

## 🛠️ Teknologi yang Digunakan

Proyek ini dikembangkan menggunakan tumpukan teknologi modern untuk memastikan skalabilitas, keamanan, dan kinerja optimal:

* **Backend**:
    * **PHP**: Bahasa pemrograman utama.
    * **Laravel**: Framework PHP yang kuat dan elegan.
* **Database**:
    * **MySQL**: Sistem manajemen database relasional yang andal.
* **Frontend**:
    * **HTML5**: Struktur dasar halaman web.
    * **CSS3**: Styling dan desain responsif.
    * **JavaScript**: Interaktivitas dan fungsionalitas dinamis.
    * **[Tambahkan Framework CSS/JS jika ada, misal: Bootstrap/Tailwind CSS, Vue.js/React.js]**

## ⚙️ Persyaratan Sistem

Untuk menjalankan aplikasi ini di lingkungan lokal Anda, pastikan Anda memiliki:

* **PHP** versi `8.1` atau lebih tinggi.
* **Composer** (Manajer Dependensi PHP).
* **Node.js** dan **npm** (atau Yarn) untuk kompilasi aset frontend.
* **MySQL** Database Server.
* Server web seperti **Apache** atau **Nginx**.

## 🚀 Cara Instalasi

Ikuti langkah-langkah berikut untuk mengatur dan menjalankan proyek Pondok Makan Kang Naryo di mesin lokal Anda:

1.  **Clone Repositori:**
    Buka terminal atau Git Bash Anda dan jalankan perintah berikut:
    ```bash
    git clone [https://github.com/phannstastic/Pondok-Makan-Kang-Naryo.git](https://github.com/phannstastic/Pondok-Makan-Kang-Naryo.git)
    cd Pondok-Makan-Kang-Naryo
    ```

2.  **Instal Dependensi Composer:**
    ```bash
    composer install
    ```

3.  **Salin File Environment:**
    Buat salinan file `.env.example` dan beri nama `.env`:
    ```bash
    cp .env.example .env
    ```

4.  **Konfigurasi Database:**
    Buka file `.env` yang baru dibuat dan sesuaikan kredensial database Anda:
    ```dotenv
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=nama_database_anda_disini # Ganti dengan nama database yang Anda inginkan
    DB_USERNAME=username_database_anda # Ganti dengan username database Anda
    DB_PASSWORD=password_database_anda # Ganti dengan password database Anda
    ```

5.  **Buat Key Aplikasi:**
    Ini akan menghasilkan kunci unik untuk aplikasi Laravel Anda:
    ```bash
    php artisan key:generate
    ```

6.  **Jalankan Migrasi Database:**
    Perintah ini akan membuat semua tabel yang diperlukan di database Anda:
    ```bash
    php artisan migrate
    ```

7.  **Seed Data (Opsional):**
    Jika Anda memiliki data awal atau data dummy (misalnya, akun admin default), Anda bisa menjalankannya:
    ```bash
    php artisan db:seed
    ```

8.  **Instal Dependensi NPM dan Kompilasi Aset Frontend:**
    ```bash
    npm install
    npm run dev # Untuk pengembangan (dengan hot-reloading)
    # ATAU
    npm run build # Untuk kompilasi aset siap produksi
    ```

9.  **Jalankan Server Lokal Laravel:**
    ```bash
    php artisan serve
    ```
    Aplikasi sekarang akan tersedia di browser Anda, biasanya di `http://127.0.0.1:8000`.

## 🤝 Kontribusi

Kami sangat menghargai setiap bentuk kontribusi untuk pengembangan Pondok Makan Kang Naryo! Jika Anda ingin berkontribusi, silakan ikuti panduan berikut:

1.  Fork repositori ini.
2.  Buat branch baru untuk fitur atau perbaikan Anda (`git checkout -b feature/nama-fitur-baru` atau `bugfix/perbaikan-bug`).
3.  Lakukan perubahan Anda dan pastikan kode bersih serta terdokumentasi.
4.  Commit perubahan Anda (`git commit -m 'Deskripsi singkat perubahan'`).
5.  Push ke branch Anda (`git push origin nama-branch-anda`).
6.  Buka Pull Request ke branch `main` repositori ini.

## 📧 Tim

* **Project Manager**: Yusep Fathul Anwar
* **System Analyst**: Muhammad Rozaky Muthohar
* **UI/UX**: Muhammad Ghozali Akbar & Muhammad Alif Ramadhani
* **Front End**: Muhammad Alif Ramadhani & Muhammad Ghozali Akbar
* **Back End**: Muhammad Irfan Trinugroho
* **Quality Assurance**: Muhammad Irfan Trinugroho
* **Deployment**: Yusep Fathul Anwar, Muhammad Alif Ramadhani & Muhammad Rozaky Muthohar
