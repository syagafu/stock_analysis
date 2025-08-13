# 📈 Analisis & Prediksi Harga Saham dengan Deep Learning

Aplikasi web interaktif yang dibangun menggunakan Streamlit untuk menganalisis data historis harga saham dan memprediksi pergerakan harga di masa depan menggunakan model *Deep Learning* (LSTM & GRU).

##  Demo / Tampilan Aplikasi

*(Sangat disarankan untuk menambahkan screenshot aplikasi Anda di sini. Jalankan aplikasi Anda, ambil screenshot, lalu letakkan file gambarnya di folder proyek Anda dengan nama `demo.png` misalnya. Kemudian hapus komentar baris di bawah ini)*
<!-- ![Tampilan Aplikasi Saham](demo.png) -->

## 📜 Deskripsi

Aplikasi ini memungkinkan pengguna untuk:
1.  Memilih **kode saham** dari Yahoo Finance (misalnya, `BBCA.JK`, `GOOGL`).
2.  Menentukan **rentang waktu** data historis yang akan dianalisis.
3.  Memilih dan mengonfigurasi **model *Deep Learning*** (LSTM atau GRU) untuk prediksi.
4.  Mengatur berbagai **hiperparameter** seperti *time steps*, *epochs*, *batch size*, dan *learning rate* untuk eksperimen.
5.  Melihat **hasil prediksi** yang dibandingkan dengan data aktual pada grafik interaktif.
6.  Mendapatkan **prediksi harga untuk beberapa hari ke depan**.
7.  Menganalisis **kinerja model** melalui grafik *loss* dan metrik akurasi (berbasis MAPE).

## ✨ Fitur Utama

- **Dasbor Interaktif**: Visualisasi data harga saham historis dan hasil prediksi menggunakan Plotly.
- **Pilihan Model**: Fleksibilitas untuk memilih antara arsitektur LSTM dan GRU.
- **Kustomisasi Hiperparameter**: Panel kontrol untuk menyesuaikan parameter model secara *real-time*.
- **Evaluasi Kinerja**: Metrik seperti Akurasi (100% - MAPE) dan grafik *Training vs Validation Loss* untuk menganalisis *overfitting*.
- **Prediksi Masa Depan**: Kemampuan untuk memproyeksikan harga saham untuk *N* hari ke depan.
- **Statistik Historis**: Ringkasan statistik data per tahun untuk melihat tren jangka panjang.

## 💻 Teknologi yang Digunakan

- **Backend & Model**: Python, TensorFlow (Keras), Scikit-learn, Pandas, NumPy
- **Frontend**: Streamlit
- **Sumber Data**: Yahoo Finance (`yfinance`)
- **Visualisasi**: Plotly

## 🚀 Instalasi & Cara Menjalankan

Untuk menjalankan aplikasi ini di komputer lokal Anda, ikuti langkah-langkah berikut:

**1. Clone Repositori**
```bash
git clone https://github.com/NAMA_USER_ANDA/NAMA_REPOSitori_ANDA.git
cd NAMA_REPOSitori_ANDA
```

**2. (Sangat Direkomendasikan) Buat dan Aktifkan Virtual Environment**
*   Untuk MacOS/Linux:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
*   Untuk Windows:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

**3. Instal Paket yang Dibutuhkan**
```bash
pip install -r requirements.txt
```

**4. Jalankan Aplikasi Streamlit**
```bash
streamlit run stock.py
```
Aplikasi akan otomatis terbuka di browser Anda.

##  disclaimer

Aplikasi ini dibuat hanya untuk tujuan edukasi dan demonstrasi teknologi. **Ini bukan merupakan saran finansial.** Segala keputusan investasi yang Anda ambil adalah tanggung jawab Anda sepenuhnya.
