Analisis Penjualan E-Commerce UK (2010–2011)

Project Overview
Proyek ini bertujuan menganalisis data penjualan e-commerce di UK pada periode 1 Desember 2010 – 9 Desember 2011.  
Analisis dilakukan untuk menemukan pola penjualan, produk terlaris, tren waktu pembelian, serta memberikan rekomendasi bisnis yang dapat meningkatkan pendapatan.  

Dataset yang digunakan berasal dari [Kaggle - E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)igunakan untuk membantu eksplorasi data, visualisasi, dan perhitungan metrik bisnis.

Dataset
- Sumber: [Kaggle - E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- Jumlah baris awal: 541.909
- Jumlah baris setelah cleaning: 392.692
- Kolom:
  - `InvoiceNo` (nomor faktur)
  - `StockCode` (kode produk)
  - `Description` (nama produk)
  - `Quantity` (jumlah unit)
  - `InvoiceDate` (tanggal transaksi)
  - `UnitPrice` (harga per unit)
  - `CustomerID` (ID pelanggan)
  - `Country` (negara pelanggan)


 Data Cleaning
1. Menghapus baris dengan `CustomerID` kosong.
2. Menghapus data dengan `Quantity <= 0` (retur barang).
3. Menghapus data dengan `UnitPrice <= 0`.
4. Mengubah `InvoiceDate` menjadi format datetime.
5. Menghapus duplikat data.


 Insight & Findings
1. Produk Terlaris:  
   - `PAPER CRAFT , LITTLE BIRDIE` memimpin penjualan unit (80.995 unit) dan revenue transaksi terbesar (£168.469,6).
   - Produk dekorasi rumah seperti `MEDIUM CERAMIC TOP STORAGE JAR` dan `WORLD WAR 2 GLIDERS ASSTD DESIGNS` juga populer.

2. Tren Waktu:  
   - Puncak penjualan pada bulan November (£1.156.205) dan Desember (£1.087.613).
   - Bulan Februari (£446.084) dan April (£468.374) adalah periode dengan revenue terendah.

3. Pelanggan Grosir:  
   - Terdapat transaksi dengan quantity sangat besar yang mengindikasikan pesanan grosir.


 Rekomendasi Bisnis
1. Perkuat Stok & Promosi Menjelang Akhir Tahun  
   - Fokus bulan Oktober–Desember untuk stok dan kampanye pre-holiday sale.

2. Strategi Low Season  
   - Diskon & bundling di bulan Februari & April.
   - Gunakan pemasaran email untuk mendorong repeat purchase.

3. Segmentasi Pelanggan Grosir  
   - Identifikasi bulk buyer dan tawarkan kontrak jangka panjang.

4. Diversifikasi Produk Laris  
   - Promosikan produk dekorasi rumah lain untuk mengurangi ketergantungan pada satu produk.


 AI Support Explanation
- Pandas & Matplotlib untuk eksplorasi dan visualisasi data.
- AI (ChatGPT/LLM) digunakan untuk:
  - Membuat ringkasan insight
  - Menyusun rekomendasi bisnis
  - Menyusun format laporan


 Link Proyek
- Google Colab Notebook: [link_notebook](https://colab.research.google.com/drive/1fDjDbg7SjfTS9xv12r0ipW7bMDTyUnhA?authuser=3#scrollTo=7dWlRBe4AyJU)
- GitHub Repository: [link_github](https://github.com/bbkoyek/ecommerce-uk-analysis.git)
- Dataset: [link_dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
