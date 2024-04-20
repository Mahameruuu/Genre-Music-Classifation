# Klasifikasi Genre Musik dengan Model CNN

Proyek ini bertujuan untuk mengklasifikasikan genre musik menggunakan model Convolutional Neural Network (CNN) 
dengan dataset GTZAN Genre Classification. Dataset ini terdiri dari 1.000 
trek audio, masing-masing berdurasi 30 detik, dan mencakup 10 genre musik yang berbeda.

# Deskripsi Dataset

Dataset GTZAN Genre Classification terdiri dari:

1. **Genres original**: Koleksi 10 genre dengan masing-masing 100 file audio, setiap file memiliki durasi 30 detik.
Images original: Representasi visual untuk setiap file audio.
2. **file CSV**: Berisi fitur-fitur dari file audio. Salah satu file memiliki rata-rata dan varian yang
   dihitung dari beberapa fitur yang diekstrak dari file audio. File lain memiliki struktur yang sama,
   tetapi lagu-lagu sudah dibagi menjadi file audio 3 detik.

# Langkah-langkah dalam Proyek

1. **Reading and Understanding the Data**: Membaca dan memahami data menggunakan Python libraries seperti pandas dan librosa.
2. **Understanding the Audio Files**: Memahami fitur-fitur audio seperti tempo, chroma energy normalized, dan lainnya dengan menggunakan library librosa.
3. **Visualizing Audio Files**: Visualisasi file audio menggunakan plot raw wave, spectrograms, spectral rolloff, chroma feature, dan zero crossing rate.
4. **Feature Extraction**: Ekstraksi fitur-fitur audio untuk persiapan data sebelum melatih model.
5. **Scaling the Features**: Standarisasi fitur-fitur untuk menghilangkan mean dan scaling menjadi unit variance.
6. **Dividing Data Into Training and Testing Sets**: Pembagian data menjadi set latih dan set uji.
7. **Building the Model**: Membangun model CNN menggunakan TensorFlow untuk melakukan klasifikasi genre musik.
8. **Model Evaluation**: Evaluasi model menggunakan metrik-metrik seperti akurasi dan loss.

# Library dan Tools yang Digunakan

**Librosa**: Library Python untuk analisis musik dan audio.
**Pandas**: Library Python untuk analisis data.
**TensorFlow**: Library untuk pembelajaran mesin dan pembangunan model neural networks.
**Sklearn**: Library untuk preprocessing data seperti LabelEncoder dan StandardScaler.

# Cara Menggunakan Proyek

1. Clone repository ini ke lokal komputer Anda.
2. Pastikan Anda memiliki semua library dan dependencies yang diperlukan yang tercantum dalam file requirements.txt.
3. Jalankan notebook atau script Python untuk melihat langkah-langkah dalam proyek dan hasil akhir dari klasifikasi genre musik menggunakan model CNN.

# Hasil Akhir

Model CNN yang dibangun dalam proyek ini mencapai akurasi sebesar 92% untuk set data uji,
menunjukkan bahwa pendekatan ini efektif dalam klasifikasi genre musik.

