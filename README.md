# 🧠 ProjectA_Group10  
**Analisis Sentimen dan TF-IDF pada Artikel Berita tentang Emirates Airlines dengan Pendekatan Natural Language Processing (NLP)**  

---

## 📚 Deskripsi Proyek  

Proyek ini merupakan implementasi **Natural Language Processing (NLP)** untuk menganalisis pemberitaan internasional mengenai **Emirates Airlines**.  
Pendekatan utama yang digunakan meliputi:
- **TF-IDF** untuk menemukan kata kunci dominan,  
- **Part-of-Speech (POS) Tagging** untuk menganalisis struktur linguistik,  
- **Named Entity Recognition (NER)** untuk mengidentifikasi entitas penting, dan  
- **Sentiment Analysis** menggunakan model **FinBERT** dari *Hugging Face Transformers*.  

---

## 🎯 Tujuan Penelitian  

- Mengidentifikasi topik dan kata kunci dominan dalam pemberitaan *Emirates Airlines*.  
- Mengetahui kecenderungan sentimen (positif, netral, negatif) dalam berita internasional.  
- Memahami bagaimana media membingkai citra dan reputasi perusahaan.  

---

## ⚙️ Metodologi  

1. **Data Collection**  
   - Mengumpulkan 150 artikel berita dari media seperti *BBC, Reuters, CNN, Gulf News,* dan *Khaleej Times*.  
   - Dilakukan dengan kombinasi *manual search* dan *web scraping* menggunakan `BeautifulSoup` dan `Trafilatura`.  

2. **Preprocessing**  
   - Cleaning, tokenization, stopword removal, dan lemmatization menggunakan `NLTK`.  
   - Output: dataset teks bersih dan siap analisis.  

3. **Feature Extraction (TF-IDF)**  
   - Menggunakan `TfidfVectorizer` dari `scikit-learn`.  
   - Menghasilkan kata dominan seperti *emirates*, *flight*, *dubai*, *airline*, dan *service*.  

4. **Linguistic Analysis (POS & NER)**  
   - POS Tagging dan Named Entity Recognition menggunakan `spaCy`.  
   - Menemukan entitas penting seperti *Emirates*, *Dubai*, *UAE*, *Boeing*, *Tim Clark*.  

5. **Sentiment Analysis (FinBERT)**  
   - Menggunakan model `ProsusAI/finbert` untuk klasifikasi sentimen:  
     - 🟩 Positif: **4.00%**  
     - ⚪ Netral: **93.33%**  
     - 🟥 Negatif: **2.67%**  

---

## 📊 Hasil Utama  

- Mayoritas artikel bersentimen **netral**, menandakan pemberitaan bersifat objektif dan informatif.  
- **Sentimen positif meningkat pada 2024**, bertepatan dengan ekspansi layanan & pertumbuhan finansial.  
- **Sentimen negatif** muncul hanya pada kasus tertentu seperti penundaan penerbangan.  
- Citra *Emirates Airlines* di media global tergolong **stabil dan positif**.  

---

## 🧩 Tools & Library  

| Kategori | Library |
|-----------|----------|
| **Scraping** | `requests`, `BeautifulSoup`, `trafilatura`, `newspaper3k` |
| **Text Processing** | `pandas`, `nltk`, `re`, `string` |
| **NLP Models** | `spaCy`, `transformers`, `scikit-learn`, `torch` |
| **Visualization** | `matplotlib`, `seaborn`, `wordcloud` |

---


