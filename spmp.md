<h1 align="center" id="software-requirements-specification">DOCUMENTASI PROYEK RPL
SOFTWARE PROJECT MANAGEMENT PLAN
APLIKASI UJIAN ONLINE DI SMAN 1 JATIBARANG
BERBASIS WEBSITE (ULine)</H1>
<p align="center"><strong>Diajukan untuk memenuhi persyaratan pada mata kuliah Rekayasa Perangkat Lunak pada jenjang Diploma III</strong></p><br><br>


</p><p align="center">  
<img src="https://lh3.googleusercontent.com/qEHYPVzo0kjd8ikhrCIF4cI_PhR8pmK5vDU14oEp9OPyVT-eA54cVp8C9iyJ8rKDfH8OR1dnT1zv=s300" alt="enter image description here" title="logo"><br>  

 
</p><p align="center"><strong>Disusun Oleh Kelompok 4 :</strong></p> 
<p align="center"> 
<ol>
	<li>Devia Suci Khoirun Nissa	(1703076)</li>
	<li>Kastuti						(1703062)</li>
	<li>Reza Pahlevi Yahya			(1703069)</li>
</ol>
<p>D3TI.2C</p>
</p>



<h1><p align="center"><strong>PROGRAM STUDI TEKNIK INFORMATIKA</p></h1>
<h1 align="center">POLITEKNIK NEGERI INDRAMAYU</h1>
<h1 align="center">2019</h1>
</strong></p>

<b>
<h1>
<i>Software Project Management Plan (SPMP)</i>
</h1>

<ol>
	<li>Pendahuluan</li>
		<ol>
			 1.1 Gambaran Proyek<br>
			 1.2 Dokumen-dokumen<br> 
			 1.3 Evolusi SPMP<br>
			 1.4 Material acuan<br>
			 1.5 Definisi dan akronim (singkatan)<br>
		</ol>
	<li>Organisasi Proyek</li>
		<ol>
			2.1 Model proses<br>
			2.2 Struktur organisasi<br>
			2.3 Batasan dan antarmuka organisasi<br>
			2.4 Lingkup tanggung jawab<br>
		</ol>
	<li> Proses Manajerial</li>
		<ol>
			3.1 Tujuan dan Prioritas Management<br>
			3.2 Asumsi-asumsi,Ketergantungan/Keterkaitan, dan Batasan-batasan<br>
			3.3 Management Resiko<br>
			3.4 Mekanisme Monitoring<br>
			3.5 Perencanaan Staff<br>
		</ol>
	<li> Proses Teknis</li>
		<ol>
			4.1 Moteda, tool, dan tekniks<br>
			4.2 Dokumentasi perangkat lunak<br>
			4.3 Fungsi-fungsi pendukung proyek<br>
		</ol>
	<li> Paket Pekerjaan,Jadwal dan Budget</li>
		<ol>
			5.1 Paket Pekerjaan<br>
			5.2 Ketergantungan / Keterkaitan<br>
			5.3 Kebutuhan - Kebutuhan Sumber Daya<br>
			5.4 Alokasi Budjet dan Sumber Daya<br>
			5.5 Jadwal<br>
		</ol>
</ol>
</b>

<ol>
	<b>
	<li>Pendahuluan</li>
	</b>
		<ol>
			 1.1 Gambaran Proyek<br>
			 <ol> Proyek yang sedang kami buat adalah sistem ujian online. Ketika penulis melakukan penelitian terhadap sistem pelaksanaan ujian tengah semester dan ujian akhir semester di SMAN 1 Jatibarang, penulis mendapati bahwa pelaksanaan ujian tersebut masih dilakukan secara manual. Hanya ujian sekolah dan ujian nasional saja yang dilakukan secara komputerisasi, sedangkan di beberapa sekolah menengah atas lainnya di kabupaten Indramayu sudah menerapkan pelaksanaan ujian tengah semester dan ujian akhir semester serta ujian-ujian lainnya secara komputerisasi. Dari hal tersebut penulis berinisiatif membuat Aplikasi Ujian Online di SMAN 1 Jatibarang Berbasis Website.
			 Aplikasi ini dibuat guna membantu ujian-ujian SMAN 1 Jatibarang yang masih manual menajadi secara komputerisasi dengan harapan para siswa mempunyai pembelajaran dan pengalaman mengerjakan ujian secara komputerisasi sehingga tidak merasa kesulitan ketika mengerjakan ujian sekolah dan ujian nasional yang memang sistemnya terlaksana secara komputerisasi. 
			 Perangkat lunak pendukung yang digunakan adalah Corel-Draw X7, Adobe Photoshop CS4, Xampp, Sublime Text 3, MYSQL, dan Framework Laravel sebagai pembangun serta dokumentasi program dan laporan. Dengan adanya aplikasi berbasis Website ini, yang sudah terkoneksi dengan database, tentunya akan mempermudah pengolahan data ujian serta pelaksanaannya.<br></ol>
			 1.2 Dokumen-dokumen<br>
			  <ol> Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai project kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi proposal, software project management plan, software requrements specifications, software design document yang berkaitan dengan pembuatan projek kami.<br></ol>
			  1.3 Evolusi SPMP<br>
			   <ol> Pembuatan dokumen ini bersifat pribadi, jadi hanya pihak yang bersangkutan saja yang boleh untuk memanfaatkan dokumen ini untuk hal-hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjual belikan dokumen ini secara ilegal, atapun mengubah dokumen tanpa izin dan dasar yang jelas.  <br></ol>
			 1.4 Material acuan<br>
			 <ol> Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar IEEE untuk membentuk model yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas. 
			IEEE adalah sebuah organisasi profesi nirlaba yang terdiri dari banyak ahli dibidang teknik yang mempromosikan pengembangan standar-standar dan bertindak sebagai pihak yang mempercepat teknologi- teknologi baru dalam semua aspek dalam industry dan rekayasa (engineering), yang mencakup telekomunikasi, jaringan komputer, kelistrikan, antariksa, dan elektronika. Tujuan inti IEEE adalah mendorong inovasi teknologi dan kesempurnaan untuk kepentingan kemanusiaan.Visi IEEE adalah akan menjadi penting untuk masyarakat teknis global dan professional teknis dimana-mana dan dikenal secara universal untuk kontribusi teknologi dan teknis yang professional dalam meningkatkan kondisi perkembangan global. Standar dalam IEEE adalah mengatur fungsi, kemampuan dan interoperabilitas dari berbagai macam  produk dan layanan yang mengubah cara orang hidup, bekerja dan berkomunikasi.<br></ol>
			 1.5 Definisi dan akronim (singkatan)<br>
			 <ol>Dalam penulisan dokumen pembuatan projek ini, ada beberapa kata yang mungkin akan sulit dipahami oleh orang awam berikut ini :<br></ol>  
             <ol>IEEE (The International Institute of Electronic and Electrical Engineers) adalah standar yang mendefinisikan lapisan fisik dan sublapisan media akses kontrol dari lapisan data-link dari standar Ethernet berkabel. 
			C (Create): yang berarti membuat sebuah data baru, contoh kita sedang melakukan registrasi disebuah web itu sudah merupakan Create dari CRUD karena kita membuat dan menyimpan data registrasi ke database.
			R (Read): Membaca atau menampilkan suatu data yang tadinya berada didatabase MySQL misalnya, kemudian ditampilkan di WEB menggunakan bahasa pemrograman Php
			U (Update): nah untuk yang satu ini prosesnya adalah mengedit sebuah data dari database yang kemudian di edit menggunakan bahasa pemrograman Php berupa WEB. Contoh edit profil facebook.
			D (Delete): Pastinya Anda tahu fungsinya apa bukan? Fungsinya hampir sama dengan Update akan tetapi proses ini adalah untuk melakukan penghapusan data di database melalui bahasa Php. Contoh pada sebuah blog terkadang ada komentar, kemudian kita hapus komentar tersebut, nah itu sudah termasuk proses delete dalam CRUD.
			ULine (Ujian onLine) adalah proses pelaksanaan Ujian di SMAN 1 Jatibarang yang dilaksanakan secara real-time (langsung) melalui komputer/laptop/tablet PC yang terhubung dengan sambungan internet.<br></ol>
		</ol> <br>
		<b> 
		<li>Organisasi Proyek </li>
		</b>
		<ol>
			2.1 Model proses <br>
				<ol>
					Model proses yang digunakan adalah V-Model, karena metode V-model bisa dikerjakan sebagai Multitask Developer, dimana setiap personal bisa mengerjakan tahap selanjut nya apabila tahap awal masih dalam proses pengerjaan. Kami menggunakan Android Studio untuk menunjang requirement perangkat lunak. <br>
				</ol>
				<img src="https://lh3.googleusercontent.com/-dKojoxI9MKc/Wp_k2a1cQEI/AAAAAAAAAIE/T9nLLrx9R0QC28nJ3WgIFM7acgnFZtoiACL0BGAs/w530-d-h256-n/Capture.JPG=s200" alt="vmodel"><br> <br>
				<ol>
				V-Model merupakan model pengembangan perangkat lunak yang didasarkan pada hubungan antara setiap fase pengembangan siklus hidup yang tercantum dalam model Watterfall yang merupakan pengembangan perangkat lunak dan fase yang terkait pengujian. Bisa dikatakan model ini merupakan perluasan dari model waterfall. Disebut sebagai perluasan karena tahap-tahapnya mirip dengan yang terdapat dalam model waterfall. Jika dalam model waterfall proses dijalankan secara linear, maka dalam model V proses dilakukan bercabang. Adapun kelebihan dari v model ini antara lain :<br></ol>
				<ol>
				<ul>Penyesuaian yang cepat pada projek yang baru</ul>
				<ul>Memudahkan dalam pembuatan dokumen projek</ul>
				<ul>Biaya yang murah dalam perawatan dan modifikasinya</ul>
				<ul>V Model sangat fleksibel. V Model mendukung project tailoring dan penambahan dan pengurangan method dan tool secara dinamik. Akibatnya sangat mudah untuk melakukan tailoring pada V Model agar sesuai dengan suatu proyek tertentu dan sangat mudah untuk menambahkan method dan tool baru atau menghilangkan method dan tool yang dianggap sudah obsolete.</ul>
				</ol>
				<ol>
				Pembuatan Proyek
				Pada tahap pembuatan proyek dilakukan pembuatan aplikasi yang telah direncanakan pada tahap perencanaan sistem.<br></ol>
				<ol>
				2.2 Struktur organisasi <br>
				<ol>
					a. Project Manajer<br>
					b. Programmer<br>
					c. Database <br>
					d. Analisis <br>
				</ol>
				2.3 Batasan dan antarmuka organisasi <br>
					<ol>
					2.3.1. Project Manager ke Anggota<br>
						<ol>
							Manager bisa disebut sebagai ketua dari tim, dimana harus mejadi pengawas dari anggota – anggotanya bila mana saat anggota lalai dengan tugas – tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena \dengan jabatanya. <br>
						</ol>
					2.3.2. Tester Ke Programmer<br>
						<ol>
							Tester dimana saat programmer melakukan kesalahan dalam mengkoding tester memiliki tanggung jawab untuk mengecek kesalahan koding – koding yang dilakukan programmer. <br>
						</ol>
					2.3.3.	Programmer ke sistem<br>
						<ol>
							Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.<br>
						</ol>
					2.3.4. Database administrator ke Programer<br>
						<ol>
							Bertugas untuk memberi rancangan database yang ada dalam projek dan akan dihubungkan melalui programnya.
							atau dapat juga Database Administrator dia bertanggung jawab untuk membuat database sistem yang diperlukan pada aplikasi.<br>
						</ol>
						</ol>
						2.4.	Lingkup tanggung jawab<br>
						<ol>
						Lingkup dan tanggung jawab ini berisi tugas dari setiap elemen anggota dalam 
						pembuatan proyek RPL ini.<br></ol>
						<ol>
						2.4.1.	Project Sponsor<br>
						<ol>
						Project Sponsor adalah seorang manajemen puncak (beserta anggota tim jika perlu), yang diserahkan tugas khusus oleh perusahaan sebagai penanggung jawab proyek sistem informasi. Secara prinsip, Direktur Utama atau Presiden Direktur-lah yang harus menjadi Project Sponsor.<br>
						</ol>
						2.4.2.	Manager<br>
						<ol>
						Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager.<br></ol>
						2.4.3.	Database Administrator<br>
						<ol>
						Database Administrator adalah seseorang yang bertanggung jawab terhadap semua database dari sistem aplikasinya. Pada dasarnya jika tidak ada database administrator maka aplikasi pun tidak akan jadi. Jadi terbukti bahwa database administrator ini sangat penting dalam tim pembuatan proyek.<br>
						</ol>
						2.4.4.	Programmer<br>
						<ol>
						Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari 
						sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.<br> </ol>
						2.4.5.	Tester<br>
						<ol>
						Dalam proyek ini, tester bertugas untuk melakukan pengecekan terhadap sebuah software/aplikasi. Apakah ada error data bug didalamnya, seorang tester harus teliti dalam melakukan tugasnya, apabila ada error yang dilewatkan, maka konsumen akan dirugikan.<br>
						</ol></ol></ol><br>
		<b> 
		3. Proses Manajerial 
		</b>
		<ol>
			3.1.	Tujuan dan prioritas manajemen<br>
			<ol>
				3.1.1.	Prioritas Jadwal<br>
				<ol>
				Prioritas jadwal yang dilakukan pada saat ini adalah membuat sistem yang akan dibuat, dokumen  projek, jadwal  kegiatan, struktur pembuatan projek dan organisasi.<br></ol>
				3.1.2.	Budget
				<ol>Prioritas budget untuk project ini lebih ditekankan pada kualitas hardware dan requirtment proyek.<br></ol>
				3.1.3.	Kemampuan (Kualitas dan Reusability)<br>
				<ol>Projek yang kami buat saat ini mempunyai kelebihan dalam memanajemen pembuatan proyek, juga berbasis desktop yang membuat konsumen merasa lebih budah dalam interaksinya.<br></ol></ol>
				3.2.	Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan<br>
				Asumsi proyek adalah sebagai berikut :<br>
				<ol>
				<li>Tim terdiri dari 3 orang</li>
				<li>Ketersediaan peralatan dan perangkat lunak</li>
				<li>Persetujuan pendanaan</li>
				</ol>
				Substansi Proyek adalah sebagai berikut :<br>
				<ol>
				<li>Aplikasi ini bisa membuat siswa menjadi lebih bersemangat dalam mengerjakan soal UNBK.</li>
				<li>Tersedianya latihan-latihan soal</li>
				</ol>
				Kendala proyek adalah sebagai berikut :<br>
				<ol>
				<li>Waktu</li>
				<li>Anggaran</li>
				<li>Waktu Pengerjaan</li>
				<li>Ketersediaan Perangkat Lunak dan Perangkat Keras beserta spesifikasinya</li>
				</ol>
				3.3.	Manajemen resiko <br>
				<table>
					<tr>
						<td>Resiko</td>
						<td>Teknik Memanajemen Resiko</td>
					</tr>
					<tr>
						<td>Estimasi biaya dan waktu yang tidak realitis</td>
						<td>1. Membuat berapa biaya etimasi<br> 
							2. Desain untuk biaya<br> 
							3. Merekam danmenganalisa project yang akan dibuat</td>
					</tr>
					<tr>
						<td>Mengembangkan Software yang salah</td>
						<td>1. Evaluasi project yang ditingkatkan Buat metode spesifikasi yang formal Survai pengguna <br>
						2. Buat prototype</td>
					</tr>
					<tr>
						<td>Terlambat membangun kebutuhan software</td>
						<td>1. Mengubah prosedur kendali<br>  
							2. Membatasi perubahan terlalu banyak<br>
							3. Meningkatkan pengembangan (akibat perubahan)</td>
					</tr>
					<tr>
						<td>Kegagalan pada komponen komponen</td>
						<td>1. Inspeksi <br>
							2. Analisis project yang akan di buat <br> 
							3. Keterbatasan bahan-bahan</td>
					</tr>
					<tr>
						<td>Pengembanganya terlalu sulit secara teknis</td>
						<td>1. Analisa teknis 
							2. Analisa biaya maanfaat 
							3. Analisa software</td>
					</tr>
					</table>
				3.4.	Mekanisme monitoring dan kontroling <br>
				<ol>
				Proses monitoring dilakukan secara tim, adapun proses pelaksanaannya yaitu :<br>
				<ol>
					<li>Rapat proyek mingguan</li>
					<li>Penyimpanan dokumen bersama</li>
					<li>Survei ke Mitra (SMAN 1 Jatibarang)</li>
					</ol></ol>
				3.5.	Perencanaan staf <br>
				<ol>
				Tim Project untuk aplikasi ini meliputi :<br>
				<ol>
				<li>Devia Suci Khoirun Nissa Sebagai Project Manager</li>
				<li>Kastuti sebagai Database Administrator</li>	
				<li>Reza Pahlevi Yahya sebagai Programmer</li>
				</ol></ol></ol><br>
		</ol>
		<b> 
		4. Proses Teknis
		</b>
		<ol>
		4.1.	Metoda, tool, dan teknik  <br>
		<ol>
		Metoda yang kami gunakan yaitu dengan cara menginputkan data yang digunakan sebagai indikator untuk menentukan nilai yang diharapkan. Tools yang digunakan adalah, database Mysql,Sublime sebagai text editor, Laragon untuk pendukung laravel. Teknik yang digunakan adalah pemrograman berbasis objek. <br></ol>
		4.2.	Dokumentasi perangkat lunak<br>
		<ol>
		Dokumentasi perangkat lunak yang digunakan berdasarkan standar internasional IEEE, karena telah menyediakan kerangka kerja yang menghubungkan seluruh spektrum siklus hidup perangkat lunak. <br> </ol>
		4.3.	Fungsi-fungsi pendukung proyek <br>
		<ol> 
		Kami membutuhkan technical support di bagian desain project. Kami membutuhkan technical support di bagian coding program sebanyak 2-3 orang. Kami membutuhkan specialist di bagian database sebanyak 1-2 orang.<br></ol></ol><br/>