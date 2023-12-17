# Sentiment Analysis dengan Metode Support Vector Machine terhadap Kasus Perundungan di Dunia Maya 
## Latar Belakang
Semenjak internet hadir, perundugan tidak hanya terjadi pada dunia nyata, bahkan perundungan dapat terjadi di dunia maya  perundungan di dunia maya melalui berbagai platform sosial media seperti Instagram, Facebook, X, atau bahkan platform uang menggunaan internet lainnya seperti game online. Bentuk perundungan di dunia maya seperti pelecehan verbal, ancaman, hingga penyebaran informasi pribadi yang bersifat negatif. Walaupun bentuk perundungan di dunia maya tidak berupa fisik, namun efek negatif yang ditimbulkan dapat berbahaya kepada korban, terlebih, terkadang sebagian masyarakat masih tak acuh dengan isu ini dengan dalih bercanda.

Oleh karena itu, dikembangkanlah sebuah machine learning yang mampu menganalisis sentimen untuk mendeteksi kasus perundungan di dunia maya.

## Metode 
Metode klasifikasi yang digunakan dalam penelitian yakni:
- Support Vector Machine

Metode pembobotan kata yang digunakan dalam penelitian yakni: 
- TF-IDF

## Referensi
Referensi penelitian ini ialah penelitian sebelumnya yang dilakukan oleh Auliya Rahman Isnain , Adam Indra Sakti, Debby Alita, Nurman Satya Marga dengan judul yang dapat dilihat pada tautan [berikut ini🔗](https://ejurnal.teknokrat.ac.id/index.php/JDMSI/article/view/1021)

Pada penelitian tersbut telah berhasil dilakukan sentimen analisis publik terhadap kebijakan lockdown pemerintah jakarta menggunakan algoritma svm. Hal yang membedekan dengan penelitian yang sedang penulis lakukan ialah:
- studi kasus pada penelitian ini ialah perundungan di dunia maya
- penelitian ini menggunakan dua kernel pengujian yakni kernel linear dan RBF

## Dataset
Dataset yang digunakan merupakan dataset yang didapatkan di kaggle pada tautan [berikut ini 🔗](https://www.kaggle.com/datasets/cttrhnn/cyberbullying-bahasa-indonesia/data) 

Dataset yang didapatkan merupakan sebuah file dengan format .xlsx yang berisi hasil crawling Twitter dengan jumlah tweet sebanyak 650 tweet yang terdiri dua kelas yakni non-bullying atau bullying.
Berikut merupakan contoh dari dataset yang didapatkan: 👇
![Screenshot (358)](https://github.com/ahmadhilmandani/riset-informatika-tgs-1/assets/88090086/2cf27ee2-50eb-4502-9b1d-b82d089e1e42)

## Code
code untuk Sentiment Analysis dengan Metode Support Vector Machine terhadap Kasus Perundungan di Dunia Maya dapat dilihat pada tautan [berikut ini🔗](https://colab.research.google.com/drive/1oDz4LjBaJ27pKoDQNzcDtT7cNjcTRiGr?usp=sharing)

## Confusion Matrix untuk Analisis Pengujian

