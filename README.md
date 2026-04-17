# 🔍 Sistem Pencarian Dokumen (Information Retrieval) Berbahasa Indonesia

Repositori ini berisi implementasi sistem NLP untuk Information Retrieval (Sistem Temu Kembali Informasi) menggunakan dataset berita berbahasa Indonesia. Proyek ini dibangun untuk membandingkan performa representasi teks leksikal dan semantik.

## 🎯 Tujuan Proyek
Membangun purwarupa mesin pencari dokumen sederhana yang mampu memproses *query* pengguna dan mengembalikan dokumen paling relevan dari korpus menggunakan penghitungan **Cosine Similarity**.

## 🛠️ Teknologi & Metode
* **Bahasa:** Python 3.8+
* **Text Preprocessing:** Case Folding, Punctuation Removal, Stopword Removal & Stemming (menggunakan `Sastrawi`).
* **Representasi Teks 1:** TF-IDF (Term Frequency - Inverse Document Frequency) via `scikit-learn`.
* **Representasi Teks 2:** Word Embeddings (Word2Vec) via `gensim`.
* **Visualisasi:** `WordCloud` untuk distribusi teks, dan PCA (`scikit-learn`) untuk memproyeksikan Word2Vec ke ruang 2 Dimensi.

## 🚀 Cara Menjalankan Proyek (Local Environment)

1. **Clone repositori**
   ```bash
   git clone [https://github.com/username-kamu/nlp-information-retrieval.git](https://github.com/username-kamu/nlp-information-retrieval.git)
   cd nlp-information-retrieval

2. **Google Drive Dataset**
   ```bash
   https://drive.google.com/file/d/1CssyTUb5FDN2XPGfTlYu5bXbX-6ZdFZg/view?usp=sharing

3. **Jupyter Notebook**
   ```bash
   https://drive.google.com/file/d/1CssyTUb5FDN2XPGfTlYu5bXbX-6ZdFZg/view?usp=sharing](https://colab.research.google.com/drive/1nFq_SGQj06JlzJhLmexB4kj8277-8Gco?usp=sharing

4. **Kaggle Dataset**
   ```bash
   [Indonesian Hoax News Dataset](https://www.kaggle.com/datasets/ireddragonicy/indonesian-hoax-news-dataset/data)
