Memetakan Bucket Amazon S3 sebagai Drive Nyata

Apakah Anda ingin memetakan bucket Amazon S3 Anda sebagai drive nyata di Windows? Ada alat yang bagus untuk itu bernama DriveMaker, yang melakukan hal itu. Setelah bucket S3 Anda dipasang sebagai drive, Anda dapat menggunakan aplikasi apa pun di Windows untuk mengaksesnya secara langsung. Ini berfungsi bahkan pada prompt perintah dan dari dalam file batch dan skrip PowerShell, pemindai anti-virus, dll. Ini seperti drive jaringan lokal pada mesin Anda sendiri, tetapi muncul sebagai drive fisik yang nyata.

Misalnya, Anda dapat memetakan bucket Amazon S3 Anda ke X:\ dan kemudian mengedit dokumen Word langsung di dalamnya, tanpa harus mengunduh dan mengunggah file dengan tangan. Selain itu, Anda dapat menyalin dan menempelkan file di Windows File Explorer, persis seperti yang Anda lakukan dengan drive lainnya. Alat yang bagus di dalam DriveMaker adalah kemampuan Sync-nya. Anda bisa menjalankan tugas sinkronisasi secara otomatis atau dengan mengklik tombol, untuk menyinkronkan file di cloud dengan salinan lokal Anda atau sebaliknya.

Setelah Anda menginstal DriveMaker, cukup klik 'add site' dan masukkan semua informasi Amazon S3, seperti yang ditunjukkan pada contoh di bawah ini:

Contoh di atas memetakan bucket Amazon S3 kami ke drive X:. Setelah Anda menyimpan profil dan klik connect, drive X: akan terbuka di Windows File Explorer. Kemudian tersedia untuk bekerja seperti drive lainnya.
Memetakan S3 sebagai Drive Jaringan yang Dipasang di semua Platform Windows

[DriveMaker](https://backupchain.com/en/drivermakerplus-mountmap-ftp-and-ftps-secure-to-a-drive-letter/) berjalan di semua platform Windows. Windows 7 hingga Windows 11 PC dan Windows Server 2008 hingga 2022. Anda dapat memulainya secara otomatis dengan Windows dan situs dapat dikonfigurasikan untuk terhubung secara otomatis jika Anda suka. [DIY cloud](https://backupchain.com/i/how-to-own-private-diy-cloud-server-storage-with-mapped-drive) adalah alternatif lain dari Amazon.

Gambaran Umum Amazon
Amazon Web Services (AWS) adalah penyedia komputasi awan AS yang didirikan pada tahun 2006 sebagai anak perusahaan dari perusahaan pesanan surat online Amazon.com. Banyak layanan populer seperti Dropbox, Netflix, Foursquare atau Reddit mengandalkan Amazon Web Services. Pada tahun 2017, Gartner menempatkan AWS sebagai penyedia internasional terkemuka dalam komputasi awan.
Sejarah

AWS diluncurkan pada tahun 2006 untuk menyediakan infrastruktur TI sesuai permintaan bagi para pengembang; sejak awal, fokus utamanya adalah pada perusahaan daripada pengguna akhir. Perusahaan ini membutuhkan pusat data yang didistribusikan secara global dan layanan yang sangat tersedia untuk pengoperasian platform e-commerce-nya itu sendiri, serta antarmuka ke aplikasi lain, yang juga akan tersedia untuk pihak ketiga dengan Amazon Web Services. Namun, Amazon tidak mengambil langkah ini untuk memanfaatkan kapasitasnya dengan lebih baik. Layanan server virtual AWS pertama dirancang di salah satu situs perusahaan di Afrika Selatan.
Layanan Amazon Web Services ditawarkan sebagian secara gratis. Pada bulan November 2010, perusahaan ini meluncurkan program yang disebut Free Usage Tier, yang mencakup daya komputasi (750 jam) dan layanan AWS populer lainnya secara terbatas. Pada akhir tahun pertama, pelanggan harus beralih ke paket komersial dan membayar biaya biasa. Pengenalan kontingen gratis secara luas dipandang sebagai reaksi terhadap OpenStack, yang secara khusus didorong oleh perusahaan saingan Rackspace.
Amazon juga mengoperasikan pusat pengembangan di Jerman, Rumania dan Belanda, di mana Amazon sedang mengerjakan teknologi masa depan untuk AWS. Di Frankfurt am Main, grup ini mengoperasikan tiga pusat data.
Pada bulan Oktober 2021, AWS menerima kontrak besar dari dinas intelijen Inggris (MI5, MI6 dan GCHQ) untuk membangun sistem cloud untuk data rahasia di Inggris.
Komponen
Server

EC2 (Elastic Compute Cloud) adalah server virtual yang menjalankan distribusi Linux atau Microsoft Windows Server. Mereka tidak memiliki jangka waktu kontrak tetap dan ditagih per jam atau bahkan per detik. Ada beberapa tarif yang dapat dipilih, yang berbeda berdasarkan RAM yang tersedia dan unit komputasi, yang sesuai dengan prosesor virtual. Dibandingkan dengan penyedia lainnya, instance mesin virtual tidak persisten. Artinya, isi RAM dihapus ketika instance dihentikan.
Penyimpanan

S3 (Simple Storage Service) adalah layanan hosting file yang secara teoritis dapat menyimpan sejumlah data dan ditagih berdasarkan penggunaan. Akses melalui HTTP/HTTPS. Amazon pertama kali memperkenalkan konsep bucket dan objek, yang menyerupai direktori dan file dan telah menjadi standar yang ditiru oleh penyedia lain. Amazon juga menawarkan drive jaringan dengan Elastic File System dan pengarsipan file dengan Glacier. Amazon menjanjikan masa simpan data "99,9999999" persen.
Amazon Elastic Block Store (EBS) menyediakan penyimpanan tingkat blok yang dapat dilampirkan ke instance Amazon EC2.

Untuk memfasilitasi transfer data dalam jumlah besar, AWS menyediakan penyimpanan disk yang dapat disewa melalui layanan Snowball-nya, di mana sejumlah besar data dapat disalin dan dikembalikan melalui layanan paket. Mentransfer data dalam jumlah yang sangat besar (beberapa ratus terabyte hingga petabyte) ke cloud dengan demikian jauh lebih cepat.
Jaringan


CloudFront adalah jaringan pengiriman konten yang dapat mengirimkan konten dari layanan AWS lainnya, seperti EC2 atau S3, dengan cara yang terdistribusi secara global untuk mengurangi waktu akses. Layanan ini terbatas pada protokol HTTP (S) dan dikenakan biaya berdasarkan gigabyte yang diakses tergantung pada wilayahnya. Tergantung pada konfigurasi, file individual atau seluruh domain dapat disediakan melalui CloudFront, secara opsional dienkripsi melalui SSL. Selain itu, Amazon mengoperasikan layanan nama domain dengan nama Route 53, yang memungkinkan terjemahan timbal balik alamat IP dan domain. Penagihan dilakukan secara bertahap sesuai dengan zona yang digunakan.
Basis Data

Baik SimpleDB atau Relational Database Service (disingkat RDS) dapat digunakan sebagai basis data virtual. Yang pertama dimaksudkan untuk menyimpan informasi sederhana - yaitu, non-relasional - yang dapat disusun dalam bentuk objek dan properti. SimpleDB masih dalam pengujian beta, menurut Amazon, sementara RDS didukung secara resmi. Layanan Basis Data Relasional mencakup basis data virtual berdasarkan MySQL, Microsoft SQL Server atau Oracle. Sementara SimpleDB ditagih semata-mata berdasarkan jumlah memori yang digunakan, tarif Amazon RDS didasarkan pada memori dan kekuatan pemrosesan dari instance yang dipilih.
Pengembangan

Amazon menawarkan Elastic Beanstalk, PaaS untuk Java, Python, Docker dan platform lainnya. Selain itu, dengan Simple Workflow Service (SWS), Simple Email Service (SES), Simple Queue Service (SQS) atau Simple Notification Service (SNS), layanan lebih lanjut disediakan untuk pengembang. Yang terakhir ini cocok, misalnya, untuk mengirim pemberitahuan tentang peristiwa tertentu dari layanan AWS lainnya melalui email atau SMS. Selain itu, aplikasi dapat digunakan di Amazon Web Services dalam apa yang disebut AWS Marketplace, di mana mereka dapat dipesan oleh pihak ketiga.


Direktori

AWS Identity and Access Management (disebut IAM) adalah layanan direktori untuk mengelola pengguna dan sumber daya dalam suatu organisasi. Tanpa Amazon IAM, login ke layanan AWS apa pun terbatas pada akun Amazon pribadi, yang memberikan hak administratif dan mungkin merupakan risiko keamanan dalam penggunaan produksi. Identitas dan Manajemen Akses dapat digunakan untuk membuat pengguna, mengelompokkannya, dan mengontrol akses mereka ke hampir semua layanan AWS, seperti EC2 atau S3.


Manajemen

Dalam beberapa tahun terakhir, Amazon telah mengembangkan banyak layanan web yang berfungsi untuk mengelola penawaran inti. Misalnya, pada bulan Mei 2009 Amazon CloudWatch memperkenalkan kemungkinan untuk memantau server virtual pada EC2 dan, jika perlu, untuk secara otomatis menyesuaikan tarif yang dipilih dan sumber dayanya berdasarkan pemanfaatan (skalabilitas). Sejak awal tahun 2012, koneksi jaringan khusus ke Amazon Web Services dapat dibuat dengan Amazon Direct Connect, yang diimplementasikan melalui host web pihak ketiga dan dimaksudkan untuk memfasilitasi transfer data dalam volume besar dan meningkatkan keamanan TI dan perlindungan data.


Lainnya

Sementara semua layanan lainnya didasarkan pada layanan teknis, Amazon Mechanical Turk (setelah nama bahasa Inggris dari shaft Turk) adalah pengecualian: pekerjaan dapat diposting di sana yang dapat dipecah menjadi tugas-tugas kecil dan diproses oleh manusia. Ini termasuk, misalnya, pekerjaan pencarian sederhana di World Wide Web atau koreksi kesalahan ejaan dalam kalimat individu. Mechanical Turk juga banyak digunakan untuk mengenali objek dalam gambar (seperti manusia atau hewan). Layanan ini masih dalam pengujian beta.


Privasi

Karena Amazon adalah perusahaan AS, Amazon Web Services, seperti layanan yang sebanding, telah dikritik di Jerman selama bertahun-tahun sehubungan dengan perlindungan data. Untuk mengimbangi masalah tersebut, Amazon menawarkan apa yang disebut wilayah, yang pada gilirannya dibagi menjadi Zona Ketersediaan dan sesuai dengan lokasi fisik untuk menyimpan data. Misalnya, untuk Amazon EC2, wilayah Irlandia (eu-west-1) dan Frankfurt am Main (eu-central-1) dapat dipilih sehingga instance hanya akan berjalan di sana. Sejak tahun 2007, wilayah di luar Amerika Serikat juga telah tersedia untuk Amazon S3. Namun, server yang berlokasi di UE tidak melindungi dari akses oleh otoritas AS berdasarkan Cloud Act.
Untuk meningkatkan perlindungan data, Amazon juga secara eksplisit memberikan pengembang kemampuan untuk mengenkripsi ulang data yang disimpan di AWS sendiri - bahkan ketika menggunakan kit pengembangan perangkat lunak resmi. Perusahaan besar diizinkan untuk menggunakan enkripsi perangkat keras dengan komponen individual.


Kritik

Kerentanan keamanan yang serius di Amazon Web Services telah berulang kali diketahui, itulah sebabnya platform ini dipandang kritis oleh para ahli. Selain itu, diketahui pada tahun 2013 bahwa Amazon telah menerima pesanan besar dari CIA dan akan mengoperasikan cloud publiknya, yang menimbulkan keraguan lebih lanjut tentang perlindungan data dari penawaran tersebut. Amazon menang dengan AWS dalam penghargaan melawan IBM dan pelamar lainnya.
Pada bulan Desember 2010, Amazon Web Services sempat digunakan oleh WikiLeaks untuk mengurangi beban pada server mereka sendiri. Server-server ini berada di bawah tekanan karena publikasi pengiriman diplomatik dan kadang-kadang tidak bisa lagi mengirimkan konten sama sekali. Amazon memblokir akses untuk WikiLeaks tidak lama setelah hubungan pelanggan diketahui, karena "materi ilegal" telah tersedia di sana, menurut pernyataan resmi dari perusahaan. Namun, para pengamat menganggap tekanan politik sebagai alasan yang menentukan, terutama dari pihak Senator Joe Lieberman. Keputusan Amazon disambut dengan kontroversi publik dan meraih perhatian media yang luas.
Amazon mengklaim melindungi pusat datanya sesuai dengan prosedur standar industri, terutama dari pemadaman listrik. Namun, perusahaan ini mendapat kritik karena masalah serius tetap saja terjadi berkali-kali. Misalnya, sambaran petir pada bulan Agustus 2011 menyebabkan layanan di pusat data Irlandia tidak tersedia dan banyak layanan online lainnya yang mati sebagai akibatnya. Kasus ini menarik perhatian luas, karena Microsoft juga terpengaruh selain Amazon. Pada bulan Juli 2012, kesalahan serupa terjadi, yang diserap oleh catu daya darurat, tetapi yang pada gilirannya juga mengalami kerusakan teknis beberapa saat kemudian. Setelah pemadaman tiga kali lipat, Amazon dituduh tidak cukup menguji sistemnya. Baru-baru ini, pemadaman pada bulan Agustus 2013 mengganggu Vine dan Instagram, antara lain. 
