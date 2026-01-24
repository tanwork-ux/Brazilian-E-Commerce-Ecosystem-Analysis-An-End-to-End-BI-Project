# 📊 Olist Marketing Funnel Analysis
**Analyzing Lead-to-Deal Conversion & Marketing Performance**

## 📝 Project Overview
Proyek ini bertujuan untuk menganalisis efisiensi *marketing funnel* dari dataset Olist. Fokus utamanya adalah memahami bagaimana performa konversi dari Leads (MQL) menjadi Closed Deals serta mengidentifikasi tren bulanan selama periode 2017-2018.

## 🛠️ Tech Stack
* **Python (Pandas):** Data Cleaning, Merging, & Pre-processing.
* **Power BI:** Data Modeling, DAX, & Interactive Dashboarding.

## 📁 Repository Structure
```text
📂 Data
 ├── 📂 raw          # Dataset asli (MQL & Closed Deals)
 └── 📂 cleaned      # Dataset hasil olahan Python (ready for BI)
📂 Notebook          # Jupyter Notebook / Python script (.py)
📂 Dashboard         # File Power BI (.pbix)
📂 Visualisasi       # Screenshot dashboard untuk dokumentasi
```

## 📈 Key Insights

   Conversion Rate (CR): Rata-rata konversi stabil di angka 10.53%.

   Peak Season: Bulan April menunjukkan volume leads tertinggi, namun perlu diimbangi dengan kapasitas sales.

   Anomali: Terdapat penurunan drastis pada bulan Juni, yang terdeteksi secara otomatis melalui sistem pewarnaan dinamis pada dashboard.

## 💡 Business Recommendations

   Berdasarkan hasil analisis, berikut adalah beberapa strategi yang disarankan:

   Optimasi Leads di Bulan April: Karena volume leads memuncak di bulan April, tim sales harus dipersiapkan dengan kapasitas ekstra agar respon tetap cepat dan Conversion Rate tidak turun.

   Investigasi Anomali Leads dan Conversion Rate: Terjadi penurunan volume leads sejak Juni yang stagnan hingga Desember dan diikuti anjloknya conversion rate pada periode Juni-Desember. Perlu dilakukan audit pada kanal marketing di bulan Juni untuk mengidentifikasi penyebab turunnya performa secara drastis 

   Segmentasi Leads: Disarankan untuk memprioritaskan leads dari kanal yang memiliki historis konversi di atas rata-rata (10.53%) guna menekan biaya akuisisi (CAC).

   Retensi Seller: Mengingat hanya sekitar 10% leads yang menjadi seller, tim onboarding perlu menyederhanakan proses pendaftaran agar mengurangi hambatan (friction) bagi calon seller baru.

## 📊 Dashboard Preview

![Dashboard](Visualisasi/General.png)
💡 Key Features (Power BI)

   Dynamic Measures: Perhitungan CR otomatis menggunakan DAX yang menangani data null secara akurat.

   Interactive Slicers: Filter berdasarkan bulan untuk melihat tren secara mendalam.

🚀 How to Run

   Data Cleaning: Jalankan file di folder ![Notebook](Notebook) untuk melihat proses pembersihan data.

   Dashboard: Download file di folder ![Dashboard](Dashboard) dan buka menggunakan Power BI Desktop.
