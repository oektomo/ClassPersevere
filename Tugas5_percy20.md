# TUGAS SESI PAGI

## Python OOP

## 1. Apa itu OOP dan cobalah buat 2 implementasi konsep OOP menggunakan Python!

### OOP

OOP atau Object Oriented Programming merupakan cara dalam * programming * yang menerapkan konsep kelas dan objek agar program yang dibuat menjadi sederhana, dapat di gunakan ulang dan dapat digunakan untuk membuat beberapa objek yang sama.

### Inherintence
Kemampuan bagi suatu kelas untuk menurunkan atribut dan fungsi yang ada ke kelas lain.

' 
class Mahasiswa:

	def  __init__(self, name, nim):

		self.name=name

		self.nim= nim

	def  desc(self):

	return  f"Name: {self.name}, NIM:{self.nim}"

  

	class  Anggota(Mahasiswa):

		pass

	obj= Anggota("Budi",  18346)

	obj.desc()'

Output:
Name: Budi, NIM:18346



### Polymorphism

Polymorphism merupakan kemampuan sebuah data, fungsi atau objek yang mampu memiliki bentuk berbeda-beda. Contohnya fungsi yang sama tetapi memiliki penggunaan yang berbeda.

class Human:

	def  speak(self):

		print("hello")

  

class Dog: 

	def  speak(self):

		print("woof")
		
		
Output:
	hello
	woof

## 2. Sebut dan jelaskan 2 jenis modules yang ada di Python
- Built in modules
Modul-modul standar bawaan dari Python. Contohnya:
os, sys, random, dll.

- User-defined modules
Fungsi atau modul yang dibuat sendiri oleh seorang individu. Contohnya:

	`def print(x):
		print("Hello World")`
	
		

## 3. Hitunglah berapa hasil dari √175 + 4√7 + (1/3) + ³log 81 menggunakan module math!
 

    import math as m
	m.sqrt(175)+ 4*m.sqrt(7)+ 1/3 + m.log(81,3)

Output:
28.145095132914648

## 4. Apa itu custom exception handling dan berikan 1 contoh implementasinya!

 *Custom exception* handling merupakan cara di Python supaya program kita tidak dipaksa mengembalikan *error* jika ada yang salah.
Contoh:

    def  numChecker(x):

    if x//2==0:
    
    print('odd')
    
    else:
    
    raise Exception("Even
    
    numChecker(3)

Output:
  

     ---------------------------------------------------------------------------
    
    Exception Traceback (most recent call last)
    
    [<ipython-input-54-58f4e85cc122>](https://localhost:8080/#) in <module>()  6  raise  Exception("Even")  7   ----> 8  numChecker(3)  
    
    [<ipython-input-54-58f4e85cc122>](https://localhost:8080/#) in numChecker(x)  4   5  else:  ----> 6  raise  Exception("Even")  7   8  numChecker(3)  
    
    Exception: Even



## Artificial Intelligence

## 1. Apa perbedaan structured & unstructured data dan sebutkan 3 sumber data!

 
|Structured|Unstructured  |
|--|--|
|Data disimpan dengan model atau struktur yang telah dibuat terlebih dahulu| Bentuk format berbeda dari data terstruktur  | 
|Bentuk data quantitatif|Bentuk data qualitatif |
|Data tersimpan dalam baris dan kolom| Data tersimpan dalam file audio, text, vidio dan no SQL database |

3 Contoh sumber data:
 1. *Log Website*
 2. Sensor
 3. Aktivitas pengguna sosial media

## 2. Perbedaan AI, ML dan DL

| Artificial Intelligence      | Machine Learning| Deep Learning     |
| :---        |    :----:   |          ---: |
| Segala metode yang memberi kemampuan mesin / komputer untuk melakukukan kemampuan seperti manusia dengan mengimplementasikan aturan-aturan      | Implementasi teknik AI yang menggunakan metode statistik agar mesin dapat mempelajari data dan beradaptasi dari data      | Implementasi *neural network* buatan untuk dilatih dengan data yang besar agar dapat belajar dan beradaptasi |


## 3. Beda Machine Learning dan *Software* tradisional

|Machine Learning|*Software* Tradisional  |
|--|--|
| Tujuanya memperbaiki metric dari model (akurasi, presisi, dll) yang dapat memberi hasil lebih berguna | Tujuanya memenuhi kebutuhan fungsional dan non-fungsional  |
|Komputer menerima data input dan hasil dari input dan mengembalikan model atau program setelah diproses dengan metode *machine learning* tertentu	| Menggunakan rumus atau aturan yang disediakan untuk mengembalikan hasil|

## 4. Contoh Aplikasi *Machine Learning* di bidang *Smart City* dan Agrikultur

|*Smart City*| Agrikultur  |
|--|--|
| Pendeteksi Parkiran Kosong | Pendeteksi hama atau penyakit tumbuhan  |
| Pendeteksi Pelanggaran Lalu Lintas| Prediksi jumlah panen|
| Otomasi transportasi umum mulai dari otomasi pengemudi, jalur dan penjadwalan| Otomasi pekerjaan seperti penanaman bibit, *maintanance* dan panen dengan drone / robot|


## Maths for AI

## 1. Mengapa ilmu matematika penting ketika mempelajari AI?

Matematika merupakan inti dari AI. Secara garis besar, implementasi AI melibatkan banyak konsep dari statistika / probabilitas seperti distribusi, aljabar seperti matrix, eigenvektor, dan kalkulus seperti turunan, dll. Konsep-konsep ini telah digabungkan dan seperti tujuanya, untuk mencari pola dalam data.


## 2. Jelaskan perbedaan vektor dan skalar!
|Vektor|Skalar  |
|--|--|
|Vektor merupakan besaran tetapi tidak memilik arah  |Skalar merupakan besaran yang memiliki arah|
|Contoh: Panjang, berat, suhu, dll	|Contoh: Momentum, kecepatan, gaya, dll	|



## 3. Apa perbedaan dari Jarak Euclidean dan Manhattan?

| Euclidean | Manhattan  |
|--|--|
| Menghitung jarak berdasarkan perbedaan a**kar kuadrat** antara koordinat objek (Berdasarkan teorema pitagoras) | Menghitung jarak berdasarkan perbedaan **absolut** antara koordinat objek  |
| Euclidean lebih cocok digunakan untuk menghitung jarak antara data numerik yang berbeda | Manhattan lebih cocok untuk menghitung data yang berbentuk vektor	|


## 4. Apa kegunaan matriks dalam ilmu matematika ketika menerapkan AI?
Matriks merupakan salah satu konsep yang digunakan dalam *neural network*. Matriks diimplementasikan sebagai wadah untuk menghitung jumlah besaran koneksi antara neuron. 

## *Machine Learning*

## 1. Beda *supervised* dan *unsupervised learning*

|Supervised Learning|Unsupervised Learning  |
|--|--|
|Di latih dengan data yang terlabel|Di latih dengan data yang tidak terlabel|
|Menerima *feedback* untuk mengetahui hasil prediksi salah atau benar	| Tidak menerima *feedback*	|
|Data *input* di berikan kepada model dan *output*	|Data *input* hanya di berikan ke model	|
| Contoh: *Linear regression*, *Support Vector Machine*	| Contoh: *Clustering,  K-Nearest Neighbors* 	|



## 2. Tahap dalam *machine learning lifecycle*
### 1. Pengumpulan Data:
Pengumpulan data dari beberapa sumber seperti database, *web scrapping*

### 2. Mempersiapkan Data:
Melibatkan proses seperti eksplorasi data. Eksplorasi data dapat membantu kita untuk melihat sifat dari data dan kualitasnya. 

### 3. Membersihkan dan memperbaiki data
Di tahap ini, data dibersihkan dan diubah ke format yang dapat kita gunakan. Membersihkan data dapat berupa, menambah atau mengurangi data yang hilang, data duplikat dan mengurangi *noise*.

### 4. Melakukan data analisis
Melibatkan pemilihan model yang cocok untuk data kita seperti klasifikasi, regresi, *clustering*, dll.

### 5. Melatih model
Data yang telah dipersiapkan digunakan untuk melatih model agar model dapat memahami pola, fitur, dll.

### 6. *Model Testing*
Melihat akurasi dari model dengan parameter seperti *F1 Score*.

### 7. *Deployment*
Model yang kita buat dapat di-*deploy* setelah memenuhi kriteria yang kita inginkan dan berharap model dapat berkembang lebih jauh.


## 3. Beda *regression* dan *clustering*
|Regression|Clustering  |
|--|--|
| Bertujuan menjelaskan atau menebak sesuatu berdasarkan data sebelumnya atau historis | Bertujuan mengelompokan data berdasarkan karakteristik fitur-fitur |
| Supervised Learning	| Unsupervised Learning	|
|Regresi perlu memisah data antara data *training* dan *test*	| *Clustering* tidak butuh	|
|Butuh data yang terlabel|Melibatkan pengelompokan data|




## 4. Algoritma *neural network* dan fungsinya

*Neural network* merupakan kelompok algoritma yang mencari hubungan tersirat dalam data yang menyerupai cara kerja otak manusia. *Neural network* membantu merubah *input* agar jaringan dapat memberi hasil yang optimal tanpa merubah alur.

*Neural network* telah digunakan dalam beragam bidang seperti analisis data, *speech to text*, pendeteksi wajah, hingga memainkan *video game*.
