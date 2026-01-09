#Air Quality Prediction Using Linear Regression (SDG 13 - Climate Action)

Proyek ini merupakan tugas mata kuliah **Kecerdasan Buatan** yang bertujuan untuk memprediksi kadar **Karbon Monoksida (CO)** berdasarkan parameter lingkungan menggunakan algoritma **Linear Regression** yang dibangun dari nol (from scratch) tanpa menggunakan library Machine Learning seperti scikit-learn.

## Deskripsi Proyek
Kualitas udara merupakan indikator krusial dalam kesehatan masyarakat dan perubahan iklim. Polusi udara, termasuk emisi CO, berkontribusi pada efek rumah kaca. Proyek ini memberikan solusi berbasis data untuk memantau kadar polutan secara akurat menggunakan sensor lingkungan seperti suhu, kelembaban, dan gas polutan lainnya (NOx, NO2, O3).

## Fitur Utama
* **Implementation From Scratch**: Model Regresi Linear dibangun murni menggunakan aljabar linear (Numpy) tanpa library ML eksternal.
* **Data Splitting Manual**: Implementasi pembagian dataset training dan testing dilakukan secara manual.
* **Analisis Korelasi**: Menghitung hubungan antar variabel lingkungan terhadap konsentrasi CO.
* **Interpretasi Model**: Memberikan pemahaman yang mudah bagi non-teknisi melalui koefisien regresi.

## Dataset
* **Nama**: Air Quality Data Set
* **Sumber**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+Quality)
* **Periode**: Maret 2004 - April 2005
* **Jumlah Data**: ~9,358 entri
* **Fitur**: Suhu (T), Kelembaban (RH/AH), NOx, NO2, O3, dan sensor kimia lainnya.

## Metodologi
1.  **Exploratory Data Analysis (EDA)**: Pembersihan data dan penanganan missing values.
2.  **Feature Selection**: Memilih variabel yang memiliki korelasi kuat terhadap kadar CO.
3.  **Model Building**: Menggunakan persamaan normal atau gradient descent manual untuk mencari koefisien regresi.
4.  **Evaluation**: Mengukur performa model menggunakan metrik seperti Mean Squared Error (MSE) atau R-Squared.

## Cara Menjalankan
1. Unduh file `AI_PROJECT.ipynb` dari repositori ini.
2. Jalankan file menggunakan Google Colab atau Jupyter Notebook.
3. Jalankan setiap sel dari atas ke bawah untuk melihat hasil analisis dan grafik.

## Video Presentasi
Penjelasan lengkap pada video berikut:
👉 **[Link Video Presentasi YouTube](https://www.youtube.com/watch?v=cgMChROV-8A)**

---
**Disusun Oleh:**
- Hayunitya Edadwi Pratita (23/518670/TK/57134)  
- Desi D Simamora (23/514990/TK/56564)  
