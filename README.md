# Klasifikasi Gender 

### 1. Background 
Pada klasifikasi gambar untuk mengidentifikasi jenis kelamin, sistem menggunakan algoritma pembelajaran mesin untuk membedakan gambar wajah laki-laki dan perempuan. Model ini memproses gambar, mengekstraksi fitur penting seperti bentuk wajah, tekstur kulit, dan atribut visual lainnya. Tujuannya adalah untuk mengkategorikan gambar ke dalam dua kelas: Male atau Female. Pendekatan ini sering digunakan dalam berbagai aplikasi, seperti pengenalan wajah, analisis demografi, dan sistem keamanan berbasis biometrik.

### 2. Dataset
![{8A1CDD88-0218-49EA-BCC5-CF85837A745C}](https://github.com/user-attachments/assets/5542ec55-7eeb-4282-ba40-87a083691332)

a. Dataset CelebA dari Kaggle, yang berisi atribut visual dari wajah, termasuk label jenis kelamin.

b. Ukuran dataset: 20.000 gambar label male dan female

### 3. Preprocessing Data

 a. Hapus data duplikat
 
 b. Balancing Data

 c. Augmentasi

### 4. Training Model
a. Hyperparameter

Adam optimizer, loss function: Sparse Categorical Crossentropy.

b. Training Model

Epoch : 10, Learning Rate : 0,00001
