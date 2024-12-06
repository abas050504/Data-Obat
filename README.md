# Proyek Klasifikasi Obat

## Anggota Kelompok
M. Hasan Basri : 2205903040041
Munawar Khaliq : 2205903040071
Yuliana risfa : 2205903040064
Raihan Putri : 2205903040006
Cut handriyani : 2205903040084

## Deskripsi  
Proyek ini bertujuan untuk mengklasifikasikan pasien ke dalam kategori obat tertentu berdasarkan atribut kesehatan mereka dengan menggunakan pendekatan pembelajaran mesin (supervised learning). Dataset mencakup berbagai atribut pasien seperti usia, jenis kelamin, tekanan darah, kadar kolesterol, rasio natrium terhadap kalium, dan jenis obat (variabel target).  

Model klasifikasi ini diharapkan dapat membantu merekomendasikan obat yang paling sesuai untuk pasien berdasarkan profil medis mereka.  

---

## Dataset  
Dataset yang digunakan adalah **Dataset Klasifikasi Obat**, yang berisi data tentang 200 pasien dan obat yang diresepkan untuk mereka. Dataset ini dibagi menjadi:  
- **Data Latih**: 140 sampel (70%)  
- **Data Uji**: 60 sampel (30%)  

### Atribut Dataset:  
1. **Age**: Usia pasien (dalam tahun).  
2. **Sex**: Jenis kelamin pasien (Male/Female).  
3. **BP**: Tingkat tekanan darah (Low/Normal/High).  
4. **Cholesterol**: Tingkat kolesterol (Normal/High).  
5. **Na_to_K**: Rasio natrium terhadap kalium dalam darah.  
6. **Drug**: Kategori obat (Drug A, Drug B, Drug C, Drug D, atau Drug X).  

### Sumber Dataset  
Dataset diperoleh dari sumber terpercaya dan diolah untuk tujuan klasifikasi.  

---

## Teknologi yang Digunakan  
- **Bahasa Pemrograman**: Python  
- **Library**:  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Scikit-learn  

---

## Langkah-Langkah Proyek  
1. **Pra-pemrosesan Data**:  
   - Pembersihan data.  
   - Transformasi nilai kategorikal menjadi numerik.  

2. **Pengembangan Model**:  
   - Membagi dataset menjadi data latih dan data uji.  
   - Melatih model menggunakan algoritma klasifikasi seperti Decision Tree atau Random Forest.  

3. **Evaluasi Model**:  
   - Mengukur akurasi, presisi, recall, dan F1-score.  

---

## Cara Menjalankan  
1. Clone repository ini:  
   ```bash
   git clone https://github.com/username/drug-classification.git
