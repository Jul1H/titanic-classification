#  Titanic Survival Prediction

Project Machine Learning untuk memprediksi kemungkinan keselamatan penumpang kapal Titanic berdasarkan profil mereka (usia, jenis kelamin, kelas tiket, dll.).

##  Deskripsi Project

Project ini menganalisis dataset historis penumpang Titanic dan membangun model klasifikasi untuk memprediksi siapa yang selamat dari tragedi 1912. Project mencakup keseluruhan pipeline data science:

- **Exploratory Data Analysis (EDA)** — analisis pola dalam data
- **Data Preprocessing** — penanganan missing values dan encoding
- **Feature Engineering** — persiapan fitur untuk modeling
- **Model Training** — perbandingan 3 algoritma klasifikasi
- **Model Evaluation** — analisis performa menggunakan multiple metrics

##  Tech Stack

- **Python 3.8+**
- **Pandas** — manipulasi data
- **NumPy** — komputasi numerik
- **Matplotlib & Seaborn** — visualisasi data
- **Scikit-learn** — machine learning

##  Dataset

Dataset Titanic dari library Seaborn, berisi 891 record penumpang dengan atribut:
- Demografi (usia, jenis kelamin)
- Status sosial (kelas tiket, harga tiket)
- Hubungan keluarga (jumlah saudara/orangtua/anak yang ikut)
- Pelabuhan keberangkatan
- Status keselamatan (target)

##  Cara Menjalankan

### 1. Clone repository
```bash
git clone https://github.com/[username-kamu]/titanic-classification.git
cd titanic-classification
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Jalankan notebook
```bash
jupyter notebook titanic_classification.ipynb
```

##  Hasil

Tiga model dibandingkan untuk mencari yang terbaik:

| Model | Akurasi |
|-------|---------|
| Logistic Regression | ~80% |
| Decision Tree | ~78% |
| Random Forest | ~82% |

**Model terbaik: Random Forest dengan akurasi ~82%**

##  Insight Utama

1. **Jenis kelamin** adalah faktor terpenting — wanita memiliki tingkat keselamatan ~74%, pria hanya ~19%
2. **Kelas tiket** sangat berpengaruh — kelas 1: ~63%, kelas 3: ~24%
3. **Usia** juga berperan — anak-anak memiliki peluang selamat lebih tinggi

##  Struktur Project

```
titanic-classification/
├── titanic_classification.ipynb   # Notebook utama
├── requirements.txt                # Dependencies
└── README.md                       # Dokumentasi project
```

##  Author

**[Juli Harto]**
- 📧 Email: [Juliharto10@gmail.com]
- 🔗 LinkedIn: [linkedin.com/in/username-kamu]
- 💻 GitHub: [@username-kamu]

---

