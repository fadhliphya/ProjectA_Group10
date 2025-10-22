# 🧠 Project A Group 10  
**Analisis Sentimen dan TF-IDF pada Artikel Berita tentang Emirates Airlines dengan Pendekatan Natural Language Processing (NLP)**  

📄 **Laporan Lengkap:** [Klik di sini untuk melihat laporan Project A (PDF)](https://drive.google.com/file/d/1MskFKRU_5g-suCJ9Xxh_ApupP3lF1MOR/view?usp=sharing)

---

## 👥 Anggota Kelompok
| Nama | NRP |
|------|-----|
| **Dinanti Vita Rachman** | 5026221190 |
| **Maureen Ghassani Fadhliphya** | 5026221193 |

---

## 📚 Deskripsi Proyek
Proyek ini merupakan implementasi **Natural Language Processing (NLP)** untuk menganalisis pemberitaan internasional mengenai **Emirates Airlines**.  
Pendekatan utama yang digunakan meliputi:

- **TF-IDF** → menemukan kata kunci dominan  
- **Part-of-Speech (POS) Tagging** → menganalisis struktur linguistik  
- **Named Entity Recognition (NER)** → mengidentifikasi entitas penting  
- **Sentiment Analysis (FinBERT)** → mengukur kecenderungan opini media  

Analisis dilakukan untuk memahami bagaimana media membingkai citra dan reputasi *Emirates Airlines* secara objektif.

---

## 🎯 Tujuan
- Mengidentifikasi topik dan kata kunci dominan dalam pemberitaan *Emirates Airlines*  
- Mengetahui kecenderungan sentimen (positif, netral, negatif) dalam berita internasional  
- Memahami bagaimana media membentuk persepsi publik terhadap citra perusahaan  

---

## ⚙️ Metodologi

### 1. Data Collection
- Mengumpulkan **151 artikel berita** dari media internasional: *BBC, Reuters, CNN, Gulf News,* dan *Khaleej Times*  
- Pengumpulan dilakukan secara **manual search** dan **web scraping** menggunakan `BeautifulSoup` dan `Trafilatura`  

### 2. Preprocessing
- Cleaning teks dari HTML, angka, dan tanda baca  
- Tokenization, stopword removal, dan lemmatization dengan `NLTK`  
- Menghasilkan dataset teks bersih siap analisis  

### 3. Feature Extraction (TF-IDF)
- Menggunakan `TfidfVectorizer` dari `scikit-learn`  
- Kata dominan: *emirates*, *flight*, *dubai*, *airline*, *service*  

### 4. Linguistic Analysis (POS & NER)
- **POS Tagging** dan **Named Entity Recognition** dilakukan dengan `spaCy`  
- Entitas utama: *Emirates*, *Dubai*, *UAE*, *Boeing*, *Tim Clark*  

### 5. Sentiment Analysis (FinBERT)
- Model: `ProsusAI/finbert` dari *Hugging Face Transformers*  
- Hasil klasifikasi:
  - 🟩 **Positif:** 4.00%  
  - ⚪ **Netral:** 93.33%  
  - 🟥 **Negatif:** 2.67%

---

## 📊 Hasil Utama
- Mayoritas berita bersentimen **netral**, menunjukkan pemberitaan yang objektif dan informatif.  
- **Sentimen positif meningkat pada 2024**, seiring ekspansi layanan dan pertumbuhan finansial.  
- **Sentimen negatif** muncul secara situasional (misalnya keterlambatan atau gangguan operasional).  
- Citra *Emirates Airlines* di media global tergolong **stabil dan positif secara konsisten.**

---

## 🧩 Tools & Library
| Kategori | Library |
|-----------|----------|
| **Scraping** | `requests`, `BeautifulSoup`, `trafilatura`, `newspaper3k` |
| **Text Processing** | `pandas`, `nltk`, `re`, `string` |
| **NLP Models** | `spaCy`, `transformers`, `scikit-learn`, `torch` |
| **Visualization** | `matplotlib`, `seaborn`, `wordcloud` |

---

## 🧠 Insight
Pendekatan NLP seperti ini dapat digunakan untuk:
- **Analisis reputasi digital** suatu perusahaan  
- **Pemantauan media (media monitoring)**  
- **Analisis framing dan persepsi publik** terhadap isu atau brand tertentu  

---

## 🔗 Referensi Laporan
Laporan lengkap Project A tersedia di Google Drive:  
👉 [https://drive.google.com/file/d/1MskFKRU_5g-suCJ9Xxh_ApupP3lF1MOR/view?usp=sharing](https://drive.google.com/file/d/1MskFKRU_5g-suCJ9Xxh_ApupP3lF1MOR/view?usp=sharing)

---

✳️ *Departemen Sistem Informasi — Fakultas Teknologi Elektro dan Informatika Cerdas (FTEIC) — Institut Teknologi Sepuluh Nopember, 2025*
