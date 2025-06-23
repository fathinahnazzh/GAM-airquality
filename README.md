# GAM Air Quality Dataset🍃

## 📦 Dataset

- Dataset: Air Quality
- Sumber: Pre-built dataset
- Jumlah observasi: 153
- Jumlah variabel: 6
- Variabel target: `Ozone` (rata-rata ozon per bagian di Pulau Roosevelt)

## 🔧 Tools dan Teknologi

- Bahasa Pemrograman: **R**
- Library yang digunakan:
  - `mgcv` (model GAM)
  - `Metrics` (evaluasi model)
  - `corrplot` (korelasi heat map)
  - `caret` (machine learning)

---

## 📊 Langkah Analisis

1. Load dan eksplorasi data
2. Analisis korelasi antar variabel
3. Membagi data latih dan uji 80:20
4. Membuat model GAM
5. Evaluasi model R²
6. Mengecek residual plot

---

## 🔍 Hasil Singkat

- Model GAM dengan pendekatan spline mampu menangkap data variabel `temp` dan `Wind` yang memiliki korelasi cukup signifikan terhadap `Ozone` serta plot yang terlihat tidak linier.
- Model GAM mampu menjelaskan 71.15% dari data uji.
