# 🧠 Autoencoder on Fashion MNIST

Proyek ini merupakan eksplorasi model **Autoencoder** menggunakan dataset **Fashion MNIST** untuk memahami bagaimana arsitektur encoder-decoder mempengaruhi hasil rekonstruksi dan representasi laten.

## 📁 Struktur Proyek

- `autoencoder_fashionmnist.ipynb` — Notebook utama berisi seluruh proses pelatihan dan eksplorasi model.
- `Laporan_Singkat_Reflektif_Autoencoder.docx` — Laporan singkat dan reflektif proses eksperimen.
- `README.md` — Ringkasan proyek dan petunjuk eksekusi.

---

## 🚀 Arsitektur Model

Model terdiri dari:
- **Encoder**:
  - 2 lapis Conv2D + MaxPooling
  - Dense layer sebagai representasi laten (latent_dim = 64)
- **Decoder**:
  - Dense + Reshape
  - 2 lapis Conv2DTranspose
  - Output layer sigmoid

Total parameter: `479,105`

---

## 📊 Hasil Pelatihan

- **Loss akhir**: `0.2589`
- **Validation loss akhir**: `0.2613`
- Model mampu merekonstruksi gambar dengan cukup baik.
- Visualisasi latent space dengan PCA menunjukkan pemisahan kelas yang cukup jelas meskipun model dilatih secara unsupervised.

---

## 📈 Visualisasi

- **Rekonstruksi Gambar**: Menampilkan perbandingan gambar asli dan hasil rekonstruksi.
- **Representasi Laten**: Visualisasi PCA 2D dengan pewarnaan berdasarkan label kelas.

---

## 🧪 Cara Menjalankan

1. Pastikan environment Python 3.x dengan package berikut sudah tersedia:
    ```bash
    pip install tensorflow matplotlib numpy seaborn scikit-learn
    ```

2. Jalankan notebook:
    ```bash
    jupyter notebook autoencoder_fashionmnist.ipynb
    ```

---

## 🤖 Penggunaan AI

Dalam proyek ini, bantuan **ChatGPT** digunakan untuk:
- Brainstorming struktur model autoencoder
- Debugging error pada layer dan dimensi
- Penyusunan laporan dan penjelasan eksploratif

Namun semua proses eksplorasi dan pemahaman dilakukan secara mandiri dan aktif.

---

## 📚 Dataset

- [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)

---

## ✍️ Author

Andrian Maulana – Universitas Darussalam Gontor  
Tugas Individu - Eksplorasi Autoencoder, 2025
