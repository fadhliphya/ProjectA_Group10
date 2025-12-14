# 🧠 Project A dan Project B Group 10  
**Analisis Sentimen dan TF-IDF pada Artikel Berita tentang Emirates Airlines dengan Pendekatan Natural Language Processing (NLP) dan 
Analisis Sentimen Menggunakan BERT**

📄 Laporan Lengkap Project A: [Klik di sini untuk melihat laporan Project A (PDF)](https://drive.google.com/file/d/1QskrWnTEmLUOhQqfg0dpRkfZVppqkSQc/view?usp=sharing)

📄 Laporan Lengkap Project B: [Klik di sini untuk melihat laporan Project B (PDF)]
(https://drive.google.com/file/d/1fARPtibv45kb8MhyFc4ZY9IrJjOGUdb9/view?usp=sharing).

---

## 👥 Anggota Kelompok
| Nama | NRP |
|------|-----|
| **Dinanti Vita Rachman** | 5026221190 |
| **Maureen Ghassani Fadhliphya** | 5026221193 |

---

# 📘 PROJECT A  
## Analisis Sentimen dan TF-IDF pada Artikel Berita tentang Emirates Airlines  
### dengan Pendekatan Natural Language Processing (NLP)

---

## 📚 Deskripsi Project A
Project A berfokus pada analisis teks berita internasional mengenai **Emirates Airlines**
menggunakan pendekatan NLP klasik. Analisis dilakukan untuk mengidentifikasi kata kunci dominan,
struktur linguistik, serta kecenderungan sentimen media terhadap Emirates Airlines.

---

## 🎯 Tujuan Project A
- Mengidentifikasi kata dan topik dominan dalam pemberitaan Emirates Airlines  
- Menganalisis kecenderungan sentimen media secara umum  
- Memahami framing media terhadap citra dan reputasi perusahaan  

---

## ⚙️ Metodologi Project A

### 1. Data Akuisisi
- Total artikel: **N = 130**
- Bahasa artikel: **English (EN)**
- Sumber: Reuters, BBC, CNN, Gulf News, Khaleej Times, dan media internasional lainnya
- Periode pengambilan data ditentukan secara manual

### 2. Preprocessing Teks
- Pembersihan HTML dan karakter khusus
- Tokenisasi teks
- Stopword removal
- Lemmatization menggunakan `NLTK`

### 3. Feature Extraction (TF-IDF)
- Menggunakan `TfidfVectorizer`
- Identifikasi kata dominan seperti *emirates, flight, dubai, airline*

### 4. Analisis Linguistik
- POS Tagging
- Named Entity Recognition (NER)
- Tools: `spaCy`

### 5. Analisis Sentimen (Lexicon / Rule-based)
- Klasifikasi sentimen: Positif, Netral, Negatif
- Visualisasi distribusi sentimen

---

## 📊 Output Project A
- Wordcloud global
- Wordcloud per kategori berita
- Distribusi sentimen
- Analisis kata dominan

---

# 📕 PROJECT B  
## Analisis Sentimen Menggunakan BERT

---

## 📚 Deskripsi Project B
Project B merupakan pengembangan dari Project A dengan pendekatan **Deep Learning**,
yaitu melakukan **fine-tuning model BERT** untuk analisis sentimen pada dataset berita
Emirates Airlines yang telah dilabeli secara manual.

---

## 🎯 Tujuan Project B
- Membangun model analisis sentimen berbasis **BERT**
- Mengevaluasi performa BERT dalam mengklasifikasikan sentimen berita
- Menganalisis kesalahan prediksi (misclassification)

---

## ⚙️ Metodologi Project B

### 1. Dataset
- Dataset hasil Project A
- Total artikel: **N = 130**
- Bahasa: **English (EN)**
- Label sentimen:  
  - 0 → Negative  
  - 1 → Neutral  
  - 2 → Positive  

### 2. Pra-pemrosesan untuk BERT
- Penggabungan judul dan konten artikel
- Pembersihan karakter khusus
- Tanpa stemming dan stopword removal
- Tokenisasi menggunakan `bert-base-uncased`

### 3. Model
- Model: `bert-base-uncased`
- Framework: HuggingFace Transformers
- Loss Function: CrossEntropyLoss
- Optimizer: AdamW

### 4. Training & Evaluation
- Split data: 80% train – 20% validation
- Evaluasi menggunakan accuracy dan classification report
- Analisis error berdasarkan hasil misclassification

---

## 📊 Output Project B
- Akurasi dan classification report
- Confusion matrix
- Contoh prediksi salah (error analysis)
- Model BERT hasil fine-tuning

---

## 🧠 Tools & Library
- pandas, numpy
- nltk, spaCy
- scikit-learn
- transformers, torch
- matplotlib, seaborn, wordcloud

---

## 🔗 Referensi Laporan
Laporan lengkap Project A tersedia di Google Drive:  
👉 [Laporan Lengkap Project A]
(https://drive.google.com/file/d/1QskrWnTEmLUOhQqfg0dpRkfZVppqkSQc/view?usp=sharing).

Laporan Lengkap Project B tersedia di Google Drive: 
👉 [Laporan Lengkap Project B}
(https://drive.google.com/drive/folders/1eKRDLEahBuMXquNzXzI9AMKIgzMXnJoP?usp=drive_link).

---

✳️ *Departemen Sistem Informasi — Fakultas Teknologi Elektro dan Informatika Cerdas (FTEIC) — Institut Teknologi Sepuluh Nopember, 2025*
