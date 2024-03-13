# Reflection 5

## 1.
| Performance Testing with JMeter                                                                                                                                                                                                                   | Profiling with IntelliJ Profiler                                                          |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Digunakan untuk testing performance dari web applications. Metode ini dilakukan dengan mengsimulasikan sebuah skenario di mana multiple users mengkases aplikasi secara bersamaan untuk melihat bagaimana perilaku aplikasi ketika diberi tekanan. | Digunakan untuk melakukan profiling pada Java applications                                |
| Metrics yang diukur adalah response time, throughput, error rate. | Metrics yang diukur adalah application's runtime behaviour, CPU time per method, memory allocations, thread activity, garbage collection events |
| Performance testing biasanya dilakukan saat pre-production atau staging environment untuk memastikan aplikasi memenuhi kriteria performa sebelum lanjut ke tahap production |  Profiling biasanya dilakukan pada development phase atau ketika melakukan troubleshooting|

## 2.
Profiling membantu pengguna untuk mengidentifikasi bagian program mana yang menghambat kinerja aplikasi sehingga pengguna 
hanya perlu mengoptimasi bagian tersebut agar dapat meningkatkan performa aplikasi.

## 3. 
Ya. Dengan menggunakan IntelliJ profiler, saya dapat mengetahui method mana yang paling memakan performa aplikasi. Dengan
mengetahui informasi tersebut, saya dapat memperbaiki methodnya untuk menjadi lebih efisien dan meningkatkan performa aplikasi

## 4.
Saya masih merasa kesulitan dalam membaca output dari performance testing dan profiling yang dilakukan. Kedepannya saya akan
mencoba untuk mempelajari lebih dalam tentang cara membacanya agar dapat memperoleh informasi mengenai hal apa yang harus saya
lakukan untuk meningkatkan performa aplikasi saya.

## 5.
Profiling dengan IntelliJ Profiler dapat membantu saya mengidentifikasi bottleneck dari aplikasi saya. Informasi mengenai
hal itu akan bermanfaat dalam meningkatkan performa aplikasi saya dengan mengoptimisasi bottleneck yang telah teridentifikasi.

## 6. 
Bila terjadi inkonsistensi antara IntelliJ profiler dan JMeter performance testing, dari pencarian online, hal yang bisa
saya lakukan salah satunya adalah re-evaluasi test conditions. Saya perlu memastikan bahwa keduanya menggunakan tools yang
mirip. Hal lain yang dapat dilakukan misalnya mencari permasalahan yang merupakan bawaan dari environment, analyze garbage collection,
check for concurrency issues, dan lain-lain.

## 7. 
Saya melihat waktu dari durasi yang diperlukan untuk memenuhi request dengan JMeter. Jika waktu terlalu lama, maka perlu
dilakukan optimisasi bottleneck untuk meningkatkan performa aplikasi. Setelah melakukan optimisasi, maka lakukan lagi 
performance testing dan bandingkan durasi sekarang dengan durasi sebelumnya. Apabila durasi lebih cepat, maka performa meningkat.
