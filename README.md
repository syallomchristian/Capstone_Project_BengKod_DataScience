# 🚀 PROJECT CAPSTONE BENGKOD

### 🎯 Tujuan Proyek
Proyek ini bertujuan untuk membangun model machine learning yang dapat **memprediksi kategori obesitas** seseorang berdasarkan data pribadi dan kebiasaan hidup, seperti usia, tinggi badan, berat badan, dan jenis kelamin. Model ini dikembangkan sebagai bagian dari proyek capstone Bangkit Academy oleh tim BENGKOD.

---

## 🧠 Latar Belakang
Obesitas merupakan salah satu permasalahan kesehatan yang berkembang secara global dan dapat memicu berbagai penyakit kronis seperti diabetes, hipertensi, dan penyakit jantung. Dengan memanfaatkan data dan machine learning, kita dapat **mendeteksi potensi obesitas lebih awal** dan memberikan saran pencegahan berbasis data.

---

## 🛠️ Teknologi & Tools

- Python
- Scikit-learn (Random Forest Classifier)
- Pandas
- Streamlit (untuk deployment aplikasi interaktif)
- Joblib (untuk menyimpan model)
- Git & GitHub (versi kontrol)

---

## 📊 Dataset
Dataset yang digunakan berasal dari dataset publik yang berisi informasi gaya hidup dan hasil klasifikasi obesitas seseorang berdasarkan beberapa parameter medis dan kebiasaan hidup.

**Target Kolom**: `NObeyesdad`  
**Fitur yang digunakan**:
- Age  
- Height  
- Weight  
- Gender (Male/Female → numerikal)  
- (Opsional) family_history_with_overweight

---

## 🧪 Training Model

Model yang digunakan: **Random Forest Classifier**

Proses:
- Pra-pemrosesan data
- Encoding fitur kategorikal
- Hyperparameter tuning menggunakan `GridSearchCV`
- Evaluasi akurasi, precision, recall, dan F1 score
- Menyimpan model terbaik ke file `.pkl`

---

## 🌐 Deploy Aplikasi

Aplikasi dibuat menggunakan **Streamlit** dan dapat dijalankan secara lokal atau dideploy ke **Streamlit Cloud**.

### Menjalankan Aplikasi

```bash
pip install -r requirements.txt
streamlit run app.py
