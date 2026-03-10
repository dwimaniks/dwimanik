# dwimanik
Tugas1
1. Penjelasan Array

<img width="546" height="127" alt="image" src="https://github.com/user-attachments/assets/47fad409-2f94-4612-84fa-248fadb5f291" />

nilai_mahasiswa = []
Membuat list (array) kosong untuk menyimpan nilai mahasiswa.

for i in range(10):
Perulangan untuk memasukkan 10 nilai.

input()
Digunakan untuk menerima nilai dari pengguna.

int()
Mengubah input dari string menjadi bilangan bulat.

append(n)
Menambahkan nilai n ke dalam array nilai_mahasiswa.

<img width="471" height="102" alt="image" src="https://github.com/user-attachments/assets/42355dd3-cd13-431a-9d59-ce3bf1d65e6e" />

nilai_mahasiswa → menampilkan seluruh data nilai dalam list.

max(nilai_mahasiswa) → mencari nilai tertinggi dalam array.

min(nilai_mahasiswa) → mencari nilai terendah dalam array.

<img width="642" height="55" alt="image" src="https://github.com/user-attachments/assets/2011eb7b-7d59-4870-ab00-6b3c14e500e7" />

sum(nilai_mahasiswa) → menjumlahkan semua nilai dalam list.

len(nilai_mahasiswa) → menghitung jumlah data nilai.

sum(...) / len(...) → menghasilkan nilai rata-rata.

<img width="417" height="270" alt="image" src="https://github.com/user-attachments/assets/8bd62ff3-c411-4eec-bf57-f896e8c93277" />

lulus = 0 → variabel untuk menghitung jumlah siswa yang lulus.

tidak_lulus = 0 → variabel untuk menghitung jumlah siswa yang tidak lulus.

for n in nilai_mahasiswa: → mengecek setiap nilai dalam array.

if n >= 60: → jika nilai 60 atau lebih, siswa lulus.

else: → jika nilai kurang dari 60, siswa tidak lulus.

lulus += 1 dan tidak_lulus += 1 → menambah jumlah sesuai kondisi.

<img width="461" height="286" alt="image" src="https://github.com/user-attachments/assets/bf6ab1f1-bafd-4f36-af65-563736b9cf6b" />

import matplotlib.pyplot as plt
Mengimpor library matplotlib untuk membuat grafik.

plt.figure()
Membuat area grafik baru.

kategori = ["Lulus", "Tidak Lulus"]
Menentukan label kategori pada sumbu X.

data = [lulus, tidak_lulus]
Data yang akan ditampilkan pada grafik.

plt.bar(kategori, data)
Membuat grafik batang (bar chart).

plt.title()
Memberi judul grafik.

plt.ylabel()
Memberi label sumbu Y.

plt.ylim(0, 10)
Mengatur batas nilai sumbu Y dari 0 sampai 10.

plt.show()
Menampilkan grafik ke layar.

<img width="592" height="176" alt="image" src="https://github.com/user-attachments/assets/0a1dc327-23c1-4a2d-9365-65b1fe5d08f2" />

Input 10 nilai → O(1)
Karena jumlah input selalu tetap (10).

Mencari nilai tertinggi dan terendah → O(n)
Program harus memeriksa semua elemen dalam array.

Menghitung rata-rata → O(n)
Fungsi sum() menjumlahkan seluruh elemen.

Menghitung jumlah lulus → O(n)
Menggunakan perulangan untuk mengecek setiap nilai.

Membuat grafik → O(1)
Karena jumlah data yang ditampilkan kecil dan tetap.

2. Tangkapan Layar Hasil
   
   <img width="357" height="225" alt="image" src="https://github.com/user-attachments/assets/b0ffb015-4fc7-40c2-95d3-3b06313be492" />
   
<img width="563" height="71" alt="image" src="https://github.com/user-attachments/assets/a969baa6-29ef-4d7d-9795-f8708988004b" />

<img width="213" height="41" alt="image" src="https://github.com/user-attachments/assets/1161fe46-788c-4244-b05b-5c2625520d29" />

<img width="233" height="65" alt="image" src="https://github.com/user-attachments/assets/16dae930-700e-4efb-9e63-1d925f585676" />

<img width="726" height="555" alt="image" src="https://github.com/user-attachments/assets/a25efd9c-82a6-4f95-9808-78136b0cdd90" />

<img width="713" height="552" alt="image" src="https://github.com/user-attachments/assets/a2b190a3-0fa5-487e-84e8-bffa35e0a45d" />

3. Analisis

Program ini digunakan untuk mengolah data nilai mahasiswa menggunakan array (list) pada Python. Program meminta pengguna memasukkan 10 nilai yang kemudian disimpan dalam list nilai_mahasiswa.

Setelah data dimasukkan, program melakukan beberapa proses yaitu mencari nilai tertinggi, nilai terendah, dan rata-rata. Program juga menghitung jumlah mahasiswa yang lulus (≥ 60) dan tidak lulus menggunakan perulangan dan percabangan.

Selain itu, program menampilkan grafik batang menggunakan library matplotlib untuk menggambarkan data kelulusan mahasiswa. Secara keseluruhan, program ini menunjukkan penggunaan array untuk menyimpan, mengolah, dan menampilkan data secara sederhana.

4. Refleksi Pembelajaran

Dalam pembelajaran struktur data **array (list) pada Python**, saya belajar menyimpan dan mengolah beberapa data dalam satu variabel. Melalui latihan ini, saya dapat mencari **nilai tertinggi, terendah, dan rata-rata** dari data yang dimasuk.
Saya juga memahami penggunaan perulangan (for) dan percabangan (if-else) untuk menentukan jumlah siswa yang lulus dan tidak lulus. Selain itu, saya belajar membuat grafik menggunakan matplotlib agar data lebih mudah dipahami.