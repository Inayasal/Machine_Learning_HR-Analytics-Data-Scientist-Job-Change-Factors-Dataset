# HR Analytics: Data Scientist Job Change Factors

Repository ini berisi proyek tugas mata kuliah Machine Learning mengenai analisis dan prediksi kemungkinan seorang Data Scientist untuk mencari atau berpindah pekerjaan berdasarkan faktor-faktor yang terdapat dalam data HR menggunakan Python.

## Informasi Mahasiswa

1. Nama: Inaya Salsabila
2. Universitas: Universitas Pamulang
3. Kelas: 05TPLP022

## Tentang Proyek

Proyek ini bertujuan untuk menganalisis data HR dan membangun model Machine Learning yang dapat memprediksi kemungkinan seorang kandidat Data Scientist untuk mencari atau berpindah pekerjaan.

Dataset yang digunakan terdiri dari data training dan testing:

- `aug_train.csv` → Dataset untuk proses training
- `aug_test.csv` → Dataset untuk pengujian

Proses proyek meliputi:

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Pengolahan data
4. Pembangunan model Machine Learning
5. Evaluasi model
6. Penyimpanan model
7. Deployment model menggunakan Flask REST API

## Dataset

Dataset berisi informasi mengenai kandidat Data Scientist, seperti:

- `enrollee_id`
- `city`
- `city_development_index`
- `gender`
- `relevant_experience`
- `enrolled_university`
- `education_level`
- `major_discipline`
- `experience`
- `company_size`
- `company_type`
- `last_new_job`
- `training_hours`

Target prediksi digunakan untuk mengetahui kemungkinan kandidat melakukan perubahan atau mencari pekerjaan baru.

## Sumber Dataset
Dataset yang digunakan dalam proyek HR Analytics: Data Scientist Job Change Factors berasal dari Kaggle.

Nama dataset: HR Analytics: Data Scientist Job Change Factors
Platform: Kaggle
Link dataset: [https://www.kaggle.com/datasets/obaidhere/hr-analytics-data-scientist-job-change-factors]

## Teknologi yang Digunakan

1. Python
2. Jupyter Notebook
3. Pandas
4. NumPy
5. Matplotlib
6. Scikit-learn
7. Flask
8. REST API
9. Joblib / Pickle

## Machine Learning Model

Model Machine Learning yang digunakan adalah **Gradient Boosting Regressor (GBR)**.

Model yang telah dilatih disimpan dalam bentuk:

- `gbr_model.joblib`
- `gbr_model.pkl`

Model tersebut kemudian digunakan oleh aplikasi Flask untuk menghasilkan prediksi melalui REST API.

## Deployment dan REST API

Model Machine Learning di-deploy menggunakan **Flask** sebagai REST API.

File utama untuk menjalankan API:

```text
python app.py
