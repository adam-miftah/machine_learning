# Proyek Akhir Machine Learning: Clustering & Klasifikasi

Proyek ini adalah implementasi tugas akhir mata kuliah *Machine Learning* di Universitas Pamulang. Tujuan dari proyek ini adalah membangun model *Clustering* dan *Klasifikasi* menggunakan dataset yang telah diproses, serta menganalisis hasil evaluasi model.

---

## 📌 **Deskripsi Proyek**
1. **Clustering**:  
   - Menggunakan metode *KMeans* untuk mengelompokkan data menjadi 3 cluster.
   - Dataset terdiri dari kolom numerikal dan kategorikal yang telah diproses.
   - Evaluasi dilakukan menggunakan **Silhouette Score**.

2. **Klasifikasi**:  
   - Menggunakan algoritma **Random Forest** dan **Logistic Regression**.
   - Dataset yang digunakan adalah hasil dari clustering, di mana label cluster menjadi target klasifikasi.
   - Evaluasi dilakukan dengan metrik **Accuracy** dan **F1-Score**.
   - Model dievaluasi sebelum dan setelah tuning hyperparameter.

---

## 🛠 **Teknologi yang Digunakan**
|Python 3.x
|Scikit-learn
|Pandas
|Numpy
|Matplotlib & Seaborn
|Google Colab


📁 Proyek_Machine_Learning  
 │  
├── Customers.csv                          # Dataset mentah awal  
├── Clustering_Customers_result.csv        # Dataset hasil Clustering
│  
├── [Klasifikasi]_Submission_Akhir_Adam Miftahul Falah.ipynb  # Notebook Klasifikasi  
├── [Clustering]_Submission_Akhir_BMLP_Adam Miftahul Falah.ipynb # Notebook Clustering  
 │  
└── README.md                          # Dokumentasi proyek ini  

---

## 🚀 **Langkah Eksekusi**
### **1. Clustering**
- Buka notebook [Clustering](https://colab.research.google.com/drive/1WwIJze7s44e0iNPUmgUwxFP8VnXUle2C?usp=sharing).
- Jalankan kode untuk memuat dataset, melakukan *Clustering* dengan KMeans, dan mengevaluasi hasil.

### **2. Klasifikasi**
- Buka notebook [Klasifikasi](https://colab.research.google.com/drive/1zQIgPVPdZaAdQkmJLtwEc4cSVNzkCT-R?usp=sharing).
- Jalankan kode untuk memuat dataset hasil clustering, membangun model **Random Forest** dan **Logistic Regression**, mengevaluasi model, serta melakukan tuning.

---

## 📊 **Hasil Evaluasi Model**
### **Clustering**
- Metode: KMeans
- Jumlah Cluster: 3
- Evaluasi: **Silhouette Score > 0.75**

### **Klasifikasi**
---
| Model                | Accuracy | F1-Score |
|----------------------|----------|----------|
| Random Forest        | 99.75%   | 99.75%   |
| Logistic Regression  | 98.98%   | 98.98%   |
---

## 🎓 **Informasi Tambahan**
**Dibuat Oleh:**  
**Nama:** Adam Miftahul Falah  
**NIM:** 221011400961  
**Program Studi:** Teknik Informatika  
**Universitas:** Universitas Pamulang  
**Tahun:** 2024  

---

## 📥 **Download Model**
- Random Forest Model: [random_forest_best_model.pkl](path/to/random_forest_best_model.pkl)

---

## 🤝 **Kontribusi**
Jika Anda ingin memberikan masukan atau berkontribusi, silakan fork repository ini dan ajukan pull request.  

---

## 📧 **Kontak**
Jika ada pertanyaan lebih lanjut, silakan hubungi melalui:  
- **Email:** adammiftah196@gmail.com  

---
