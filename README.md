# PREDIKSI-HARGA-RUMAH

## A. Raw Data
Dataset (train.csv) memiliki 1.460 baris dan 81 kolom/fitur dengan 1 kolom target SalePrice (harga jual rumah).  

## B. library
Menggunakan library pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, lightgbm, shap

## C. Algoritma
Menggunakan beberapa algoritma berikut.
1. Random Forest      = Ensemble bagging, 300 pohon
2. XGBoost            = Gradient boosting, 500–1200 pohon
3. LightGBM + XGBoost = Ensemble stacking dua model boosting
4. RandomizedSearchCV = Hyperparameter tuning untuk RF & XGBoost

## D. Evaluasi Model
Kualitas prediksi dievaluasi menggunakan visualisasi berikut.
1. Residual vs Fitted = Mengecek pola error
2. Residual Histogram = Memeriksa normalitas error
3. QQ Plot            = Validasi asumsi normalitas residual
4. SHAP Value         = interpretasi kontribusi tiap fitur terhadap prediksi
