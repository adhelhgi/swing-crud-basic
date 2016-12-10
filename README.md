# swing-crud-basic
Dasar pemrograman Aplikasi Java Desktop dengan Swing di Netbeans

learning source
https://www.codepolitan.com/tutorial/aplikasi-crud-java-sederhana-menggunakan-database-mysql

cek nama database dari class koneksi.

table
CREATE TABLE `karyawan` (
  `id_karyawan` int(11) NOT NULL,
  `nama_karyawan` varchar(50) DEFAULT NULL,
  `nik` varchar(20) DEFAULT NULL,
  `jabatan` varchar(20) DEFAULT NULL,
  `no_telphone` varchar(20) DEFAULT NULL,
  `alamat` varchar(100) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
