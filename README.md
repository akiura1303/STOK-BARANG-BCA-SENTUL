# STOK-BARANG-BCA-SENTUL

Aplikasi Android native Java untuk pencatatan stok material dan alat proyek.

## Build APK
GitHub Actions akan membangun APK otomatis setiap push ke branch `main`.
Buka tab **Actions**, pilih workflow **Android CI**, lalu unduh artifact
`STOK-BARANG-BCA-SENTUL-APK`.

## Fitur versi awal
- Master data material dan alat (SQLite lokal)
- Data awal material dan alat proyek
- Tambah master data
- Transaksi stok masuk dan keluar
- Validasi agar stok tidak minus
- Laporan stok dan riwayat transaksi
- Ekspor laporan stok ke CSV

Package: `com.bca.stokbarang`
Minimum Android: 6.0 (API 23)
