# Analisis Penjualan & Profitabilitas Superstore Menggunakan Excel

![Screenshot Dashboard](dashboard-superstore.png)

## 1. Ringkasan Proyek (Objective)
Proyek ini adalah analisis mendalam data penjualan "Superstore" selama empat tahun. Tujuannya adalah untuk mengidentifikasi tren utama, kategori produk dengan kinerja terbaik dan terburuk, serta menganalisis dampak strategi diskon terhadap profitabilitas.

Analisis ini dilakukan 100% di Microsoft Excel, dari pembersihan data hingga pembuatan dashboard interaktif.

---

## 2. Proses dan Tools
* **Tools:** Microsoft Excel
* **Pembersihan Data:** Menggunakan **Power Query** untuk:
    * Mengimpor dan menggabungkan data.
    * Membersihkan kolom yang tidak relevan (seperti kolom `Market2` dan `记录数`).
    * Memperbaiki tipe data yang salah (terutama `Order Date` dan kolom numerik seperti `Profit` dan `Sales`).
* **Analisis Data:** Menggunakan **PivotTable** untuk meringkas dan menganalisis data berdasarkan berbagai dimensi.
* **Visualisasi & Dashboard:**
    * Membuat 4 **PivotChart** utama (Bar, Column, dan Line chart).
    * Membangun dashboard interaktif dengan menghubungkan semua chart ke **Slicer** (filter) untuk `Region`.

---

## 3. Temuan Kunci & Insight (Key Findings)

Analisis ini menghasilkan beberapa temuan bisnis yang krusial:

1.  **"Tables" (Meja) Merugi:** Ditemukan bahwa sub-kategori `Tables` adalah satu-satunya produk yang merugi secara signifikan, dengan total kerugian **-$64,083**.
2.  **Diskon adalah Akar Masalah:** Grafik `Profit vs. Discount` menunjukkan bahwa profit anjlok dan menjadi negatif secara drastis ketika level diskon mencapai **30% (0.3) ke atas**.
3.  **Wilayah 'Central' Paling Efisien:** Wilayah `Central` tidak hanya menghasilkan `Sales` tertinggi tetapi juga `Profit` tertinggi, menjadikannya wilayah paling efisien.
4.  **Profit Tipis di 'Office Supplies':** Meskipun `Technology` adalah kategori paling menguntungkan, `Office Supplies` memiliki profit per barang (Profit/Quantity) yang paling tipis.

---

## 4. Rekomendasi Bisnis

Berdasarkan temuan di atas, berikut adalah beberapa rekomendasi:
1.  **Tinjau Ulang Strategi Diskon:** Segera hentikan atau tinjau ulang strategi pemberian diskon di atas 20% (0.2), terutama untuk sub-kategori `Tables`.
2.  **Investigasi 'Tables':** Lakukan analisis lebih lanjut pada `Tables` untuk menentukan apakah ini adalah strategi "loss leader" yang disengaja atau murni produk yang gagal.
3.  **Fokus pada Wilayah 'Central':** Terapkan strategi yang sukses di wilayah `Central` ke wilayah lain yang kinerjanya kurang.
