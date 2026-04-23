Sistem E-Klinik Kampus merupakan sebuah sistem berbasis perangkat lunak yang dirancang untuk mengelola proses pendaftaran pasien dalam layanan kesehatan kampus secara terstruktur dan terkontrol. Sistem ini bertujuan untuk memastikan bahwa proses pendaftaran berjalan sesuai dengan kapasitas layanan dokter serta menjaga keteraturan antrian pasien.

Sistem ini melibatkan tiga entitas utama, yaitu Pasien, Dokter, dan Antrian. Pasien berperan sebagai pengguna yang melakukan pendaftaran berobat, dokter berfungsi sebagai penyedia layanan dengan batas kuota harian tertentu, sedangkan antrian digunakan untuk mengatur urutan pelayanan pasien secara sistematis.

Proses utama dalam sistem ini adalah pendaftaran berobat, di mana pasien mengajukan permintaan untuk mendapatkan layanan medis. Sebelum pendaftaran dilakukan, sistem akan melakukan verifikasi terhadap kuota harian dokter. Jika kuota masih tersedia, maka proses pendaftaran dapat dilanjutkan. Sebaliknya, jika kuota telah habis, maka sistem akan menolak pendaftaran pasien.

Apabila pendaftaran berhasil, sistem akan melakukan dua aksi utama secara otomatis, yaitu:

Mengurangi kuota dokter sebagai representasi berkurangnya kapasitas layanan.
Menambahkan nomor antrian pasien secara berurutan sesuai urutan pendaftaran.

Dengan mekanisme ini, sistem mampu menjaga konsistensi antara jumlah pasien yang terdaftar dan kapasitas layanan yang tersedia, sehingga tidak terjadi overbooking.

Selain itu, sistem juga mengimplementasikan prinsip enkapsulasi dalam pengelolaan data. Atribut penting seperti kuota dokter dan nomor antrian tidak dapat diakses atau dimodifikasi secara langsung dari luar kelas, melainkan hanya melalui method yang telah dilengkapi validasi. Hal ini bertujuan untuk menjaga integritas data serta mencegah manipulasi yang tidak sesuai dengan aturan bisnis.

Secara keseluruhan, sistem E-Klinik Kampus dirancang untuk:

Mengelola pendaftaran pasien secara terstruktur
Menjaga keteraturan antrian pelayanan
Mengontrol kapasitas layanan dokter
Mencegah terjadinya pelanggaran aturan sistem

Dengan desain ini, sistem diharapkan mampu meningkatkan efisiensi layanan klinik kampus serta memberikan pengalaman yang lebih tertib dan terorganisir bagi pasien.
