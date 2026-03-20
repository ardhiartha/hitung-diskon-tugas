# Hitung Diskon Tugas

## Deskripsi
Project web sederhana berbasis PHP untuk menghitung total pembayaran pembelian buku dengan sistem diskon bertingkat, diskon member, dan perhitungan pajak (PPN).

## Fitur
- Perhitungan subtotal berdasarkan jumlah beli
- Sistem diskon bertingkat:
  - 1–2 item → 0%
  - 3–5 item → 10%
  - 6–10 item → 15%
  - >10 item → 20%
- Diskon tambahan 5% untuk member
- Perhitungan PPN 11%
- Menampilkan total akhir dan total penghematan
- Format mata uang Rupiah

## Teknologi
- PHP (Native)
- HTML
- Bootstrap 5

## Cara Menjalankan
1. Install XAMPP / Laragon
2. Simpan project di folder `htdocs`
3. Jalankan Apache
4. Buka di browser: http://localhost/nama-folder

## Alur Perhitungan
1. Hitung subtotal (harga × jumlah)
2. Tentukan diskon berdasarkan jumlah pembelian
3. Hitung diskon utama
4. Hitung diskon member (jika berlaku)
5. Hitung total setelah diskon
6. Tambahkan PPN 11%
7. Tampilkan total akhir dan total penghematan

## Tujuan
Project ini dibuat untuk memahami implementasi logika kondisi (if-else) dalam PHP serta simulasi perhitungan transaksi sederhana.

## Catatan
- Data masih bersifat statis (hardcoded)
- Belum menggunakan input user (form)
- Belum terhubung ke database

## Author
ardhiartha
