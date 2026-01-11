JUDUL PROYEK: SISTEM INFERENSI FUZZY PENENTUAN PRIORITAS PELANGGAN

Aditya Dwi Aryanto (103132400027)

Fauzi Romadhoni (103132400025)

DESKRIPSI PROGRAM Program ini merupakan implementasi sistem logika fuzzy untuk menentukan tingkat prioritas pelanggan berdasarkan data kepuasan dan perilaku pembelian. Sistem dibangun menggunakan bahasa pemrograman Python tanpa melibatkan library sistem fuzzy eksternal. Program melakukan pemrosesan data mulai dari pembacaan berkas, perhitungan derajat keanggotaan, inferensi aturan, hingga defuzzifikasi untuk menghasilkan skor kelayakan numerik.

STRUKTUR BERKAS

TubesAI.ipynb: Kode sumber implementasi logika fuzzy.

customer_satisfaction_data.csv: Dataset input berisi informasi kepuasan dan jumlah pembelian.

hasil_fuzzy_pelanggan.csv: Berkas keluaran yang dihasilkan setelah program dijalankan.

TAHAPAN IMPLEMENTASI

Membaca data: Program mengekstrak nilai Satisfaction Score dan Purchase Amount dari berkas CSV serta menangani data yang hilang atau duplikat.

Fuzzification: Mengonversi nilai numerik menjadi variabel linguistik (kepuasan dan transaksi).

Inferensi: Menerapkan aturan logika fuzzy untuk menentukan kategori prioritas.

Defuzzification: Menghitung skor akhir menggunakan metode rata-rata terbobot Sugeno.

Output: Menyimpan hasil analisis ke file eksternal.
