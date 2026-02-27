# IMDB Sentiment Analysis: RNN vs LSTM

## 📘 Studi Kasus
Proyek ini membandingkan performa **Simple RNN**, **RNN Bidirectional (2-layer)**, dan **LSTM** untuk tugas **analisis sentimen** (positif/negatif) pada dataset **IMDB Movie Review**.  
Studi ini menyoroti tantangan **long-term dependencies** pada teks panjang, serta bagaimana **LSTM** membantu mengatasi kendala RNN seperti **vanishing gradient**.

## 🎯 Tujuan
1. Membandingkan performa RNN vs LSTM pada klasifikasi sentimen IMDB.
2. Menganalisis perilaku training melalui loss/accuracy dan stabilitas gradien.
3. Mengevaluasi model menggunakan metrik klasifikasi dan confusion matrix.

## 📊 Data
Dataset yang digunakan adalah **IMDB Dataset of 50K Movie Reviews** dari Kaggle (author: **lakshmi25npathi**). Dataset berisi **50.000 ulasan** dengan label seimbang (**25.000 positif** dan **25.000 negatif**).
Sumber dataset:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews


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
