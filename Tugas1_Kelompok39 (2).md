# Tugas 1 Reinforcement Learning

## 1. Cari dan tuliskan satu contoh/implementasi RL dibidang anda!

Autonomous cars atau mobil tanpa pengemudi.

## 2. Jelaskan secara singkat mengapa aplikasi tersebut merupakan aplikasi berbasis RL dan jelaskan berdasar kesesuaian dengan karakteristik RL
Banyak dari implementasi mobil tanpa pengemudi sudah menggunakan beragam metode reinfocement learning. Ini dikarenakan banyaknya sinyal positif atau negatif saat mengendarai mobil seperti lampu lalu lintas, lampu belok pengendara lain, rambu lalu lintas dan lain-lain yang dapat digunakan untuk memutuskan aksi terbaik dengan menaikan atau menurunkan hadiah (*reward*). Selain itu, reinforcement learning dapat diberikan akses ke komponen mobil seperti roda stir, pedal rem dan gas, dll. Reinforcement learning selanjutnya dapat diberi hadiah jika berhasil mendekati tujuan dan diberi hukuman jika misalnya menabrak, melewati batas kecepatan, melewati lampu merah, dll.




## 3. Dari aplikasi tersebut, tentukan: 
### a. Objective
Reinforcement learning mampu mengendarai mobil hingga tujuan dengan aman tanpa menabrak dan melanggar lalu lintas serta mampu mengidentifikasi aksi kendaraan lain dan pengguna jalan kaki.

### b. State
1. Kecepatan
2. Percepatan sebelumnya
3. Limit kecepatan sekarang
4. Keberadaan objek disekitar mobil (kendaraan, pejalan kaki, rambu lalu lintas, marka jalan, tempat parkir penuh atau tidak, dll)
5. Kecepatan yang akan datang (misalnya melihat rambu speed limit)
6. Jarak antara kendaraan dan rambu kecepatan minimal
7. Visibilitas jalan ( jika hujan dan kaca tertutup air atau gelap)

### c. Action
1. Tekan pedal akselerasi
2. Tekan pedal rem
3. Nyalakan *wiper* (Pembersih kaca)
4. Nyalakan lampu penerangan
5. Nyalakan lampu belok
6. Belokan stir mobil

### d. Reward
Berupa total poin dari beberapa kategori
1. Keselamatan terhadap pengguna jalan, beberapa hal yang dinilai berupa jarak antara kendaraan atau objek lainya, kecepatan mobil terhadap limit kecepatan, jarak dan kecepatan terhadap kendaraan disekitar, visibilitas kaca untuk melihat sekitar, menyalakan lampu penerangan saat gelap atau hujan

2.  Navigasi jalan, identifikasi jalan tercepat 

3. Konsumsi tenaga, kemampuan RL untuk mengatur penggunaan mesin dengan efisien saat bergerak

### e. Termination
1. Sampai ke tujuan
2. Menabrak suatu objek seperti mobil, pejalan kaki, dll.
3. Diambil alih secara manual oleh manusia

## 4. Berdasarkan nomor 3, jelaskan pemahaman anda tentang RL terkait karakteristik, derajat kemudahan/kesulitan untuk diaplikasikan untuk menyelesaikan masalah riil dst.

Reinforcement learning menurut kami mencari cara untuk mencapai tujuan yang dipengaruhi nilai atau rewards yang didapat dari keputusan (actions) yang diambil pada state atau situasi yang ada pada lingkungan. Karakteristik RL antara lain tidak butuhkan pengawasan, mengambil keputusan seiring berubahnya situasi, dan hanya bergantung pada reward value untuk mengetahui baik atau buruk pekerjaan. Untuk pengaplikasian sekarang sudah banyak, tetapi masih perlu mempertimbangkan moralitas untuk pengambilan keputusan. 




