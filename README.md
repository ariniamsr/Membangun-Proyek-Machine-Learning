# 🤖 Membangun Proyek Machine Learning

Repository ini berisi submission akhir kelas **Belajar Machine Learning Terapan** yang mencakup proses **Clustering** dan **Klasifikasi**, mulai dari preprocessing data, pelatihan model, hingga penyimpanan model terbaik.

---

## 📌 Deskripsi Proyek

Proyek ini terdiri dari dua tahapan utama:

### 🔹 Clustering
Melakukan segmentasi data menggunakan algoritma clustering untuk menemukan pola dan karakteristik kelompok data.

### 🔹 Classification
Membangun model klasifikasi untuk memprediksi kategori berdasarkan fitur yang tersedia.

---

## 🏗️ Struktur Repository

```text
## 🏗️ Struktur Repository

```text
Membangun-Proyek-Machine-Learning
│
├── Dataset
│   ├── data_clustering.csv
│   └── data_clustering_inverse.csv
│
├── Notebook
│   ├── [Clustering]_Submission_Akhir_BMLP_Arini_Arumsari.ipynb
│   └── [Klasifikasi]_Submission_Akhir_BMLP_Arini_Arumsari.ipynb
│
├── Model Clustering
│   ├── model_clustering.h5
│   └── PCA_model_clustering.h5
│
├── Model Classification
│   ├── decision_tree_model.h5
│   ├── explore_RandomForest_classification.h5
│   └── tuning_classification.h5
│
└── README.md
```

### 📊 Diagram Alur Proyek

```text
                    Dataset
                        │
                        ▼
              Data Preprocessing
                        │
         ┌──────────────┴──────────────┐
         ▼                             ▼
    Clustering                   Classification
         │                             │
         ▼                             ▼
  Model Clustering            Model Klasifikasi
         │                             │
         ▼                             ▼
   Evaluasi Model             Evaluasi Model
         │                             │
         └──────────────┬──────────────┘
                        ▼
                Penyimpanan Model
                     (.h5)
```

---

## ⚙️ Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

## 🚀 Cara Menjalankan Project

### Clone Repository

```bash
git clone https://github.com/ariniamsr/Membangun-Proyek-Machine-Learning.git
```

### Install Dependency

```bash
pip install -r requirements.txt
```

### Jalankan Notebook

```bash
jupyter notebook
```

Buka file notebook:

- `[Clustering]_Submission_Akhir_BMLP_Arini_Arumsari.ipynb`
- `[Klasifikasi]_Submission_Akhir_BMLP_Arini_Arumsari.ipynb`

---

## 📈 Hasil

### Clustering
- Melakukan segmentasi data berdasarkan karakteristik yang serupa.
- Menggunakan PCA untuk reduksi dimensi.
- Menyimpan model dalam format `.h5`.

### Classification
- Membangun model klasifikasi menggunakan beberapa algoritma.
- Melakukan eksplorasi Random Forest.
- Melakukan tuning model untuk mendapatkan performa terbaik.

---

## 👩‍💻 Author

**Arini Arumsari**

GitHub: https://github.com/ariniamsr
