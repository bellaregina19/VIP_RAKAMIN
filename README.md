# Virtual Internship Program : Big Data Analytics - Kimia Farma

## Deskripsi Singkat
Program Virtual Internship "Big Data Analytics - Kimia Farma" adalah program magang daring yang bertujuan memberikan pengalaman praktis dalam pengolahan dan analisis data skala besar di domain farmasi. Peserta akan belajar pipeline data end-to-end: pengumpulan data, pembersihan dan transformasi (ETL), pemrosesan menggunakan teknologi big data (mis. Apache Spark), eksplorasi data (EDA), hingga pembuatan model dan visualisasi.

## Tools dan Dataset
Berikut adalah daftar tools utama yang digunakan beserta link dokumentasinya:

- Python — https://www.python.org/
- Jupyter Notebook / JupyterLab — https://jupyter.org/
- Apache Spark — https://spark.apache.org/
- PySpark (Python API for Spark) — https://spark.apache.org/docs/latest/api/python/
- Hadoop (opsional, untuk penyimpanan/distribusi) — https://hadoop.apache.org/
- Pandas — https://pandas.pydata.org/
- scikit-learn — https://scikit-learn.org/
- Docker — https://www.docker.com/
- Git & GitHub — https://github.com/

Dataset:

- Contoh publik (Kaggle - datasets): https://www.kaggle.com/datasets
- Placeholder khusus Kimia Farma: (silakan unggah dataset resmi ke folder `data/` di repo ini dan ganti link ini). Jika Anda memiliki tautan internal/privat, ganti dengan tautan akses internal Anda.

Catatan: Pastikan data sensitif atau pribadi di-handle sesuai kebijakan privasi dan regulasi (mis. data pasien harus dianonimkan).

## Struktur Program (Garis Besar)
- Data Ingestion: Mengambil data dari sumber (CSV, database, API) dan menyimpannya di storage terpusat.
- ETL / Data Cleaning: Normalisasi, handling missing values, transformasi fitur.
- Big Data Processing: Gunakan Apache Spark/PySpark untuk pemrosesan skala besar.
- Analisis & Modeling: EDA, fitur rekayasa, training model ML untuk prediksi/klasifikasi/regresi.
- Visualisasi & Dashboard: Laporan interaktif untuk stakeholder.

## Gambar Arsitektur
Di bawah ini terdapat diagram arsitektur pipeline (file terlampir):

![Diagram Arsitektur Pipeline](assets/diagram.svg)

## Penjelasan Gambar
1. Sumber Data: Berisi dataset raw (mis. transaksi apotek, inventory, farmasi klinis).
2. Ingestion: Proses pengambilan data (batch atau streaming) dan menaruhnya ke storage terpusat (HDFS, S3, atau file server).
3. Storage / Raw Zone: Lokasi penyimpanan data mentah sebelum transformasi.
4. ETL / Processing: Menggunakan Spark untuk transformasi skala besar — pembersihan, agregasi, dan pembuatan tabel terstruktur.
5. Analytical Zone / Data Warehouse: Hasil transformasi yang siap untuk analisis dan pemodelan.
6. Modeling & ML: Tahap pembuatan dan deployment model machine learning.
7. Visualization & Reporting: Dashboard untuk pemangku kepentingan (Grafana, Superset, Tableau).

## Cara Mulai
1. Clone repo: git clone https://github.com/bellaregina19/VIP_RAKAMIN.git
2. Siapkan environment (contoh menggunakan venv atau conda) dan install dependensi.
3. Letakkan dataset di folder `data/`.
4. Buka notebook di `notebooks/` (jika tersedia) dan jalankan langkah-langkah ETL.

## Kontribusi
Silakan buka issue atau submit PR untuk menambahkan notebook, script ETL, atau dataset contoh. Jika ingin menambahkan dataset resmi Kimia Farma, harap lampirkan deskripsi sumber dan lisensi data.

---

*README ini dibuat otomatis oleh asisten. Silakan sesuaikan link dataset internal, lisensi, dan instruksi menjalankan sesuai kebutuhan proyek.*