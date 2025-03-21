# Project 2 - Data Engineering


## 🧱 Layer Penjelasan

- **ODS (Operational Data Store):**  
  Menyimpan data hasil ekstraksi dari sistem operasional tanpa transformasi. Digunakan untuk backup dan audit trail.

- **RAW:**  
  Data mentah yang dimuat dari ODS ke dalam format yang dapat diolah lebih lanjut. Tidak ada perubahan pada struktur datanya.

- **Intermediate:**  
  Lapisan transformasi awal. Data dibersihkan, distandardisasi, dan disiapkan untuk pembuatan mart. Biasanya digunakan untuk logika bisnis seperti joins, agregasi ringan, dll.

- **Mart:**  
  Merupakan data siap konsumsi untuk analisis atau visualisasi. Berisi tabel-tabel seperti fact dan dimension (misalnya: `fact_sales`, `dim_customer`, dll).

## ⚙️ Tools yang Digunakan

- **DBT**: Untuk transformasi data SQL secara modular dan terstruktur.
- **PostgreSQL**: Sebagai database utama untuk menyimpan dan memproses data.

## 📝 Cara Menjalankan

1. Clone repository:
   ```bash
   git clone https://github.com/restifams/project2.git
   cd project2


## Author
- indah dwi resti
- restifams@gmail.com / LinkedIn
