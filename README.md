Judul Percobaan:
Konfigurasi Jaringan Komputer dengan Routing Static Menggunakan Cisco Packet Tracer

Hasil Percobaan:
Pengujian koneksi ICMP antar perangkat telah dilakukan. Hasilnya adalah sebagai berikut:
- PC 1 --> PC 5: Koneksi berhasil, ini menunjukkan bahwa routing antar subnet yang menghubungkan PC 1 dan PC 5 sudah dikonfigurasi dengan baik di router terkait. Tidak ada kendala yang ditemukan dalam pengiriman paket ICMP antara kedua PC ini.
- PC 1 --> PC 7: Koneksi berhasil, ini menunjukkan bahwa routing antar subnet yang menghubungkan PC 1 dan PC 7 sudah dikonfigurasi dengan baik di router terkait. Tidak ada kendala yang ditemukan dalam pengiriman paket ICMP antara kedua PC ini.
- PC 4 --> PC 2: Koneksi berhasil, menunjukkan bahwa routing dari PC 4 ke PC 2 sudah berjalan sesuai rute yang dikonfigurasi. Pengiriman paket ICMP antara PC 4 dan PC 2 berhasil diterima dan dibalas dengan baik.
- PC 4 --> PC 8: Pengujian ini juga berhasil, menandakan bahwa jalur routing dari PC 4 ke PC 8 sudah dikonfigurasi dengan benar pada semua router yang terlibat. Paket data dapat mencapai tujuan tanpa kendala.
- PC 7 --> PC 3: Koneksi ini berhasil, yang berarti jalur routing dari PC 7 ke PC 3 sudah ditetapkan dengan baik. Data dapat dikirimkan antar subnet tanpa masalah.
- PC 7 --> PC 9: Pengujian koneksi ini berhasil, menunjukkan konfigurasi routing antara PC 7 dan PC 9 sudah benar. Paket ICMP berhasil mencapai tujuan dan mendapatkan respons.

Analisis Percobaan:
Hasil pengujian menunjukkan bahwa konfigurasi routing static pada perangkat telah berhasil dilakukan dengan baik. Setiap perangkat yang diuji mampu saling terhubung melalui koneksi ICMP. Hal ini menandakan routing table sudah disetting dengan benar pada setiap router untuk memastikan lalu lintas data antar jaringan dapat berjalan sesuai rute yang telah ditentukan.  Tujuan utama dari percobaan ini adalah untuk memastikan bahwa setiap perangkat dalam jaringan dapat berkomunikasi satu sama lain meskipun berada pada subnet yang berbeda, dengan memanfaatkan routing static.
Pengujian Koneksi ICMP, Pengujian koneksi dilakukan menggunakan ping (ICMP Echo Request) untuk memverifikasi bahwa perangkat dapat saling berkomunikasi. Hasil pengujian ini menunjukkan bahwa koneksi antara PC-PC yang berada di subnet berbeda berjalan dengan baik. 

Kesimpulan Percobaan:
Pada percobaan ini, konfigurasi routing static berhasil diterapkan untuk menghubungkan beberapa subnet yang berisi perangkat-perangkat komputer. Pengujian koneksi antar perangkat melalui ICMP (ping) membuktikan bahwa konfigurasi routing static telah berfungsi dengan baik. Semua perangkat yang diuji, termasuk PC 1, PC 2, PC 3, PC 4, PC 5, PC 6, PC 7, PC 8, dan PC 9, dapat saling berkomunikasi tanpa mengalami masalah.
