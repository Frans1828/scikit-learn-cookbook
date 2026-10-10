# scikit-learn Cookbook - Original Code Reproduction

> **Code Reproduction & Theoretical Deep-Dive from scikit-learn Cookbook, Third Edition**
> Tugas 2 (Enrichment for Machine Learning Classes) - Individual Task

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Identitas Mahasiswa

| Informasi | Keterangan |
|---|---|
| **Nama** | **Fransisco Sitepu** |
| **NIM** | **101032300004** |
| **Kelas** | **TK 47 03** |
| **Mata Kuliah** | **Machine Learning** |
| **Institusi** | **Telkom University** |

---

## Tentang Repository Ini

Repository ini berisi **reproduksi kode original** dan **penjelasan teoritis mendalam** berdasarkan buku referensi:

> *scikit-learn Cookbook, Third Edition* — Over 80 recipes for machine learning in Python with scikit-learn

Seluruh notebook ditulis **dari awal secara original** — bukan salinan dari repositori lain. Setiap notebook mencakup:

- **Teori & Derivasi Formula**: Penjelasan konsep dengan notasi matematika (LaTeX)
- **Implementasi Kode**: Kode Python yang bersih, terstruktur, dan dapat dijalankan
- **Visualisasi**: Plot dan diagram untuk membantu pemahaman intuitif
- **Perbandingan Model**: Evaluasi dan benchmarking berbagai konfigurasi
- **Key Takeaways**: Ringkasan poin-poin penting di setiap chapter

---

## Milestone & Status Pengerjaan

| Milestone | Cakupan Chapter | Deadline | Status |
|---|---|---|---|
| **Milestone 1** | Chapter 1 - 5 | 10 Oktober 2026 (23:59) | **SELESAI** |
| **Milestone 2** | Chapter 6 - 8 | 17 Oktober 2026 (23:59) | **SELESAI** |
| **Bonus Enrichment** | Chapter 9 - 13 | - | **SELESAI** |

---

## Daftar Isi & Akses Notebook

| # | Chapter | Topik Utama | Buka di Colab |
|---|---|---|---|
| 01 | [API Elements of scikit-learn](./01.%20API%20Elements%20of%20scikit-learn/ch01_sklearn_api.ipynb) | Estimator, Transformer, Predictor, Pipeline, ColumnTransformer, GridSearchCV | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/01.%20API%20Elements%20of%20scikit-learn/ch01_sklearn_api.ipynb) |
| 02 | [Data Preprocessing](./02.%20Data%20Preprocessing/ch02_preprocessing.ipynb) | StandardScaler, MinMaxScaler, RobustScaler, OneHotEncoder, Imputation, PowerTransformer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/02.%20Data%20Preprocessing/ch02_preprocessing.ipynb) |
| 03 | [Dimensionality Reduction](./03.%20Dimensionality%20Reduction/ch03_dimensionality_reduction.ipynb) | PCA, Kernel PCA, LDA, t-SNE, SelectKBest, RFE | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/03.%20Dimensionality%20Reduction/ch03_dimensionality_reduction.ipynb) |
| 04 | [Distance Metrics & Nearest Neighbors](./04.%20Models%20with%20Distance%20Metrics%20and%20Nearest%20Neighbors/ch04_knn.ipynb) | Euclidean/Manhattan/Minkowski Distance, KNN Classifier, KNN Regressor, KDTree, BallTree | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/04.%20Models%20with%20Distance%20Metrics%20and%20Nearest%20Neighbors/ch04_knn.ipynb) |
| 05 | [Linear Models & Regularization](./05.%20Linear%20Models%20and%20Regularization/ch05_linear_models.ipynb) | OLS, Ridge (L2), Lasso (L1), ElasticNet, SGD, Bias-Variance Tradeoff | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/05.%20Linear%20Models%20and%20Regularization/ch05_linear_models.ipynb) |
| 06 | [Advanced Logistic Regression](./06.%20Advanced%20Logistic%20Regression/ch06_logistic_regression.ipynb) | Sigmoid, Log-Loss, Regularisasi C, OvR vs Multinomial, ROC-AUC, PR Curve | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/06.%20Advanced%20Logistic%20Regression/ch06_logistic_regression.ipynb) |
| 07 | [SVM & Kernel Methods](./07.%20Support%20Vector%20Machines%20and%20Kernel%20Methods/ch07_svm.ipynb) | Max-Margin Classifier, Soft-Margin SVM, RBF/Poly/Linear Kernel, SVR | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/07.%20Support%20Vector%20Machines%20and%20Kernel%20Methods/ch07_svm.ipynb) |
| 08 | [Tree-Based & Ensemble Methods](./08.%20Tree-Based%20Algorithms%20and%20Ensemble%20Methods/ch08_tree_ensemble.ipynb) | Decision Tree, Bagging, Random Forest, AdaBoost, Gradient Boosting, Extra Trees | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/08.%20Tree-Based%20Algorithms%20and%20Ensemble%20Methods/ch08_tree_ensemble.ipynb) |
| 09 | [Text Processing & Multiclass](./09.%20Text%20Processing%20and%20Multiclass%20Classification/ch09_text_multiclass.ipynb) | CountVectorizer, TF-IDF, N-grams, Naive Bayes, LinearSVC, Multiclass Strategies | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/09.%20Text%20Processing%20and%20Multiclass%20Classification/ch09_text_multiclass.ipynb) |
| 10 | [Clustering Techniques](./10.%20Clustering%20Techniques/ch10_clustering.ipynb) | K-Means, Elbow Method, Silhouette, DBSCAN, Agglomerative, Dendrogram | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/10.%20Clustering%20Techniques/ch10_clustering.ipynb) |
| 11 | [Novelty & Outlier Detection](./11.%20Novelty%20and%20Outlier%20Detection/ch11_outlier_detection.ipynb) | Isolation Forest, Local Outlier Factor, One-Class SVM, Elliptic Envelope | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/11.%20Novelty%20and%20Outlier%20Detection/ch11_outlier_detection.ipynb) |
| 12 | [Cross-Validation & Model Evaluation](./12.%20Cross-Validation%20and%20Model%20Evaluation/ch12_crossval_evaluation.ipynb) | K-Fold, StratifiedKFold, Learning Curve, Validation Curve, GridSearchCV, RandomizedSearchCV | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/12.%20Cross-Validation%20and%20Model%20Evaluation/ch12_crossval_evaluation.ipynb) |
| 13 | [Deploying Models in Production](./13.%20Deploying%20Models%20in%20Production/ch13_deployment.ipynb) | joblib Serialization, Pipeline Versioning, Model Metadata, Production Inference | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frans1828/scikit-learn-cookbook/blob/main/13.%20Deploying%20Models%20in%20Production/ch13_deployment.ipynb) |

---

## Penjelasan Setiap Chapter

### Chapter 1: Common Conventions and API Elements of scikit-learn

Chapter ini membahas fondasi dari seluruh ekosistem scikit-learn. scikit-learn dirancang dengan prinsip **konsistensi API** yang memungkinkan semua algoritma mengikuti pola yang sama: `fit()` untuk melatih, `predict()` untuk memprediksi, dan `transform()` untuk mengubah data.

**Konsep Utama:**
- **Estimator API**: Semua model mengikuti antarmuka `fit(X, y)`. Parameter yang dipelajari disimpan dengan suffix underscore (contoh: `coef_`, `intercept_`).
- **Transformer API**: Objek seperti `StandardScaler` mengimplementasikan `fit()` dan `transform()`. Penting: selalu `fit` hanya pada training data untuk menghindari *data leakage*.
- **Predictor API**: Menghasilkan prediksi melalui `predict(X)` (klasifikasi/regresi) atau `predict_proba(X)` (probabilitas kelas).
- **Pipeline**: Menggabungkan beberapa langkah preprocessing dan model menjadi satu objek yang konsisten dan bebas data leakage.
- **ColumnTransformer**: Menerapkan transformer berbeda pada subset kolom berbeda (numerik vs kategorik).
- **GridSearchCV**: Pencarian hyperparameter exhaustif menggunakan cross-validation.

**Formula Penting:**

Pipeline sebagai komposisi fungsi:
$$\hat{y} = f_n\Big(f_{n-1}\big(\ldots f_1(\mathbf{X})\big)\Big)$$

---

### Chapter 2: Data Preprocessing

Data mentah jarang bisa langsung digunakan oleh model ML. Chapter ini membahas teknik-teknik fundamental untuk mempersiapkan data.

**Scaling (Penskalaan Fitur):**

| Scaler | Formula | Kapan Digunakan |
|---|---|---|
| StandardScaler | $z = \frac{x - \mu}{\sigma}$ | SVM, PCA, Logistic Regression |
| MinMaxScaler | $x' = \frac{x - x_{\min}}{x_{\max} - x_{\min}}$ | Neural Networks, data non-Gaussian |
| RobustScaler | $x' = \frac{x - Q_{50}}{Q_{75} - Q_{25}}$ | Data dengan banyak outlier |

**Encoding Kategorik:**
- **OneHotEncoder**: Variabel nominal (tanpa urutan) → vektor biner
- **OrdinalEncoder**: Variabel ordinal (ada urutan) → integer berurutan
- **LabelEncoder**: Hanya untuk target variable (y)

**Imputasi Missing Values:**
- `SimpleImputer(strategy='mean/median/most_frequent')` untuk kasus sederhana
- `KNNImputer` untuk mengisi missing values berdasarkan tetangga terdekat

**Transformasi Distribusi (PowerTransformer):**

Box-Cox: $y = \frac{x^\lambda - 1}{\lambda}$ (untuk $x > 0$)

Yeo-Johnson: bekerja untuk nilai positif dan negatif.

---

### Chapter 3: Dimensionality Reduction

Ketika jumlah fitur sangat besar, timbul masalah *curse of dimensionality*. Chapter ini membahas teknik untuk mengurangi dimensi sambil mempertahankan informasi penting.

**Principal Component Analysis (PCA):**

PCA menemukan arah dengan variansi maksimal melalui eigendecomposition matriks kovarian:

$$\boldsymbol{\Sigma} = \frac{1}{n}\mathbf{X}^\top\mathbf{X} = \mathbf{V}\boldsymbol{\Lambda}\mathbf{V}^\top$$

Explained Variance Ratio: $\text{EVR}_k = \frac{\lambda_k}{\sum_i \lambda_i}$

**Kernel PCA:** Menangkap struktur non-linear menggunakan kernel trick:
- RBF: $K(x, x') = \exp(-\gamma\|x - x'\|^2)$
- Polynomial: $K(x, x') = (\gamma x^\top x' + r)^d$

**Linear Discriminant Analysis (LDA):** Supervised dimensionality reduction yang memaksimalkan separabilitas antar kelas:

$$J(\mathbf{w}) = \frac{\mathbf{w}^\top \mathbf{S}_B \mathbf{w}}{\mathbf{w}^\top \mathbf{S}_W \mathbf{w}}$$

**t-SNE:** Teknik visualisasi non-linear yang sangat efektif untuk mengeksplorasi struktur data berdimensi tinggi. Minimasi Kullback-Leibler divergence antara distribusi kesamaan di ruang asli dan ruang rendah dimensi.

**Feature Selection:** `SelectKBest`, `RFE`, `SelectFromModel` untuk memilih subset fitur terbaik.

---

### Chapter 4: Distance Metrics and Nearest Neighbors

K-Nearest Neighbors (KNN) adalah algoritma *instance-based learning* yang melakukan prediksi berdasarkan kemiripan dengan data training.

**Metrik Jarak:**

| Metrik | Formula |
|---|---|
| Euclidean | $d = \sqrt{\sum_{j=1}^p (x_j - x'_j)^2}$ |
| Manhattan | $d = \sum_{j=1}^p \|x_j - x'_j\|$ |
| Minkowski | $d = \left(\sum_{j=1}^p \|x_j - x'_j\|^p\right)^{1/p}$ |
| Cosine | $\cos\theta = \frac{\mathbf{x} \cdot \mathbf{x'}}{\|\mathbf{x}\| \|\mathbf{x'}\|}$ |

**KNN Classifier:**
$$\hat{y} = \text{mode}\Big(\{y_i : \mathbf{x}_i \in N_k(\mathbf{x})\}\Big)$$

**Bias-Variance Tradeoff:**
- K kecil → high variance (overfitting, decision boundary sangat kompleks)
- K besar → high bias (underfitting, decision boundary sangat halus)

**Struktur Pencarian Efisien:**
- **KDTree**: $O(\log n)$ untuk pencarian tetangga, efektif untuk dimensi rendah ($p < 20$)
- **BallTree**: Lebih efisien untuk dimensi tinggi dan metrik non-Euclidean

---

### Chapter 5: Linear Models and Regularization

Chapter ini membahas model-model linear untuk regresi, beserta teknik regularisasi untuk mencegah overfitting.

**Ordinary Least Squares (OLS):**

Minimasi Residual Sum of Squares:
$$\min_{\mathbf{w}} \|\mathbf{y} - \mathbf{X}\mathbf{w}\|^2_2$$

Solusi analitik: $\hat{\mathbf{w}} = (\mathbf{X}^\top\mathbf{X})^{-1}\mathbf{X}^\top\mathbf{y}$

**Ridge Regression (L2):** Menambahkan penalti pada norma koefisien untuk mencegah multikolinieritas:
$$\min_{\mathbf{w}} \|\mathbf{y} - \mathbf{X}\mathbf{w}\|^2_2 + \alpha\|\mathbf{w}\|^2_2$$

**Lasso Regression (L1):** Menghasilkan koefisien *sparse* (feature selection otomatis):
$$\min_{\mathbf{w}} \|\mathbf{y} - \mathbf{X}\mathbf{w}\|^2_2 + \alpha\|\mathbf{w}\|_1$$

**ElasticNet:** Kombinasi L1 dan L2:
$$\min_{\mathbf{w}} \|\mathbf{y} - \mathbf{X}\mathbf{w}\|^2_2 + \alpha\rho\|\mathbf{w}\|_1 + \frac{\alpha(1-\rho)}{2}\|\mathbf{w}\|^2_2$$

**Bias-Variance Decomposition:**
$$\text{MSE} = \text{Bias}^2 + \text{Variance} + \text{Irreducible Noise}$$

Semakin besar $\alpha$ → bias meningkat, variance menurun. Pemilihan $\alpha$ optimal dilakukan via `RidgeCV` / `LassoCV`.

---

### Chapter 6: Advanced Logistic Regression

Logistic Regression adalah algoritma klasifikasi yang memodelkan probabilitas kelas menggunakan fungsi sigmoid.

**Fungsi Sigmoid:**
$$P(y=1|\mathbf{x}) = \frac{1}{1 + e^{-(\mathbf{w}^\top\mathbf{x} + b)}}$$

**Log-Odds (Logit):**
$$\log\frac{P(y=1|\mathbf{x})}{P(y=0|\mathbf{x})} = \mathbf{w}^\top\mathbf{x} + b$$

**Binary Cross-Entropy Loss:**
$$\mathcal{L} = -\frac{1}{n}\sum_{i=1}^n \left[y_i\log(\hat{p}_i) + (1-y_i)\log(1-\hat{p}_i)\right]$$

**Regularisasi:** Parameter $C$ adalah *inverse regularization strength*:
- C kecil → regularisasi kuat (koefisien kecil, bias tinggi)
- C besar → regularisasi lemah (bisa overfit)

**Multiclass Strategies:**
- **OvR (One-vs-Rest)**: Melatih K classifier biner independen
- **Multinomial (Softmax)**: Satu model tunggal untuk semua kelas menggunakan fungsi softmax

**Evaluasi:** ROC-AUC mengukur kemampuan discriminatif model; Precision-Recall Curve lebih informatif untuk data tidak seimbang.

---

### Chapter 7: Support Vector Machines and Kernel Methods

SVM mencari *hyperplane* yang memisahkan kelas dengan **margin terbesar**.

**Hard-Margin SVM (linearly separable):**
$$\min_{\mathbf{w}, b} \frac{1}{2}\|\mathbf{w}\|^2 \quad \text{s.t.} \quad y_i(\mathbf{w}^\top\mathbf{x}_i + b) \geq 1, \forall i$$

**Soft-Margin SVM (C-SVM):** Mengizinkan beberapa pelanggaran margin dengan slack variables:
$$\min_{\mathbf{w}, b, \boldsymbol{\xi}} \frac{1}{2}\|\mathbf{w}\|^2 + C\sum_i \xi_i$$

**Kernel Trick:** Pemisahan non-linear tanpa menghitung pemetaan eksplisit:

| Kernel | Formula |
|---|---|
| Linear | $K(x, x') = x^\top x'$ |
| RBF | $K(x, x') = \exp(-\gamma\|x-x'\|^2)$ |
| Polynomial | $K(x, x') = (\gamma x^\top x' + r)^d$ |

**SVR (Support Vector Regression):** Menggunakan epsilon-tube — prediksi dalam tube tidak memberikan kontribusi loss.

**Panduan Hyperparameter:**
- **C**: Tradeoff margin vs pelanggaran
- **gamma**: Bandwidth kernel RBF — gamma besar = boundary kompleks, rawan overfit
- Selalu normalisasi data sebelum SVM!

---

### Chapter 8: Tree-Based Algorithms and Ensemble Methods

Decision tree dan ensemble methods adalah salah satu keluarga algoritma paling kuat dan populer dalam machine learning.

**Decision Tree — Kriteria Pemisahan:**

Gini Impurity: $I_G(t) = 1 - \sum_{k=1}^K p_k^2$

Entropy: $H(t) = -\sum_{k=1}^K p_k\log_2 p_k$

**Bagging (Bootstrap Aggregating):**

Melatih $T$ model pada bootstrap samples:
$$\hat{y} = \frac{1}{T}\sum_{t=1}^T f_t(\mathbf{x})$$

Variance model ensemble: $\text{Var} = \rho\sigma^2 + \frac{1-\rho}{T}\sigma^2$

Semakin kecil korelasi $\rho$ antar trees, semakin kecil variance.

**Random Forest = Bagging + Random Feature Subspace**

Setiap split hanya mempertimbangkan $\sqrt{p}$ fitur acak (klasifikasi) atau $p/3$ fitur (regresi).

**Gradient Boosting:** Model dibangun secara sekuensial, setiap model baru memprediksi residual dari model sebelumnya:
$$F_m(\mathbf{x}) = F_{m-1}(\mathbf{x}) + \eta \cdot h_m(\mathbf{x})$$

di mana $h_m$ dilatih untuk memprediksi *negative gradient* dari loss function.

---

### Chapter 9: Text Processing and Multiclass Classification

Machine learning membutuhkan representasi numerik dari teks. Chapter ini membahas cara mengubah teks mentah menjadi fitur yang dapat digunakan model.

**Bag of Words (CountVectorizer):**

Merepresentasikan dokumen sebagai frekuensi kata. Output: matriks sparse berukuran (n_docs × |vocab|).

**TF-IDF (Term Frequency - Inverse Document Frequency):**

$$\text{tfidf}(t, d, D) = \text{tf}(t,d) \times \left(\log\frac{1+|D|}{1+|\\{d:t\in d\\}|} + 1\right)$$

Memberikan bobot tinggi pada kata yang diskriminatif (sering di satu dokumen, jarang di corpus).

**N-grams:** Menangkap frasa dan konteks lokal:
- Unigram: "machine", "learning"
- Bigram: "machine learning", "deep learning"

**Model untuk Klasifikasi Teks:**
- **Naive Bayes**: Cepat, efektif untuk teks, mengasumsikan independensi fitur
- **LinearSVC**: Sering state-of-the-art; efisien untuk fitur sparse berdimensi tinggi
- **Logistic Regression**: Memberikan probabilitas; mudah diinterpretasikan

**Strategi Multiclass:**
- **OvR**: K classifier biner, satu per kelas
- **Multinomial**: Satu model dengan softmax output

---

### Chapter 10: Clustering Techniques

Clustering adalah unsupervised learning yang mengelompokkan data berdasarkan kemiripan tanpa label.

**K-Means Clustering:**

Minimasi Within-Cluster Sum of Squares (WCSS):
$$\min_{\mathbf{c}_1,...,\mathbf{c}_K} \sum_{k=1}^K \sum_{\mathbf{x}_i \in C_k} \|\mathbf{x}_i - \mathbf{c}_k\|^2$$

**Pemilihan K Optimal:**
- **Elbow Method**: Cari "siku" pada plot inertia vs K
- **Silhouette Score**: $s(i) = \frac{b(i) - a(i)}{\max(a(i), b(i))}$, di mana $a$ = intra-cluster distance, $b$ = nearest-cluster distance

**DBSCAN (Density-Based):**
- Tidak perlu menentukan K
- Mendeteksi outlier secara otomatis (label = -1)
- Menemukan cluster berbentuk arbitrer (non-spherical)
- Parameter: `eps` (radius) dan `min_samples`

**Hierarchical Clustering (Agglomerative):**
- Bottom-up: mulai dari setiap titik sebagai cluster, merge secara iteratif
- Divisive: mulai dari satu cluster, split secara rekursif
- Visualisasi melalui **dendrogram**

---

### Chapter 11: Novelty and Outlier Detection

Anomaly detection mengidentifikasi data yang menyimpang signifikan dari pola mayoritas.

**Isolation Forest:**

Outlier lebih mudah diisolasi (path length pendek dalam isolation tree):
$$s(x, n) = 2^{-\frac{E[h(x)]}{c(n)}}$$

Score mendekati 1 → anomali; mendekati 0.5 → normal.

**Local Outlier Factor (LOF):**

Membandingkan densitas lokal titik dengan densitas tetangganya:
$$LOF_k(p) = \frac{\sum_{o \in N_k(p)} \frac{lrd_k(o)}{lrd_k(p)}}{|N_k(p)|}$$

LOF >> 1 berarti titik tersebut outlier dalam konteks lokalnya.

**One-Class SVM:**

Melatih pada data normal saja, kemudian mendeteksi titik yang jauh dari distribusi normal.

**Elliptic Envelope:**

Fit ellipse Gaussian di sekitar data normal; titik di luar ellipse dianggap outlier.

**Hyperparameter `contamination`**: Proporsi outlier yang diharapkan dalam data (estimasi dari domain knowledge).

---

### Chapter 12: Cross-Validation and Model Evaluation

Evaluasi model yang tepat adalah kunci untuk mendapatkan estimasi performa yang tidak bias.

**K-Fold Cross-Validation:**

$$\text{CV Score} = \frac{1}{K}\sum_{k=1}^K \text{Score}(M_k, D^{(k)}_{\text{test}})$$

- K=5 atau K=10: kompromi terbaik antara bias dan variance estimasi
- **StratifiedKFold**: Wajib untuk klasifikasi — menjaga proporsi kelas di setiap fold

**Learning Curves:**
- Diagnosis underfitting (train & val rendah, berdekatan) vs overfitting (train tinggi, val jauh lebih rendah)
- Panduan: apakah menambah data atau mengubah model lebih tepat

**Validation Curves:**
- Efek satu hyperparameter terhadap performa training dan validasi
- Menemukan sweet spot regularisasi

**GridSearchCV vs RandomizedSearchCV:**

| | GridSearchCV | RandomizedSearchCV |
|---|---|---|
| Pendekatan | Exhaustive | Random sampling |
| Jumlah evaluasi | $N_1 \times N_2 \times ... \times K$ | $n\_iter \times K$ |
| Kapan digunakan | Parameter space kecil | Parameter space besar |

---

### Chapter 13: Deploying Models in Production

Setelah model ML berhasil dilatih, langkah selanjutnya adalah membuatnya tersedia untuk digunakan secara nyata.

**Model Serialization dengan joblib:**

```python
import joblib

# Simpan pipeline
joblib.dump(pipeline, 'model_v1.joblib', compress=3)

# Muat kembali
model = joblib.load('model_v1.joblib')
predictions = model.predict(new_data)
```

**Mengapa menyimpan Pipeline (bukan hanya model)?**

Pipeline memastikan preprocessing yang **identik** antara training dan production:
- Tanpa pipeline: scaler harus diaplikasikan secara manual → rawan kesalahan
- Dengan pipeline: `pipeline.predict(raw_data)` langsung menghasilkan prediksi yang benar

**Model Metadata:** Selalu simpan informasi tentang model:
- Versi scikit-learn dan Python
- Tanggal dan waktu training
- Performa pada validation set
- Nama fitur dan preprocessing parameters

**Production Workflow:**

```
Data Baru (raw) → Pipeline.predict() → Prediksi
                       ↑
              [Scaler + Model]
              (tersimpan sebagai satu unit)
```

**Best Practices Production ML:**
1. Serialisasi seluruh pipeline (bukan hanya model)
2. Unit test prediksi setelah loading model
3. Versioning model dengan semantic versioning
4. Monitor data drift dan model performance decay
5. A/B testing sebelum full deployment

---

## Cara Menjalankan Notebook

### Opsi 1: Google Colab (Paling Mudah, Direkomendasikan)

Klik badge **Open in Colab** pada tabel di atas. Tidak perlu instalasi apapun.

### Opsi 2: Lokal (Jupyter Notebook)

```bash
# 1. Clone repository
git clone https://github.com/Frans1828/scikit-learn-cookbook.git
cd scikit-learn-cookbook

# 2. Buat virtual environment
python -m venv venv

# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate

# 3. Install semua dependensi
pip install --upgrade pip
pip install -r requirements.txt

# 4. Jalankan Jupyter
jupyter notebook
```

---

## Dependencies

```
scikit-learn>=1.3.0
numpy>=1.24.0
pandas>=2.0.0
matplotlib>=3.7.0
seaborn>=0.12.0
scipy>=1.10.0
joblib>=1.3.0
jupyter
nltk
```

---

## Referensi

1. **Buku Referensi Utama:**
   *scikit-learn Cookbook, Third Edition* — John Sukup (O'Reilly / Packt)
   - [Akses Buku via Google Drive](https://drive.google.com/file/d/1b7mWwNMYWxOVwnWbPZd8_njVXAgGEMQR/view?usp=sharing)

2. **Dokumentasi Resmi scikit-learn:**
   [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)

3. **Repositori Referensi Pengumpulan Dosen:**
   [farrelrassya/scikit-learn-cookbook](https://github.com/farrelrassya/scikit-learn-cookbook)

---

**Fransisco Sitepu | NIM: 101032300004 | Kelas: TK 47 03 | Machine Learning | Telkom University**
