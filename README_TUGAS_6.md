🧠 Klasifikasi Berita Indonesia: Politik vs Olahraga dengan RNN (LSTM)

Proyek ini merupakan implementasi model Recurrent Neural Network (RNN) berbasis LSTM untuk mengklasifikasikan berita berbahasa Indonesia ke dalam dua kategori: Politik dan Olahraga. Model ini dibangun menggunakan Keras dan TensorFlow, serta dilatih dengan dataset berita dari Kaggle.

📌 Ringkasan Proyek

Tujuan: Mengklasifikasikan berita berdasarkan isi kontennya (teks) ke dalam dua topik utama.

Kategori:

0 → Politik

1 → Olahraga

Metode: Recurrent Neural Network dengan LSTM

Dataset: Indonesian News Dataset (Kaggle)

🗂️ Struktur Folder

├── data/
│   └── data.csv                  # Dataset utama
├── model/
│   └── model_lstm.h5             # Model terlatih
├── notebook/
│   └── klasifikasi_berita_lstm.ipynb   # Notebook utama
├── README.md

⚙️ Langkah Menjalankan Proyek

1. Clone Repository

git clone https://github.com/username/klasifikasi-berita-rnn.git
cd klasifikasi-berita-rnn

2. Install Dependensi

Gunakan virtual environment (opsional) dan install semua kebutuhan:

pip install -r requirements.txt

Requirements utama:

tensorflow

scikit-learn

pandas

numpy

matplotlib

3. Jalankan Notebook

Buka file notebook/klasifikasi_berita_lstm.ipynb di Jupyter Notebook:

jupyter notebook

Atau jalankan via Google Colab.

4. Pelatihan Ulang (Opsional)

Jika ingin melatih ulang model:

Pastikan data.csv sudah tersedia di folder data/

Jalankan seluruh sel di notebook

5. Evaluasi Model

Model akan mencetak:

Akurasi pelatihan dan validasi tiap epoch

Classification Report

Confusion Matrix

📈 Hasil Akhir

Akurasi total: 94%

F1-score Politik: 0.97

F1-score Olahraga: 0.79

Confusion Matrix:

[[2794   85]
 [ 104  356]]

✍️ Refleksi Pribadi

Proyek ini memperdalam pemahaman saya dalam:

Natural Language Processing (NLP)

Implementasi LSTM untuk klasifikasi teks berbahasa Indonesia

Penanganan data tidak seimbang menggunakan class_weight

📄 Lisensi

Proyek ini bebas digunakan untuk keperluan akademik dan pengembangan non-komersial. Sertakan atribusi jika digunakan.

