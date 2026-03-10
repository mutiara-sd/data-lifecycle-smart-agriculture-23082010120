# Smart Agriculture Data Lifecycle Project

## Overview
Project ini merupakan implementasi dari konsep Data Lifecycle Management menggunakan dataset Smart Agriculture. Dataset ini berisi data sensor yang digunakan untuk memantau kondisi lingkungan dalam sistem pertanian pintar.

Tujuan dari analisis ini adalah untuk memahami hubungan antara beberapa parameter lingkungan seperti temperatur, kelembaban udara, dan kelembaban tanah terhadap kondisi pertumbuhan tanaman.

## Dataset
Dataset yang digunakan merupakan Smart Agriculture Sensor Data yang berisi beberapa atribut, antara lain:

- crop ID
- soil_type
- Seedling Stage
- MOI (Soil Moisture)
- temperature
- humidity
- result

Dataset diperoleh dari Kaggle dan disimpan dalam folder `data/raw`.

## Tools
Beberapa tools yang digunakan dalam project ini:

- Python
- Pandas
- Google Colab
- Power BI
- GitHub

## Data Lifecycle Process

### 1. Data Acquisition
Dataset diunduh dari Kaggle dan disimpan sebagai raw dataset dalam repository.

### 2. Data Processing
Proses eksplorasi data dilakukan menggunakan Python di Google Colab. Tahapan ini meliputi:
- Melihat statistik dasar dataset menggunakan `df.describe()`
- Mengecek missing values menggunakan `df.isnull().sum()`
- Membersihkan data jika diperlukan

Dataset yang telah diproses kemudian disimpan sebagai `cleaned_data.csv`.

### 3. Data Analysis
Analisis dilakukan untuk memahami hubungan antara variabel seperti temperature, humidity, dan soil moisture yang dapat mempengaruhi kondisi pertumbuhan tanaman.

### 4. Data Visualization
Visualisasi data dibuat menggunakan Power BI untuk menampilkan informasi dalam bentuk dashboard. Beberapa visualisasi yang dibuat antara lain:
- Tren sensor temperature dan humidity
- Gauge meter untuk menampilkan nilai kelembaban
- Heatmap korelasi antar variabel
- Sistem alert berdasarkan threshold tertentu

## Data Quality
Berdasarkan hasil analisis:
- Dataset tidak memiliki missing values
- Data memiliki struktur yang baik untuk dianalisis lebih lanjut

## Conclusion
Berdasarkan hasil analisis yang dilakukan, dataset Smart Agriculture memiliki kualitas data yang baik dan dapat digunakan untuk memahami kondisi lingkungan dalam sistem pertanian pintar. Visualisasi dashboard membantu dalam mempermudah interpretasi data serta monitoring parameter sensor.


