# Klasifikasi Jamur: Dapat Dimakan vs. Beracun (Kaggle)
## Proyek Kompetisi OmahTI Data Royale 2025

Proyek ini adalah entri saya untuk kompetisi Data Royale Kaggle yang diselenggarakan oleh OmahTI. Tujuannya adalah untuk membangun model *machine learning* yang dapat memprediksi secara akurat apakah suatu jamur dapat dimakan (*edible*) atau beracun (*poisonous*) berdasarkan fitur-fitur fisiknya.

Model final LightGBM berhasil mencapai **akurasi 99.75% ** pada *test set 30%*.

---

## 💻 Tumpukan Teknologi (Tech Stack)

* **Python:** Bahasa pemrograman utama.
* **Jupyter Notebook:** Untuk analisis interaktif dan *storytelling*.
* **Pandas:** Untuk manipulasi dan pembersihan data (Data Preprocessing).
* **Scikit-learn (Sklearn):** Untuk *preprocessing*, *feature engineering*, dan *modeling*.
* **Matplotlib / Seaborn:** Untuk visualisasi data (Exploratory Data Analysis).

---

## 🚀 Alur Kerja Proyek (Project Workflow)

Proses dari data mentah hingga prediksi model mengikuti langkah-langkah berikut:

1.  **Eksplorasi Data (EDA):** Menganalisis dataset untuk memahami distribusi fitur, mengidentifikasi korelasi, dan memvisualisasikan hubungan antara fitur dan variabel target (beracun/tidak).
2.  **Pra-pemrosesan Data (Data Preprocessing):**
    * Menangani nilai yang hilang (*missing values*) dengan KNN Imputer.
    * Melakukan *Feature Encoding* Label Encoder untuk mengubah semua fitur kategorikal menjadi format numerik yang dapat dipahami oleh model.
3.  **Seleksi Model & Pelatihan:**
    * Membagi data menjadi set Latih (*train*) dan set Uji (*test*).
    * Melatih dan membandingkan beberapa model klasifikasi, seperti:
        * Linear Model (Decision Tree, KKN, Logistic Regression)
        * Advanced Gradient Boosting Model (XGBoost, CatBoost, LightGBM)
4.  **Evaluasi Model:** Mengevaluasi setiap model menggunakan metrik seperti **
