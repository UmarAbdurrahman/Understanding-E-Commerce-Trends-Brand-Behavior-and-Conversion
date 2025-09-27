# 📊 Understanding E-Commerce Trends: Brand, Behavior, and Conversion

## 📌 Deskripsi Proyek

Industri e-commerce terus berkembang pesat, sehingga perusahaan perlu memahami **perilaku konsumen** secara mendalam.
Proyek ini menganalisis **data aktivitas pengguna** (view, add to cart, purchase) dari dataset publik [Kaggle: E-Commerce Events History in Electronics Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-electronics-store/data).

Analisis dilakukan untuk:

* Mengidentifikasi pola belanja konsumen berdasarkan waktu, produk, dan kategori.
* Mengukur konversi dari **View → Cart → Purchase**.
* Menilai kontribusi kategori/brand terhadap penjualan.
* Mengevaluasi strategi harga & promosi.

---

## 🛠️ Tools & Teknologi

* **Python** (Pandas, Matplotlib, Seaborn) → Data preprocessing & EDA
* **Power BI** → Dashboard visualisasi interaktif
* **Jupyter Notebook** → Eksperimen & dokumentasi analisis

---

## ❓ Problem Statement

1. Bagaimana pola perilaku konsumen berdasarkan events (view, cart, purchase) dan tren musiman?
2. Brand mana yang paling sering dilihat dan berkontribusi besar terhadap profit?
3. Bagaimana tren aktivitas konsumen dari waktu ke waktu (bulanan)?
4. Berapa tingkat konversi dari View → Cart → Purchase, dan di tahap mana hambatan terbesar terjadi?

---

## 🎯 Tujuan Proyek

* Memahami pola perilaku konsumen berdasarkan aktivitas (view, cart, purchase).
* Mengukur conversion rate pada setiap tahap funnel belanja.
* Mengidentifikasi brand dominan & kontribusinya terhadap profit.
* Memberikan rekomendasi strategi bisnis untuk meningkatkan **konversi & profit e-commerce**.

---

## 📂 Data Understanding

* **Jumlah data**: 885,129 rows × 9 columns
* **Fitur utama**:

  * `event_time`
  * `event_type`
  * `product_id`
  * `category_id`
  * `category_code`
  * `brand`
  * `price`
  * `user_id`
  * `user_session`

---

## 🔎 Exploratory Data Analysis (EDA) - Insight Utama

* Aktivitas user **puncak di Okt–Jan** (holiday season). Setelah itu menurun signifikan di Feb 2021.
* **Distribusi event**:

  * View: 89.67%
  * Cart: 6.11%
  * Purchase: 4.22%
* **Top Brands**: ASUS, MSI, Gigabyte → menyumbang >190M profit.
* **Conversion Funnel**:

  * View → Cart: 9.08%
  * Cart → Purchase: 57.6%
  * View → Purchase (Overall): 5.24%

---

## 💡 Business Recommendations

* **Funnel Optimization**: Tingkatkan View → Cart dengan rekomendasi personal, bundling, & strategi harga kompetitif.
* **Seasonal & Promo**: Fokuskan kampanye besar di Okt–Jan, buat program loyalitas agar interest tidak drop.
* **Brand Strategy**: Prioritaskan brand utama (ASUS, MSI, Gigabyte), sambil meningkatkan awareness mid-tier brands.
* **UX Improvement**: Perbaiki proses checkout, tambahkan fitur wishlist/save cart.
* **Monitoring & Segmentation**: Analisis lebih lanjut segmen user (frequent buyer vs one-time buyer).

---

## 📊 Dashboard Power BI

Proyek ini juga dilengkapi dengan **Power BI Dashboard** untuk memvisualisasikan insight utama.

---

## ✅ Kesimpulan

* Aktivitas user didominasi **View (90%)**, namun konversi keseluruhan masih rendah (5.2%).
* **ASUS, MSI, Gigabyte** adalah brand dengan kontribusi terbesar pada profit.
* Aktivitas puncak terjadi di **Oktober–Januari** → strategi musiman sangat penting.
* Hambatan utama ada di tahap **View → Cart**, sehingga butuh optimasi funnel sejak awal.

---
