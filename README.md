Saya akan menjelaskan Program dari codingan saya, yang hasil program saya ada Masukan Jumlah Poltek, masukkan nama atlet dari cabang badminton, cabang Basket, Cabang Bola voli


1. Import dan Deklarasi Kelas:

Kode dimulai dengan mengimpor kelas Scanner dari paket java.util, yang digunakan untuk mengambil input dari pengguna.
Kelas utama bernama UAS_DASPRO dideklarasikan.

2. Metode main:

Di dalam metode main, objek Scanner dibuat untuk membaca input dari pengguna.
Variabel jmlPoliteknik diinisialisasi dengan nilai 0.

3. Input Jumlah Politeknik:

Program meminta pengguna untuk memasukkan jumlah politeknik dalam loop while yang terus berjalan hingga input valid diterima.
Jika input adalah integer dan lebih besar dari 0, loop akan berhenti. Jika tidak, program akan memberikan pesan kesalahan dan meminta input ulang.

4. Deklarasi Array:

Sebuah array tiga dimensi atlet dideklarasikan untuk menyimpan nama atlet. Dimensi pertama untuk cabang olahraga, dimensi kedua untuk jumlah politeknik, dan dimensi ketiga untuk jumlah atlet (3 atlet per cabang per politeknik).
Array cabor berisi nama-nama cabang olahraga: "Badminton", "Basket", dan "Bola Voli".

5. Input Nama Atlet:

Program meminta pengguna untuk memasukkan nama atlet untuk setiap cabang olahraga.
Dalam loop bersarang, pengguna diminta untuk memasukkan nama atlet untuk setiap politeknik. Jika nama yang dimasukkan kosong, program akan meminta input ulang untuk atlet tersebut.

6. Menampilkan Informasi Atlet:

Setelah semua nama atlet dimasukkan, program mencetak informasi nama atlet berdasarkan cabang olahraga dan politeknik.
Menggunakan loop bersarang, program menampilkan nama atlet untuk setiap cabang olahraga dan politeknik.

7. Output:

Program menampilkan informasi dengan format yang jelas, memisahkan setiap cabang olahraga dan politeknik.
Secara keseluruhan, kode ini bertujuan untuk mengumpulkan dan menampilkan nama-nama atlet dari berbagai politeknik untuk beberapa cabang olahraga.


