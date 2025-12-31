# Spooky Author Identification 🕸️✍️

Proyek ini bertujuan untuk mengidentifikasi penulis teks horor klasik berdasarkan gaya penulisan mereka menggunakan teknik **Natural Language Processing (NLP)** dan **Machine Learning**. Dataset ini diambil dari kompetisi Kaggle "Spooky Author Identification".

## 📋 Deskripsi Proyek
Tujuan utama dari notebook ini adalah untuk memprediksi probabilitas identitas penulis dari sebuah kutipan kalimat. Penulis yang diidentifikasi adalah:
1. **EAP**: Edgar Allan Poe
2. **HPL**: HP Lovecraft
3. **MWS**: Mary Wollstonecraft Shelley

## 🛠️ Tech Stack & Library
Proyek ini menggunakan bahasa pemrograman Python dengan beberapa library utama:
- **Pandas & NumPy**: Manipulasi dan analisis data.
- **Scikit-learn**: Pemodelan Machine Learning dan ekstraksi fitur.
- **NLTK / SpaCy**: Preprocessing teks (Tokenization, Lemmatization, Stopwords removal).
- **Matplotlib & Seaborn**: Visualisasi data.

## 🚀 Fitur & Workflow
Alur kerja dalam `NLP_Classification_Notebook.ipynb` meliputi:
1. **Exploratory Data Analysis (EDA)**: Melihat distribusi kata-kata populer untuk setiap penulis dan panjang kalimat.
2. **Text Preprocessing**: Membersihkan teks dari tanda baca, angka, dan melakukan normalisasi (lowercase & lemmatization).
3. **Feature Engineering**: 
   - TF-IDF Vectorization.
   - Count Vectorizer.
   - Penambahan fitur metadata (panjang kata, jumlah tanda baca, dll).
4. **Model Building**: Implementasi berbagai algoritma klasifikasi seperti:
   - Multinomial Naive Bayes
   - Logistic Regression
   - XGBoost / Random Forest (sesuaikan dengan isi notebookmu)
5. **Evaluation**: Menggunakan metric *Multi-class Log Loss* untuk mengukur performa model.

## 📁 Struktur Repositori
- `NLP_Classification_Notebook.ipynb`: Notebook utama berisi analisis dan model.
- `train.csv` / `test.csv`: Dataset yang digunakan (disarankan download dari Kaggle).

## 💻 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/ciell0/Spooky-Author-Identification.git](https://github.com/ciell0/Spooky-Author-Identification.git)
