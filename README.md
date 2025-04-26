# Penerapan Metode Klasifikasi Machine Learning dalam Analisis Sentimen Komentar YouTube terkait Mobil Listrik

Maryesta Apriliani Sihombing

Program Studi Statistika, Fakultas Matematika dan Ilmu Pengetahuan Alam, Universitas Indonesia

maryesta.apriliani@ac.ui.id


---

## Abstrak 
Analisis sentimen YouTube mengkategorikan perspektif atau opini yang diungkapkan dalam kolom komentar video. Dalam penelitian ini, analisis dilakukan pada komentar salah satu video YouTube yang membahas kemunculan kendaraan listrik di Indonesia, yang memicu beragam tanggapan, baik pro maupun kontra. Tujuan penelitian ini adalah memahami persepsi publik terhadap mobil listrik dan membuat model klasifikasi sentimen dari dataset komentar Youtube.  Sebanyak 1.517 komentar dilabeli secara manual ke dalam sentimen positif, negatif, dan netral, kemudian diproses melalui tahapan preprocessing dan vektorisasi TF-IDF (Term Frequency–Inverse Document Frequency). Mengatasi ketidakseimbangan data, metode SMOTE (Synthetic Minority Oversampling Technique) diterapkan sebelum modeling. Sepuluh algoritma klasifikasi (Random Forest, Multinomial Naive Bayes, Gaussian Naive Bayes, Support Vector Machine, XGBoost, Regresi Logistik, Decision Tree, Bagging, Ada Boost, dan Gradient Boosting) dibandingkan dan evaluasi dilakukan menggunakan k-fold cross validation dengan metrik akurasi, precision, recall, dan F1-Score. Support Vector Machine (SVM) dengan SMOTE terpilih sebagai model terbaik yang setelah hyperparameter tuning mencapai akurasi 73,03% dan CV Mean Accuracy 91,61%. Hasil analisis sentimen menunjukkan dominasi komentar negatif (57,3%) serta isu harga dan subsidi sebagai topik utama pembahasan publik terkait mobil listrik di Indonesia.

---

## Keywords:
Text Mining, Natural Language Processing, Imbalance Data, Support Vector Machine, Sentiment Analysis

