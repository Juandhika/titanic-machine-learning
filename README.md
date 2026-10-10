# Titanic Survival Prediction

Project latihan end-to-end Machine Learning buat nemuin pola dan memprediksi keselamatan penumpang Titanic.

### Summary
- Masalah: Klasifikasi (Selamat / Gak Selamat)
- Dataset: Titanic Kaggle (train.csv)
- Model: Random Forest Classifier
- Akurasi: ~80% (Training 80.45% vs Testing 80.00% — Good Fit, gak overfitting)

### Step Pengerjaan
1. Cleaning: Isi data bolong di Age (median) & Embarked (modus). Drop kolom gak kepake (PassengerId, Name, Ticket, Cabin).
2. Preprocessing: Ubah teks ke angka (One-Hot Encoding) & rapiin skala data (StandardScaler).
3. Split Data: Rasio 80% train & 20% test.
4. Training & Evaluasi: Latih model Random Forest + cek akurasi & confusion matrix.

### Cara Run
1. Clone repo ini.
2. Install library: pip install pandas numpy scikit-learn jupyter
3. Buka dan run latihan_ml.ipynb di VS Code / Jupyter Notebook.# titanic-machine-learning
project klasifikasi machine learning prediksi keselamatan penumpang titanic
