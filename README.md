# 📊 Analisis Sentimen Ulasan Pengguna Itemku Menggunakan Support Vector Machine (SVM)

Proyek ini bertujuan untuk melakukan **analisis sentimen** terhadap ulasan pengguna aplikasi **Itemku** yang diambil dari Google Play Store.  
Metode yang digunakan adalah **Support Vector Machine (SVM)** dengan fitur **TF-IDF** dan preprocessing berbasis **Sastrawi** untuk teks Bahasa Indonesia.

---

## 🚀 Fitur Utama
- Scraping ulasan aplikasi Itemku menggunakan **google-play-scraper**
- Preprocessing teks:
  - Case folding
  - Cleaning (penghapusan tanda baca, angka, simbol)
  - Stopword removal
  - Stemming Bahasa Indonesia (Sastrawi)
- Labeling sentimen otomatis berdasarkan rating
- Ekstraksi fitur menggunakan **TF-IDF**
- Training model menggunakan **Linear SVM**
- Evaluasi model menggunakan Accuracy, Precision, Recall, F1-score
- Analisis hasil sentimen pengguna
