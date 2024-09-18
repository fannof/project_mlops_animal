# project_mlops_animal

Mengembangkan Machine Learning Pipeline untuk Klasifikasi Gambar Hewan Menggunakan Tensorflow Extended

Pipeline TFX terdiri dari beberapa komponen, yang dapat mencakup:

1. ExampleGen: Memuat dataset

2. StatisticsGen: Menghitung statistik untuk dataset

3. SchemaGen: Menghasilkan schema untuk dataset

4. ExampleValidator: Mendeteksi anomali dalam dataset

5. Transform: Melakukan pra-pemrosesan data

6. Trainer: Melatih model menggunakan TensorFlow

7. Evaluator: Mengevaluasi performa model
  
8. Pusher: Mendepoy model ke lingkungan produksi

Tahapan dalam Data Ingestion

 Pada machine learning pipeline, komponen data ingestion akan mengerjakan beberapa tahapan untuk memastikan data yang masuk telah sesuai dan dapat diproses oleh komponen lain. Anda dapat menganggap tahapan ini sebagai proses ETL (extract, transform, load) yang sederhana.

•	Tahapan pengumpulan data (extract)

   Pada tahapan ini, komponen data ingestion akan mengumpulkan data dari berbagai sumber. Sumber data ini bisa bermacam-macam mulai dari database hingga perangkat IoT.

•	Tahapan pengubahan format data (transform)

   Tahapan kedua yang umum dijumpai adalah mengubah format data sesuai dan dapat diproses oleh komponen lain dalam sebuah machine learning pipeline. Ingatlah bahwa pada tahapan ini, kita hanya melakukan pengubahan format suatu data ke dalam format standar.

•	Tahapan memuat data (load)

   Tahap terakhir adalah memuat atau mentransfer data yang telah ditransformasi ke komponen lain yang terdapat dalam machine learning pipeline. Pada tahapan ini sering kali kita menambahkan proses split data untuk membagi data menjadi beberapa kategori, seperti training, evaluation, dan test set.

--Data Schema


