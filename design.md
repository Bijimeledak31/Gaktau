# Sistem Manajemen Gudang - Desain Dasar

## 1. Halaman Login

*   **Tujuan:** Mengizinkan pengguna admin dan staf untuk mengakses sistem secara aman.
*   **Elemen:**
    *   Kolom nama pengguna
    *   Kolom kata sandi
    *   Tombol login
    *   (Opsional) Tautan "Lupa Kata Sandi"

## 2. Dasbor Admin

*   **Tujuan:** Memberikan gambaran umum operasi gudang dan akses ke fungsi-fungsi utama.
*   **Item Menu:**
    *   **Dasbor:** Menampilkan metrik dan ringkasan utama (misalnya, peringatan stok rendah, transaksi terbaru).
    *   **Item:** Mengelola item/produk gudang.
        *   Menambahkan item baru
        *   Mengedit item yang ada
        *   Melihat detail item (level stok, deskripsi, dll.)
        *   Mengategorikan item
        *   **Lokasi Item:** Menentukan lokasi fisik item di dalam gudang (contoh: Ruangan A-Rak 1-Level 2). Ini menggunakan sistem hierarkis: Ruangan-Rak-Level.
    *   **Transaksi:** Menangani transaksi masuk dan keluar.
        *   **Masuk:** Mencatat item yang masuk (misalnya, dari pemasok).
            *   Menggunakan pemindai barcode untuk mempercepat proses input data.
        *   **Keluar:** Mencatat item yang keluar (misalnya, pesanan pelanggan).
            *   Menggunakan pemindai barcode untuk mempercepat proses input data.
    *   **Laporan:** Menghasilkan laporan tentang inventaris, transaksi, dan data relevan lainnya.

## 3. Interaksi Dasar

*   **Login:** Pengguna memasukkan kredensial mereka di halaman login. Login yang berhasil mengarahkan mereka ke Dasbor Admin.
*   **Navigasi:** Pengguna menavigasi sistem menggunakan item menu di Dasbor Admin.
*   **Manajemen Item:** Pengguna dapat menambah, mengedit, dan melihat detail item di dalam bagian "Item".
*   **Manajemen Transaksi:** Pengguna dapat mencatat transaksi masuk dan keluar di bagian masing-masing di bawah "Transaksi".
*   **Pelaporan:** Pengguna dapat menghasilkan dan melihat laporan di bagian "Laporan".