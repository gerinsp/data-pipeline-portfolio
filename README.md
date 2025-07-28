# 📁 Portfolio – Gerin Sena Pratama

**AI Engineer | Web Developer**

---

## 📇 OLTP to OLAP Data Pipeline Migration

**Perusahaan:** PT Trans Berjaya Khatulistiwa  
**Periode:** 2025

### 📝 Deskripsi Proyek
Merancang arsitektur data warehouse untuk memisahkan beban transaksi (OLTP) dan analitik (OLAP), serta mempercepat proses agregasi jutaan baris data penumpang harian.

### 🔧 Peran & Kontribusi
- Membangun batch ETL pipeline menggunakan **Apache Airflow** untuk migrasi data dari **MySQL (OLTP)** ke **ClickHouse (OLAP)**
- Menyusun skema warehouse untuk kebutuhan analitik dan dashboard
- Meneliti dan merancang **CDC (Change Data Capture)** pipeline menggunakan **Debezium + Kafka** (dalam tahap pengujian)

**Teknologi:** Apache Airflow, ClickHouse, MySQL, Kafka, Debezium  
**Hasil:** Masih dalam proses, tapi untuk eksperimen awal, kecepatan eksekusi query meningkat hingga 100%

---

## 🚍 Passenger Volume Forecasting System

**Perusahaan:** PT Trans Berjaya Khatulistiwa  
**Periode:** Agustus 2024 – Sekarang

### 📝 Deskripsi Proyek
Membangun sistem prediksi jumlah penumpang shuttle secara harian, lengkap dengan workflow pelatihan model, pelacakan eksperimen, deployment, dan orkestrasi.

### 🔧 Peran & Kontribusi
- Melatih model time series dengan **Prophet** berdasarkan data historis volume penumpang
- Melacak dan membandingkan eksperimen menggunakan **MLflow** (metrics, artifacts, params)
- Mengembangkan API prediksi menggunakan **FastAPI**
- Menyimpan model dan output sebagai artifacts ke **MinIO**
- Menjadwalkan pipeline training menggunakan **Prefect**

**Teknologi:** Prophet, MLflow, FastAPI, MinIO, Prefect  
**Hasil:**  
Model digunakan manajemen untuk laporan dan estimasi operasional harian  
- **RMSE:** 711.15  
- **MAPE:** 18.54%  
- **R² Score:** 0.5676

---

## 📈 MovieLens Data Pipeline Optimization

**Proyek:** Freelance  
**Periode:** 2025

### 📝 Deskripsi Proyek
Mengoptimalkan proses ETL dan analisis data skala besar (10 juta record) menggunakan pendekatan paralel.

### 🔧 Peran & Kontribusi
- Melakukan tuning konfigurasi memory, paralelisasi dan optimasi code untuk efisiensi

**Teknologi:** PySpark  
**Hasil:** Proses data dipercepat dari >1 jam menjadi 35 menit

---

## 📊 Data Summary Pipeline & Dashboard Integration

**Perusahaan:** PT Transa Berjaya Khatulistiwa  
**Periode:** 2024

### 📝 Deskripsi Proyek
Membangun sistem integrasi dan penyediaan data untuk dashboard analitik yang digunakan oleh tim data analyst dan operator internal.

### 🔧 Peran & Kontribusi
- Membuat pipeline ETL dengan **Apache Airflow** untuk mengambil dan merangkum data dari MySQL ke database khusus summary
- Menyediakan tabel summary untuk tim data analyst membangun dashboard di **Apache Superset**
- Mengembangkan sistem **embed Superset dashboard** ke dalam aplikasi **Laravel**, termasuk pengaturan akses berbasis role
- Menjembatani integrasi antara tim data dan operator pengguna akhir

**Teknologi:** Apache Airflow, Laravel, MySQL, Apache Superset, JWT  
**Hasil:** Dashboard Superset dapat diakses langsung dari Laravel oleh puluhan operator dengan akses sesuai peran, tanpa perlu login ulang

---

## 🔧 Skill Ringkasan

- **ETL & Workflow:** Apache Airflow, Prefect, Kafka, Debezium  
- **Data & Storage:** MySQL, ClickHouse, MinIO  
- **Machine Learning:** Prophet, MLflow, TensorFlow  
- **API & Serving:** FastAPI, Docker, Laravel  
- **Visualization:** Superset, Matplotlib  
- **Tools:** Git

---

## 🗣️ Languages

- Bahasa Indonesia – Native  
- English – Actively learning (Beginner proficiency)  
