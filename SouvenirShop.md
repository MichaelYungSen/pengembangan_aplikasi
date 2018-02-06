Souvenir Shop
Contoh user requirements untuk sebuah usaha  Souvenir Shop
Identifikasi stakeholder
	1	Pemilik Toko
	2	Karyawan Toko, terdiri dari:
		o	kasir
		o	staff managemen
		o	satpam
		o	cleaning service
	3	Pelanggan
Identifikasi tujuan proyek
	Membangun aplikasi Point of Sale (POS) untuk digunakan pada Souvenir Shop. Aplikasi POS ini nantinya menjadi alat pencatatan transaksi dan sebagai acuan dalam akuntibilitas operasional Souvenir Shop.
Functional Requirement
	Fitur-fitur yang harus diimplementasikan pada aplikasi POS ini adalah:
	1.	Menerima orderan pelanggan dan mencatat transaksi pembayaran.
	2.	Mencetak faktur order dan pembayaran
	3.	Menampilkan catatan jumlah uang pada cash register
	Setiap transaksi harus mencantumkan nama staff yang menerima orderan dan memproses pembayaran.
Flow proses bisnis
	1.	Pelanggan datang ke souvenir Shop dan melakukan pemesanan terhadap staff di-counter.
	2.	Staff menginput pemesanan ke sistem dan kemudian mencetak faktur order dan pembayaran.
	3.	Pelanggan membayar pesanan dan staff memberikan uang kembalian (jika ada)
	4.	Pelanggan memilih product yang ada
	5.	Pelanggan membayar product yang inginkan
	6.	Pelanggan meninggalkan restoran.
Non-Functional Requirements
	Aplikasi yang dikembangkan harus dapat digunakan dengan touch screen secara optimal.
Design solusi
Needs
	1.	Aplikasi Point of Sales (POS)
		o	identifikasi staff (berarti ada sistem login/logout)
		o	input order
		o	cetak faktur order/pembayaran
		o	Laporan tansaksi
	2.	Catatan jumlah uang pada cash register
		o	Deposit (menambah uang ke cash register bukan melalui proses pembayaran)
		o	Withdrawal (mengambil uang dari cash register)
		o	Pergantian staff (cetak tanda serah terima)
		o	Laporan jumlah uang beserta transaksi
Features
	1.	Aplikasi Point of Sales (POS)
		o	User management
			Untuk login/logout dan identifikasi staff yang melakukan transaksi.
		Fungsi untuk manajemen:
			-Menambahkan user baru
			-Menghapus/disable user (user tidak dapat login)
			-Mengganti password user (reset password)
		o	Product management
			Untuk daftar produk yang dijual dan bisa diorder.
			-Menambahkan product baru
			-Mengupdate informasi product
			-Mengubah spesifikasi product
			-Menghapus/mengnontaktifkan product
		o	Order and Payment
			Menerima orderan dan menerima pembayaran.
			-Menerima pemesanan dari pelanggan
			-Menerima pembayaran dari pelanggan
		o	Report
	Menampilkan daftar transaksi yang terjadi.
	2.	Catatan jumlah uang pada Cash Register
		o	User management
			Untuk login/logout dan identifikasi staff yang melakukan transaksi.
		o	Cash out/in
			Untuk melakukan deposit atau withdrawal dari cash register yang tidak berkaitan dengan transaksi penjualan.
		o	Ganti shift
			Proses pergantian staff kasir.
		o	Report
			Menampilkan jumlah uang dan transaksi.
			Dokumen use case lihat di Use Case Diagram.
