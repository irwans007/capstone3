# capstone3 by Irwan

Travel Insurance Claim Prediction

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model machine learning yang dapat memprediksi apakah seorang pelanggan akan mengajukan klaim asuransi perjalanan atau tidak, berdasarkan data historis pelanggan dan perjalanan.

## 🧠 Business Problem
Perusahaan asuransi ingin mengantisipasi risiko klaim dengan memprediksi kemungkinan pelanggan akan mengajukan klaim. Solusi ini membantu dalam proses underwriting dan perhitungan premi yang lebih adil.


## 🔍 Proses
1. Data Cleaning & Imputasi missing value
2. One-Hot Encoding fitur kategorikal
3. Penanganan data imbalance dengan Upsampling
4. Modeling:
   - Logistic Regression
   - Random Forest
   - Voting Classifier (Final Model)
5. Evaluasi menggunakan:
   - F1 Score
   - Recall
   - ROC AUC

## ✅ Model Final
Model akhir yang dipilih adalah **Voting Classifier**, karena memberikan hasil paling seimbang antara recall dan ROC AUC.

Disimpan sebagai file: [`voting_model.pkl`](./voting_model.pkl)


