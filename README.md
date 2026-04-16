# 🛍️ Customer Satisfaction & Sentiment Analysis (Amazon Reviews)

---

> ## 📦 Project Summary
>
> **Background**
> Tingginya nilai Customer Satisfaction (CSAT) tidak selalu mencerminkan pengalaman pelanggan yang konsisten di seluruh kategori produk. Untuk memahami akar masalah secara lebih mendalam, diperlukan analisis berbasis teks (customer reviews) untuk mengidentifikasi faktor utama yang memengaruhi kepuasan dan ketidakpuasan pelanggan.
>
> **Objective**
> Menganalisis customer reviews menggunakan pendekatan data analytics & text mining untuk:
>
> * Mengukur customer satisfaction (CSAT)
> * Mengidentifikasi sentiment pelanggan (Positive, Neutral, Negative)
> * Menggali Voice of Customer (VOC) & pain points
> * Menentukan faktor utama yang memengaruhi kepuasan pelanggan
>
> **Business Problem**
>
> * CSAT tinggi (±75.88%), tetapi tidak merata antar kategori
> * Beberapa kategori menunjukkan performa rendah (Home & Kitchen, Electronics)
> * Sulit mengidentifikasi root cause hanya dari rating numerik
>
> **Dataset Overview**
>
> * Source: Kaggle (Amazon Reviews Dataset)
> * ±1,455 cleaned data (dari 1,465 raw data)
> * 16 features (product info, rating, review text, category)
> * Tidak ada duplicate, missing value minimal & sudah ditangani
>
> **Approach**
>
> * Data Cleaning & Preprocessing
> * CSAT Scoring (rating ≥ 4 = satisfied)
> * Sentiment Analysis (NLTK – VADER)
> * Voice of Customer (VOC) & Keyword Extraction
> * Topic Modeling (LDA) untuk identifikasi tema utama
> * Exploratory Data Analysis (EDA) & Dashboard Visualization
>
> **Key Insights**
>
> * Overall CSAT tinggi (~75.88%), namun tidak konsisten antar kategori
> * **Home & Kitchen (67.79%)** → kategori dengan CSAT terendah
> * **Electronics (~74.71%)** juga relatif rendah dibanding kategori lain
> * Complaint utama:
>
>   * Product quality issues
>   * Poor performance / not working
>   * Battery & durability problems
> * Faktor harga → **tidak signifikan memengaruhi kepuasan**
> * Tema utama customer discussion:
>
>   * Quality
>   * Usability
>   * Value for money
>
> **Customer Behavior Insight**
>
> * Customer lebih peduli pada **fungsi & performa produk** dibanding harga
> * Negative sentiment didominasi oleh pengalaman produk yang tidak sesuai ekspektasi
> * VOC menunjukkan pola keluhan yang konsisten → indikasi masalah sistemik
>
> **Business Value**
>
> * 🎯 Mengidentifikasi driver utama dissatisfaction
> * 📉 Mengurangi negative reviews melalui perbaikan kualitas
> * 📊 Mendukung product & quality strategy berbasis data
> * 💰 Meningkatkan customer satisfaction & retention
>
> **Recommendations**
>
> * Tingkatkan standar kualitas produk (terutama kategori low CSAT)
> * Optimasi deskripsi produk (spesifikasi, performa, durability)
> * Berikan insentif untuk high-quality sellers
> * Monitoring keyword VOC sebagai early warning system
> * Remove / flag produk dengan defect rate tinggi
>
> **Dashboard Highlights**
>
> * CSAT distribution by category
> * Sentiment distribution (Positive / Neutral / Negative)
> * VOC keyword analysis (Top complaints & positive keywords)
> * Topic modeling insight untuk customer discussion themes
>
> **Conclusion**
> Customer satisfaction tidak hanya dipengaruhi oleh rating numerik, tetapi lebih oleh pengalaman nyata terhadap kualitas dan performa produk. Dengan memanfaatkan analisis sentiment dan VOC, perusahaan dapat mengidentifikasi root cause dissatisfaction dan mengambil tindakan yang lebih tepat sasaran.
>
> 📈 *Next Step:* Integrasi predictive model untuk mendeteksi produk berisiko tinggi terhadap negative reviews.
