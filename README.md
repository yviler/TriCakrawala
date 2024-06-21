<h1 align="center">  Batik Pedia / Tim AAI- Tricakrawala </h1>

<div align="center">
    <img src="Logo Batik Pedia.png">
</div>

<p align="center"> 
Ini adalah repository untuk contoh struktural yang bisa dipakai untuk melakukan dokumentasi Project Massive anda
</p>

<div align="center">
    <!-- Your badges here -->
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
    <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
    <img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white">
    <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white">
    <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white">
</div>

## Teams

- Moehammad Azzriel.I 
- Rayhan Favian Al Gaffar 
- Rizqi Hairunnisa 
- Surya Saputra

## Idea Background

### 1. Theme
Tema : "Batikpedia: Menjelajahi Warisan Budaya Batik Indonesia dengan Teknologi Canggih"

### 2. Problem
Masalah : 
- Kurangnya informasi mendalam: Banyak orang tertarik dengan batik, tetapi sulit menemukan informasi lengkap dan terpercaya tentang sejarah, filosofi, motif, dan teknik pembuatan batik.
- Keterbatasan pengetahuan Pengrajin Batik: Pengrajin batik, terutama generasi muda, seringkali tidak memahami makna dan nilai budaya di balik motif batik yang mereka buat. 
- Identifikasi Batik yang Sulit: Orang awam sering kesulitan mengetahui jenis batik, asal daerah, dan makna motif batik.


### 3. Solution
Solusi : 
- Website Informatif dan Interaktif: Menyediakan informasi lengkap tentang batik dalam bentuk artikel, gambar, video, dan infografis. Website juga dilengkapi dengan chatbot yang dapat menjawab pertanyaan pengunjung secara real-time.
- Aplikasi Mobile dengan Fitur Scan Batik: Memungkinkan pengguna untuk mengidentifikasi jenis batik, asal daerah, dan makna motif batik hanya dengan memindai foto batik menggunakan kamera smartphone.
- Database Motif Batik: Menyediakan database motif batik yang lengkap dengan penjelasan detail tentang makna, filosofi, dan asal daerah setiap motif.
- Fitur Pembelajaran Interaktif: Menawarkan kuis, permainan, dan tutorial interaktif untuk membantu pengguna mempelajari batik dengan cara yang menyenangkan.

## Dataset and Algorithm

### 1. Dataset
- Data Collection <br />
Dataset image didapatkan dengan image scraping menggunakan <a href=https://github.com/ultralytics/flickr_scraper>Ultralytics</a>
- Data Cleaning <br />
Kami menggunakan roboflow untuk membersihkan data image:
    1. Standardkan Resolusi 224x224px
    2. Greyscaling
    3. Augmentasi

### 2. Algorithm

- Framework <br />
Kami menggunakan TensorFlow dan Keras.

- Pembangunan Model <br />
Transfer Learning menggunakan MobileNetV2

- Model Evaluation <br />
Validation Accuracy: ~80%

## Prototype
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

## Integration
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

## Deployment
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

## Result
<img src="Preview  AI in Batik Pedia.png" alt="Alt text">
Bersama tim mobile & web development berhasil merealisasikan ide kami yakni membuat sebuah sistem identifikasi motif batik digital menggunakan aplikasi model dan sistem chatbot pada website untuk pengguna bertanya seputar batik di indonesia. Model berhasil diintegrasikan ke mobile dan web. Model berhasil mengidentifikasi motif batik yang di scan. Serta, chatbot dapat menjawab dan memberikan penjelasan dari pertanyaan pengguna.

## Conclusion
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.
