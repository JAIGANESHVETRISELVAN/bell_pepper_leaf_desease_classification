# Sistem Informasi Deteksi Daun Paprika (SIDEPRIKA)

Sideprika singkatan dari Sistem Informasi Deteksi Penyakit Daun Paprika yang merupakan hasil pengembangan aplikasi dari penelitian tesis tentang image processing. Dalam penelitian ini dibangun menggunakan Fine-Tuned Transfer Learning dengan arsitektur DenseNet121 yang dilatih ulang dengan parameter FC Layer yang baru. Hasil akhir pada penelitian ini didapatkan tingkat akurasi sebesar **99.30%** dan nilai cohen's cappa sebesar **0.9865** dengan kata lain penelitian ini dikatakan penelitian yang **Sangat Kuat (Very Good)**.

## Halaman Beranda
<img src="static/img/Halaman Beranda Aplikasi2.png"/>

## Halaman Prediksi
<img src="static/img/Halaman Prediksi Aplikasi2.png"/>

## BackEnd

```
Python 3.8.5
```
## Install

```
Download this project and enter the project folder from command line

```

```
pip install -r requirements.txt

```

```

It will take time to install all dependencies and DenseNet121 model

```

```
python app.py

```

```
Open Browser and type http://localhost:5000

```
