# IMDB Sentiment Analysis: RNN vs LSTM

## 📘 Studi Kasus
Proyek ini membandingkan performa **Simple RNN**, **RNN Bidirectional (2-layer)**, dan **LSTM** untuk tugas **analisis sentimen** (positif/negatif) pada dataset **IMDB Movie Review**.  
Studi ini menyoroti tantangan **long-term dependencies** pada teks panjang, serta bagaimana **LSTM** membantu mengatasi kendala RNN seperti **vanishing gradient**.

## 🎯 Tujuan
1. Membandingkan performa RNN vs LSTM pada klasifikasi sentimen IMDB.
2. Menganalisis perilaku training melalui loss/accuracy dan stabilitas gradien.
3. Mengevaluasi model menggunakan metrik klasifikasi dan confusion matrix.

## 📊 Data
Dataset: **IMDB Movie Review**
- Total **50.000 ulasan**
- Label seimbang:
  - **25.000 positif**
  - **25.000 negatif**


## 🔄 Alur Proyek
1. Preprocessing (cleaning, tokenisasi, stopwords)
2. Split data (train/val/test)
3. Tokenizing & padding
4. Modeling (RNN, BiRNN, LSTM)
5. Training & evaluation
6. Analisis lanjutan (gradien & panjang teks)


## 🤖 Modeling
Model yang dibandingkan:
- Simple RNN
- RNN Bidirectional (2-layer)
- LSTM


## ✅ Kesimpulan (Ringkas)
Secara umum, **LSTM** memberikan performa paling stabil dan unggul untuk review yang panjang karena lebih tahan terhadap **vanishing gradient** dibanding RNN.

## 🚀 Cara Menjalankan
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
