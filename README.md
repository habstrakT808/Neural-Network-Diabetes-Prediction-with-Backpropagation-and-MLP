# Proyek Jaringan Saraf Tiruan

![License](https://img.shields.io/badge/license-MIT-green)  

Proyek ini menampilkan implementasi jaringan saraf dari awal tanpa menggunakan pustaka, serta menggunakan `MLPClassifier` dari Scikit-learn untuk melatih jaringan saraf pada dataset yang terkait dengan prediksi diabetes.

---

## Implementasi Manual
- Melakukan implementasi feedforward, backpropagation, dan pembaruan bobot secara manual.
- Mendemonstrasikan proses tersebut dengan dataset contoh dan parameter jaringan yang ditentukan.

## Pengolahan Data dengan Pustaka
- Memuat, membersihkan, dan memproses dataset terkait prediksi diabetes menggunakan Pandas dan Scikit-learn.
- Mengkodekan fitur kategoris dan normalisasi data menggunakan StandardScaler.

## Pelatihan dengan MLPClassifier
- Melatih jaringan saraf menggunakan `MLPClassifier` dari Scikit-learn.
- Mengevaluasi model menggunakan metrik seperti akurasi, presisi, recall, dan F1-score.
- Menyetel hiperparameter menggunakan `RandomizedSearchCV` untuk kinerja yang lebih baik.

## Visualisasi dan Analisis
- Menganalisis kinerja model menggunakan matriks kebingungan dan laporan klasifikasi.
- Menggunakan PCA untuk reduksi dimensionalitas dan visualisasi.

## File
- `manual_neural_network.py`: Berisi implementasi manual dari algoritma feedforward dan backpropagation.
- `neural_network_with_library.py`: Menunjukkan pelatihan jaringan saraf menggunakan `MLPClassifier`.
- `data_processing_with_libraries.py`: Menunjukkan langkah-langkah pengolahan data dengan Pandas dan Scikit-learn.
- `README.md`: Ikhtisar proyek.

## Dependensi
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Silakan jelajahi file kode dan dataset yang disediakan di repositori ini. Jika Anda memiliki pertanyaan atau saran, jangan ragu untuk menghubungi saya.

---
