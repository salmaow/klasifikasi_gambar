# Proyek Klasifikasi Gambar

```
Proyek ini bertujuan untuk membangun model klasifikasi gambar untuk membedakan antara kucing dan anjing.
Sumber Dataset: https://www.kaggle.com/datasets/ashfakyeafi/cat-dog-images-for-classification

Isi:
Gambar-gambar kucing dan anjing yang telah dipisahkan ke dalam folder masing-masing.

Cocok untuk tugas klasifikasi gambar biner.
```
```
Cara Download Dataset di Colab
!pip install kaggle
```
```
Upload file API Kaggle (kaggle.json):
from google.colab import files
files.upload()
```
```
Konfigurasi kredensial Kaggle:
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
```
```
Download dan Ekstrak dataset:
!kaggle datasets download -d ashfakyeafi/cat-dog-images-for-classification
!unzip cat-dog-images-for-classification.zip
```
```
Library Utama yang Digunakan
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Matplotlib
```
