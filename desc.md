# Silabus Machine Learning - 8 Pertemuan

## Pertemuan 1: Pengantar Machine Learning & Basic Math
Materi pertemuan pertama dibagi menjadi dua bagian utama untuk memberikan gambaran besar:

### Pengantar Machine Learning
- Penjelasan teori dasar pembelajaran mesin: Supervised, Unsupervised, dan Reinforcement Learning (RL)
- Perbedaan fundamental antara konsep Regresi dan Klasifikasi
- Pemahaman mendasar mengenai pentingnya pembagian data menjadi Training dan Testing

### Basic Math (Matematika Dasar)
- **Aljabar Linear**: Konsep Eigenvalue dan Eigenvector
- **Kalkulus**: Dasar-dasar turunan dan turunan parsial
- **Statistika Dasar**: Konsep dasar regresi dan penurunan rumus Maximum Likelihood Estimation (MLE) untuk Linear Regression secara matematis:  
  $$\hat{\beta} = (X^T X)^{-1} X^T Y$$

---

## Pertemuan 2: Data Cleaning & Exploratory Data Analysis (EDA)
Pertemuan ini difokuskan pada praktik langsung (hands-on) terkait persiapan data:

### Data Cleaning
Praktik teknik-teknik berikut:
- Imputasi nilai yang hilang (missing values) menggunakan mean, median, atau modus
- Penghapusan data duplikat
- Standarisasi format data

### Exploratory Data Analysis (EDA)
Pengenalan berbagai fungsi plot (visualisasi) beserta contoh penerapannya untuk menggali informasi dan menganalisis karakteristik data.

---

## Pertemuan 3: Feature Engineering & Preprocessing
Fokus pada rekayasa dan prapemrosesan fitur agar data siap digunakan oleh model:

### Feature Engineering
Contoh penerapan teknik pembuatan fitur baru berdasarkan domain knowledge.

### Feature Encoding
Penjelasan alasan mengapa data kategorikal harus melalui proses encoding, disertai penjelasan tambahan mengenai jenis-jenis encoding yang umum digunakan.

### Feature Scaling
Pemahaman awal bahwa rentang nilai fitur perlu diseragamkan (scaling), dengan penjelasan mendalam mengenai alasannya yang akan dibahas pada pertemuan selanjutnya.

---

## Pertemuan 4: Klasifikasi, Imbalance Class, dan Pengenalan Berbagai Model

### Pengenalan Klasifikasi & Logistic Regression
Penjelasan konsep dasar klasifikasi secara sederhana (sebagai Linear Regression yang ditambahkan fungsi sigmoid). Materi ini juga mencakup perbedaan antara klasifikasi biner dan multiclass.

### Imbalance Class
Identifikasi masalah ketidakseimbangan kelas (imbalance class) dalam dataset dan contoh penanganan untuk mengatasi hal tersebut.

### Pengenalan Jenis Model
Memperkenalkan berbagai algoritma: Support Vector Machine (SVM), KNN, Decision Tree, dan Random Forest. Fokus pada sesi ini sebatas implementasi coding saja, baik untuk kasus regresi maupun klasifikasi.

---

## Pertemuan 5: Algoritma Dasar, Evaluation Metric, & Hyperparameter Tuning

### Konsep Algoritma
Penjelasan logika dan cara kerja algoritma dasar yang relatif mudah dipahami: KNN dan Decision Tree.

### Evaluation Metric
Contoh dan penjelasan mengenai berbagai metrik evaluasi untuk mengukur performa model.

### Hyperparameter Tuning
Penjelasan cara kerja pencarian parameter optimal menggunakan metode sederhana seperti Grid Search atau Random Search, serta contoh implementasi coding menggunakan Optuna (sebagai materi opsional).

---

## Pertemuan 6: Aplikasi Basic Math pada Machine Learning
Penjelasan aplikasi nyata dari materi matematika dasar yang telah dipelajari pada pertemuan pertama:

### Principal Component Analysis (PCA)
Penjelasan penerapannya menggunakan Eigenvalue dan Eigenvector.

### Gradient Descent
Penjelasan penerapannya menggunakan konsep turunan.

---

## Pertemuan 7: Dasar-dasar Neural Network
Membangun fondasi pemahaman sebelum masuk ke arsitektur jaringan saraf tiruan:

### Loss Function & Cost Function
Penguraian definisi serta perbedaan antara Loss Function dan Cost Function, baik untuk kasus regresi maupun klasifikasi.

### Implementasi Manual
Contoh praktik membangun model Linear Regression dari awal menggunakan algoritma Gradient Descent.

---

## Pertemuan 8: Membangun Neural Network
Puncak materi yang menggabungkan teori matematika dan pemrograman:

### Membangun Model NN
Penjelasan cara membangun model Neural Network secara komprehensif, baik dari sisi matematis (menggunakan Chain Rule pada kalkulus) maupun dari sisi implementasi coding.
