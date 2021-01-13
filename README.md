# Aplikasi KumbahKU UAS Pemmob

Nama Kelompok :
1. Muhamad Fikri Rizki Romadhoni (18051204060)
2. M. Adharis Adlani (18051204072)
3. Hanif Afrizal (18051204044)

Kelas TI2018B
Prodi Teknik Informatika
Universitas Negeri Surabaya 

Aplikasi berjalan berdasarkan pengambilan data yang disediakan oleh server MySql.

Persiapan :
Koneksi lokal -> bisa pakai Hotspost Smartphone lalu set IP komputer server
		menjadi 192.168.43.59 , pastikan ip Smartphone juga berada
		pada subnet jaringan yang sama.

Komputer Server -> persiapkan laptop/komputer yang menjadi server dan terhubung
		dengan Smartphone lewat jaringan lokal.

Software Xampp -> Software Bundle untuk menjalankan layanan server database dan
		Apache. pastikan service Apache dan Mysql dalam status Running.
		Bisa perlu jalankan service Filezilla untuk transfer file.

Database -> akses alamat http://localhost/phpmyadmin/  setelah itu buat database
		dengan nama "dblaundry". setelah database jadi, pilih menu import,
		lalu browse file dblaundry.sql yang tedapat pada paket rar arsip
		ini. jika file sudah terpilih lalu pilih "Go" untuk mengeksport
		data-data pada database.

Setting Database -> untuk database menggunakan setting 
			host = "localhost"
			user = "root"
			pass = ""
			db   = "dblaundry"   -> yaitu database target.

File Resource -> karena untuk menghubungkan aplikasi dengan server membutuhkan
		perantara PHP dan file foto yang tersimpan pada folder server,
		maka copy / cut folder bernama "laundry" kedalam root hosting
		xampp (biasanya ada di "C:/xampp/htdocs/). taruh folder resource
		itu kedalam folder htdocs (bisa berbeda).

Untuk Source Code -> terdapat file project pada folder "CRUD_MySql". didalamnya
		dapat dibuka aplikasinya (debug).

Aplikasi jadi -> Untuk Aplikasi Jadi (Release) Bisa Langsung diinstal pada Smartphone yang
		bernama "KumbahKU_UAS_Pemmob_44_60_72_TI2018B"

File Database & php -> dikompress dalam format rar bernama server web
