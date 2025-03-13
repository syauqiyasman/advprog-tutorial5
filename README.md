## Before Optimization
### Test Plan 1 (all-student request)
<img width="1155" alt="Screenshot 2025-03-13 at 11 36 16" src="https://github.com/user-attachments/assets/943cdadd-1f33-4c7d-bcaf-02e8c3f8f9ad" />

### Test Plan 2 (all-student-name request)
<img width="1145" alt="Screenshot 2025-03-12 at 20 04 23" src="https://github.com/user-attachments/assets/b32f1571-a42e-4298-95cd-c71b619c4756" />

### Test Plan 3 (highest-gpa request)
<img width="1150" alt="Screenshot 2025-03-12 at 20 07 40" src="https://github.com/user-attachments/assets/922e3c0a-40ab-4b61-8434-73ffcee897e2" />

### Test Plan 1 (all-student request)
<img width="1094" alt="Screenshot 2025-03-13 at 11 31 58" src="https://github.com/user-attachments/assets/5a545873-c648-4924-a565-68d8f8241db0" />

### Test Plan 2 (all-student-name request)
<img width="1109" alt="Screenshot 2025-03-12 at 20 26 30" src="https://github.com/user-attachments/assets/811c25e5-8b0e-4a76-8d8c-98d317281590" />

### Test Plan 3 (highest-gpa request)
<img width="1087" alt="Screenshot 2025-03-12 at 20 25 55" src="https://github.com/user-attachments/assets/a9f0aa80-53cf-4c3d-9dba-6a4846635e9f" />

## After Optimization
### Test Plan 1 (all-student request)
<img width="1147" alt="Screenshot 2025-03-13 at 16 40 42" src="https://github.com/user-attachments/assets/bcd3e6bb-1655-4182-91e2-df5e357a9e2d" />

### Test Plan 2 (all-student-name request)
<img width="1147" alt="Screenshot 2025-03-13 at 16 41 47" src="https://github.com/user-attachments/assets/085bd88f-1d9d-4134-bf33-29d42f29c54b" />

### Test Plan 3 (highest-gpa request)
<img width="1150" alt="Screenshot 2025-03-13 at 16 42 08" src="https://github.com/user-attachments/assets/a154a8b9-4166-4bdc-8a3a-d23e1bae1653" />

### Test Plan 1 (all-student request)
<img width="1099" alt="Screenshot 2025-03-13 at 16 45 38" src="https://github.com/user-attachments/assets/fdce33bc-c49f-48f4-8a14-f60f854ff0de" />

### Test Plan 2 (all-student-name request)
<img width="1099" alt="Screenshot 2025-03-13 at 16 45 55" src="https://github.com/user-attachments/assets/580d7bb1-e35c-413f-bded-b1b4520c33e6" />

### Test Plan 3 (highest-gpa request)
<img width="1123" alt="Screenshot 2025-03-13 at 16 46 13" src="https://github.com/user-attachments/assets/50fb4663-57da-4220-9565-64cab7eb8e6f" />

## Kesimpulan
1. all-student 
- Sebelum dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 80000ms. Setelah dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 3700ms.
- Hal tersebut memberikan speedup sebesar 2100% lebih cepat.

2. all-student-name
- Sebelum dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 1800ms. Setelah dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 80ms.
- Hal tersebut memberikan speedup sebesar 2250% lebih cepat.

3. highest-gpa
- Sebelum dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 75ms. Setelah dilakukan optimisasi, sample time untuk menjalankan request adalah selama kurang-lebih 15ms.
- Hal tersebut memberikan speedup sebesar 500% lebih cepat.

## Reflection
1. Perbedaan Antara Pengujian Kinerja dengan JMeter dan Profiling dengan IntelliJ Profiler \
   JMeter terutama digunakan untuk pengujian kinerja dengan mensimulasikan banyak pengguna dan mengukur respons sistem di bawah beban. Alat ini membantu mengidentifikasi masalah kinerja seperti latensi, throughput, dan pemanfaatan sumber daya dalam kondisi stres. Sementara itu, IntelliJ Profiler digunakan untuk menganalisis proses internal aplikasi, seperti penggunaan CPU, alokasi memori, dan waktu eksekusi metode. JMeter memberikan gambaran luas tentang kinerja sistem, sedangkan IntelliJ Profiler memberikan wawasan lebih mendalam tentang hambatan di tingkat kode.

2. Peran Profiling dalam Mengidentifikasi Kelemahan Aplikasi \
   Profiling memainkan peran penting dalam mengidentifikasi dan memahami titik lemah suatu aplikasi. Dengan menganalisis penggunaan CPU dan konsumsi memori, saya dapat menemukan algoritma yang tidak efisien, operasi yang berlebihan, atau kebocoran memori yang dapat memperlambat kinerja. Alat ini memungkinkan saya untuk melacak pemanggilan fungsi dan waktu eksekusinya, sehingga membantu mengungkap bagian kode yang perlu dioptimalkan.

3. Efektivitas IntelliJ Profiler dalam Mengidentifikasi Bottleneck \
   IntelliJ Profiler terbukti efektif dalam membantu saya menganalisis dan mengidentifikasi hambatan dalam kode aplikasi. Alat ini menyediakan visualisasi mendetail tentang penggunaan CPU dan memori, sehingga memudahkan deteksi jalur kode yang tidak efisien serta operasi yang menghambat kinerja. Kemampuan untuk menganalisis waktu eksekusi metode dan alokasi objek sangat membantu dalam menyempurnakan bagian penting dari aplikasi.

4. Tantangan dalam Pengujian Kinerja dan Profiling \
   Data yang diperoleh dari pengujian kinerja dan profiling bisa sangat kompleks, sehingga memerlukan analisis yang cermat untuk mendapatkan kesimpulan yang bermakna. Untuk mengatasi tantangan ini, saya berusaha untuk mengamati data dengan cermat sehingga mendapat kesimpulan yang tepat.

5. Manfaat Menggunakan IntelliJ Profiler
   - Analisis Mendalam: Memberikan wawasan mendetail tentang eksekusi kode, membantu mengidentifikasi inefisiensi.

   - Pemantauan Waktu Nyata: Memungkinkan saya untuk mengamati perubahan kinerja secara dinamis selama eksekusi.

   - Integrasi dengan IntelliJ IDEA: Integrasi dengan IDE mempercepat proses debugging dan optimalisasi.

6. Menangani Ketidakkonsistenan Antara Profiling dan Pengujian Kinerja \
   Terkadang, hasil dari IntelliJ Profiler tidak sepenuhnya selaras dengan temuan dari pengujian kinerja menggunakan JMeter. Dalam situasi seperti ini, saya melakukan pengecekan silang antara metrik kinerja tingkat sistem dan wawasan pada tingkat kode untuk mengidentifikasi sumber ketidakkonsistenan. Faktor seperti latensi jaringan, kinerja database, atau proses latar belakang dapat berkontribusi terhadap variasi hasil yang tidak terduga.

7. Strategi Optimalisasi Kode Aplikasi
   - Refactoring Kode: Memperbaiki algoritma yang tidak efisien dan mengurangi operasi yang berlebihan.

   - Optimasi Memori: Mengidentifikasi dan memperbaiki kebocoran memori untuk mengurangi konsumsi sumber daya yang berlebihan.

   - Optimasi Query Database: Meningkatkan interaksi dengan database untuk meminimalkan query yang lambat.
     
   Untuk memastikan bahwa perubahan yang saya lakukan tidak berdampak negatif terhadap fungsionalitas aplikasi, saya mengikuti praktik terbaik berikut:

   - Melakukan pengujian menyeluruh setelah perubahan.

   - Menjalankan pengujian kinerja sebelum dan sesudah optimasi untuk mengukur peningkatan.

   - Memantau metrik kinerja dunia nyata setelah implementasi untuk memvalidasi perbaikan.