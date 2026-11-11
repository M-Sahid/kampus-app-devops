# Optimasi Halaman KRS

## Perubahan
- Menambahkan cache (Redis) untuk daftar mata kuliah
- Mengoptimalkan kueri daftar kelas dengan indeks database
- Menambahkan pengujian beban untuk 5.000 pengguna bersamaan

## Hasil yang diharapkan
- Waktu respons p95 di bawah 2 detik
- Beban database turun saat periode KRS
