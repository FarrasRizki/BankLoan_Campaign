# Bank Personal Loan Campaign
Project by Muhammad Farras Rizki


## A. Latar Belakang
Dataframe ini milik sebuah bank bernama Thera Bank. Manajemen Thera Bank ingin membuat para nasabah untuk menggunakan jasa pinjaman pribadi dari bank (dengan tetap mempertahankan mereka sebagai deposan). Tahun lalu telah didakan sebuah kampanye yang membuat para nasabah (deposan) Thera Bank menggunakan jasa pinjaman pribadi, dengan tingkat keberhasilan 9%. Hal ini mendorong departemen pemasaran ritel untuk merancang kampanye dengan target pemasaran yang lebih baik untuk meningkatkan rasio keberhasilan dengan anggaran yang minimal.


## B. Tentang Dataframe
Dataframe berisi data 5000 nasabah. Data tersebut meliputi informasi demografis nasabah (umur, pendapatan, dll), hubungan nasabah dengan bank (hipotek, rekening, surat berharga, dll), dan respon nasabah terhadap kampanye pinjaman pribadi sebelumnya (`Personal Loan`). Di antara 5000 nasabah ini, hanya 480 (= 9,6%) yang menggunakan jasa pinjaman pribadi yang ditawarkan kepada mereka pada kampanye sebelumnya.


## C. Tujuan Proyek
1. Menemukan Business Insight yang dapat membantu meningkatkan rasio keberhasilan kampanye
2. Membuat model machine learning untuk memprediksi minat nasabah dalam menggunakan jasa pinjaman pribadi


## D. Sumber Dataset
Sumber: https://www.kaggle.com/datasets/krantiswalke/bank-personal-loan-modelling


## E. Deskripsi singkat akan pemodelan yang digunakan
Tujuan dari pemodelan adalah ingin membuat model yang mampu memprediksi minat seorang nasabah dalam menggunakan jasa pinjaman pribadi. Target Variabel yang akan digunakan adalah `Personal Loan` (respon nasabah terhadap kampanye pinjaman pribadi sebelumnya). Variabel yang paling diinginkan untuk optimal adalah Recall, dengan tujuan meminimalisir kesalahan prediksi pada nasabah yang sebenarnya ingin menggunakan jasa pinjaman.

Hipotesis yang dibuat berdasarkan target variabel :
- 0: Nasabah tidak berminat menggunakan jasa pinjaman pribadi (Negative)
- 1: Nasabah berminat menggunakan jasa pinjaman pribadi (Positive)

Model Machine Learning yang akan diuji antara lain:
1. Logical Regression
2. K-NN
3. Decision Tree Classification
4. Random Forest Classification


## F. Deskripsi singkat tiap file
1. Bank Loan Modelling Project.ipynb : File python berisi coding dalam melakukan Exploratory Data Analysis (EDA) dan Model Machine Learning 
2. Bank Loan_ Column Description.txt : File Note berisi keterangan kolom
3. Bank Personal Loan Campaign.pdf : File PDF berisi kesimpulan dan rekomendasi dari analisa data
4. Bank_Personal_Loan_Modelling.csv : File CSV berisi Dataset Bank Personal Loan
