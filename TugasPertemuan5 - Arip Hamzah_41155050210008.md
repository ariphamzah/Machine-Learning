Classification dengna K-NEAREST Neighbours 
1.	Persiapan sample dataset 
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture1.png)

2.	Visualisasi dataset 

   ![Deskripsi Gambar](images/gambar_tugas5/Picture2.png)

3.	Pengantar classification dengan K-Nearst Neighbours | KNN 
Model ini akan melakukan prediksi, dalam hal ini akan melakukan prediksi Gender/ jenis kelamin berdasarkan kemiripan karakteristik atau picturs berdasarkan dataset yang kita miliki
4.	Preprocessing dataset dengan Label Binarizer

  ![Deskripsi Gambar](images/gambar_tugas5/Picture3.png)

  ![Deskripsi Gambar](images/gambar_tugas5/Picture4.png)

5.	Training KNN Classification Model
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture5.png)

6.	Prediksi dengan KNN Classification Model
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture6.png)

7.	Visualisasi Nearest Neighbours
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture7.png)
 

8.	Kalkulasi jarak dengan Euclidean Distance
   
   ![Deskripsi Gambar](images/gambar_tugas5/Picture8.png)
   
   ![Deskripsi Gambar](images/gambar_tugas5/Picture9.png)

9.	Evaluasi KNN Classification Model | Persiapan testing set
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture10.png)

10.	Evaluasi model dengan accuracy score
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture11.png)

11.	Evaluasi model dengan precision score
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture12.png)

12.	Evaluasi model dengan recall score
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture13.png)

13.	Evaluasi model dengan F1 score
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture14.png)

14.	Evaluasi model dengan classification report
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture15.png)

15.	Evaluasi model dengan Mathews Correlation Coefficient
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture16.png)
 

Classification dengan Support Vector Machine – SVM 

1.	Pengenalan Decision Boundary & Hyperplane
  
  ![Deskripsi Gambar](images/gambar_tugas5/Picture17.png)

Decision Boundary adalah garis atau permukaan dalam ruang fitur yang memisahkan kelas-kelas yang berbeda dalam suatu dataset. Pada klasifikasi biner, decision boundary adalah batas yang membedakan antara dua kelas.
Hyperplane adalah konsep yang digunakan dalam Support Vector Machine (SVM). Dalam ruang 2D, hyperplane adalah garis; dalam ruang 3D, itu adalah bidang; dan dalam dimensi lebih tinggi, ini adalah batas yang memisahkan kelas. Hyperplane dipilih sedemikian rupa sehingga memaksimalkan margin antara dua kelas, membantu menghindari overfitting pada data training.

2.	Pengenalan Support Vector & Maximum Margin

  ![Deskripsi Gambar](images/gambar_tugas5/Picture18.png)

Support Vectors adalah titik data dalam dataset yang paling dekat dengan hyperplane. Dalam SVM, support vectors adalah elemen penting karena mereka menentukan posisi hyperplane. Perubahan pada support vector akan mengubah posisi hyperplane.
Maximum Margin adalah jarak terbesar antara hyperplane dan titik data terdekat dari kedua kelas. SVM bertujuan untuk menemukan hyperplane dengan margin maksimal agar model lebih general dan memiliki daya prediksi yang baik untuk data baru.



3.	Pengenalan kondisi Linearly Inseparable dan Kernel Tricks

   ![Deskripsi Gambar](images/gambar_tugas5/Picture19.png)

Linearly Inseparable terjadi ketika data tidak dapat dipisahkan oleh garis lurus atau hyperplane dalam ruang fitur aslinya. Misalnya, dalam kasus data yang berbentuk lingkaran, garis lurus tidak dapat memisahkan kelas dengan benar.
Kernel Trick adalah teknik yang digunakan SVM untuk menangani data yang tidak dapat dipisahkan secara linear. Dengan kernel, data dapat dipetakan ke dalam dimensi yang lebih tinggi, sehingga menjadi lebih mudah untuk memisahkan kelas dengan hyperplane. Beberapa kernel umum adalah kernel polinomial, RBF (Radial Basis Function), dan sigmoid.

4.	Pengenalan MNIST Handwritten Digits Dataset

   ![Deskripsi Gambar](images/gambar_tugas5/Picture20.png)
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture21.png)

5.	Klasifikasi dengan Support Vector Classifier | SVC

   ![Deskripsi Gambar](images/gambar_tugas5/Picture22.png)

6.	Hyperparameter Tuning dengan Grid Search
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture23.png)

7.	Evaluasi Model
 
   ![Deskripsi Gambar](images/gambar_tugas5/Picture24.png)

  
