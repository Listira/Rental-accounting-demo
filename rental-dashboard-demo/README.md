# RentalPro — Dashboard Manajemen Rental Kendaraan

Demo/portfolio version. Single-file web app (HTML/CSS/JS, no backend) untuk mengelola
operasional & keuangan perusahaan rental kendaraan: Armada, Penyewaan, Invoice, Bunga Leasing,
Penyewa, Jurnal Umum (GL), Laporan Keuangan (Neraca/Laba Rugi/Trial Balance), dan Pajak (CIT).

Data tersimpan di `localStorage` browser (opsional: hubungkan ke file `data.json` lokal
via File System Access API untuk auto-save). Semua data pada versi ini adalah **placeholder/dummy**
— tidak ada data perusahaan, pelanggan, atau keuangan nyata.

## Coba langsung
Buka `index.html` di Chrome/Edge, lalu klik **"Isi Data Dummy Tahun Berjalan"** di halaman
Data & Backup untuk mengisi contoh data (armada, penyewaan, invoice, leasing, penyewa, jurnal)
secara otomatis.

## Tech
Vanilla JS, Chart.js untuk grafik dashboard, tanpa dependency build tool — bisa langsung
dibuka sebagai file statis atau dihost via GitHub Pages.
