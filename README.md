# Kelompok [18] _Deep Learning_ - Analisis Perbandingan Prediksi Suhu Baterai Li-Ion Polymer Berdasarkan Voltase Menggunakan Metode RNN dan GRU
Proyek ini dikembangkan oleh Team-X dalam rangka tugas besar mata kuliah Deep Learning, dengan fokus pada analisis prediksi suhu baterai Li-Ion menggunakan dua metode neural network: Recurrent Neural Network (RNN) dan Gated Recurrent Unit (GRU). Penelitian ini bertujuan untuk memprediksi suhu baterai Li-Ion berdasarkan voltase untuk meningkatkan pengelolaan suhu dan keselamatan baterai.

![Gambar Baterai Li-Ion](https://cdn1-production-images-kly.akamaized.net/mgrEiHs346Rtj1GNcmrIVr7XQfM=/1200x675/smart/filters:quality(75):strip_icc():format(webp)/kly-media-production/medias/34329/original/ion-130812b.jpg)

## 📌 Anggota Kelompok
1. Annisa Novantika (121450005)
2. Sylviani Primaastuti Ananda (121450042)
3. Rahmat Putra Aji (121450053)
4. Nadia Silvani (121450054)
5. Jelli Kurnilia (121450083)
6. Muhammad Fathir Fadillah (121450098)

## 🚀 Tujuan Proyek
Penelitian ini bertujuan untuk membandingkan kinerja model RNN dan GRU dalam memprediksi suhu baterai Li-Ion Polymer berdasarkan parameter voltase. Tujuan utama dari proyek ini adalah untuk memberikan prediksi yang lebih akurat dan stabil dalam memonitor suhu baterai.

## 📂 Dataset
Dataset yang digunakan dalam penelitian ini terdiri dari data pengukuran suhu dan voltase baterai Li-Ion Polymer yang diperoleh dari pengujian pada perangkat Infinix X6739, dengan total 720 sampel data.

**Link Dataset**: [Dataset Pengukuran Suhu dan Voltase](URL_Dataset)

## 🛠️ Teknologi yang Digunakan
* **Python** untuk pemrograman
* **TensorFlow/Keras** untuk pembuatan model RNN dan GRU
* **Matplotlib** dan **Seaborn** untuk visualisasi hasil

## 🧠 Model yang Digunakan
1. **Recurrent Neural Network (RNN)**: Model yang digunakan untuk memproses data berurutan dan memprediksi suhu berdasarkan voltase.
2. **Gated Recurrent Unit (GRU)**: Model dengan struktur yang lebih efisien dan cocok untuk prediksi deret waktu dengan data dinamis.

## 📊 Metodologi
1. **Preprocessing Data**: Data voltase dan suhu diproses untuk digunakan dalam pelatihan model.
2. **Pelatihan Model**: Menggunakan RNN dan GRU dengan kombinasi parameter seperti epoch, learning rate, dan jumlah neuron.
3. **Evaluasi Model**: Menggunakan Mean Square Error (MSE) untuk mengukur seberapa baik model bekerja atas data validasi.
4. **Pengecekan Train-Val Loss** : Nilai validation dan train loss dicek sepanjang berjalannya epoch baik untuk kombinasi terbaik untuk RNN maupun GRU untuk mengecek apakah kedua model dengan kombinasi terbaiknya

## 📈 Hasil yang Diharapkan
* Mendapatkan model dengan kombinasi hyper parameter terbaiknya yang unggul dibandingkan yang lain baik saat pelatihan sepanjang epoch maupun pengujiannya atas data tes.
* Hasil prediksi suhu baterai lithium-ion polymer berdasarkan voltase menggunakan model dengan kombinasi terbaiknya.

## Flowchart 
![Deskripsi Gambar](URL_Gambar_Flowchart)

## 🧑‍💻 Cara Menjalankan Proyek
1. **Clone repositori**:
   ```
   git clone https://github.com/sains-data/Prediksi-Suhu-Baterai-Li-Ion-RNN-GRU.git
   ```
2. **Masuk ke direktori proyek**:
   ```
   cd Prediksi-Suhu-Baterai-Li-Ion-RNN-GRU
   ```
3. **Instal dependensi**:
   ```
   pip install -r requirements.txt
   ```
4. **Jalankan notebook atau script**:
   ```
   python main.py
   ```

## 👥 Kontibutor
* Annisa Novantika - [Github](https://github.com/annisanovantika)
* Sylviani Primaastuti Ananda - [Github](https://github.com/sylvianipa)
* Rahmat Putra Aji - [Github](https://github.com/RahmatPa)
* Nadia Silvani - [Github](https://github.com/naddslvn)
* Jelli Kurnilia - [Github](https://github.com/JelliKurnilia)
* Muhammad Fathir Fadillah - [Github](https://github.com/fadillah180403)

## 📫 Kontak
Jika ada pertanyaan, silakan hubungi:

- ✉️ **Email:**
  - annisa.121450005@student.itera.ac.id
  - sylviani.121450042@student.itera.ac.id
  - rahmat.121450053@student.itera.ac.id
  - nadia.121450054@student.itera.ac.id
  - jelli.121450083@student.itera.ac.id
  - muhammad.121450098@student.itera.ac.id

## 🔗 Tautan Kelompok
Kunjungi ...

```
