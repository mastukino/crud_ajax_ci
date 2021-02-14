# PHP CRUD Dengan MySQLi dan CodeIgniter 4

Materi CodeIgniter 4: Beberapa Bulan lalu ramainya sebuah topik pembahasan untuk framework codeigniter 4 di Indonesia, sebagai user CodeIgniter seperti saya tentunya penasaran untuk mencoba framework yang masih anget ini. CodeIgniter muncul versi terbaru yaitu versi 4, cukup banyak hal yang berubah dari segi bentuk kode bagi saya seperti penambahan namespace, use dan sebagainya pada fitur yang dibawa php versi 7 , meskipun saya juga merupakan user baru dari codeigniter 4 ini dan masih perlu sama-sama belajar untuk CI 4 ini. Hal-hal apa saja yg akan di pelajari pada materi basic CRUD CodeIgniter 4 ini yaitu sebagai berikut:
1.	Pengenalan CodeIgniter 4
2.	Cara Installasi CodeIgniter 4
3.	Membangun aplikasi CRUD Sederhana dengan CodeIgniter 4, berikut hal-hal yang dipelajari:
    - Melihat konsep menampilkan data view (Read)
    - Mengkoneksikan CodeIgniter 4 dengan Database
    - Menampilkan data dari database ke view dengan tampilan Bootstrap 4 (Read)
    - Melakukan Insert data (Create)
    - Melakukan Update data (Update)
    - Melakukan Delete data (Delete)
    
## Pengenalan CodeIgniter 4
CodeIgniter merupakan salah satu Framework PHP untuk membangun aplikasi berbasis web, yang bersifat open source yang menggunakan metode MVC (Model, View, Controller). Framework Codeigniter dibuat dengan tujuan yang sama dengan framework lain yaitu membantu mempermudah kan developer atau programmer dalam membangun sebuah aplikasi berbasis web, tanpa harus build dan coding dari awal. MVC adalah teknik atau konsep yang memisahkan komponen utama menjadi 3 bagian:
# Model
Model merupakan bagian penanganan yang berhubungan atau manipulasi data dengan database, misal mengambil data dari database, dan proses crud atau intruksi yang berhubungan dengan database diletakan di dalam model.
# View
View merupakan bagian penanganan interface atau antarmuka web, yang muncul kepada user, dengan memisahkan controller dengan model dapat memudahkan programmer untuk melakukan suatu pengembangan web pada tampilan halaman suatu website.
# Controller
Controller merupakan bagian instruksi aksi yang menghubungkan model dan view, jadi controller ini kumpulan instruksi aksi yang berfungsi sebagai jembatan dari model dan view.

Spesifikasi yang dibutuhkan CodeIgniter 4 : Menurut dokumentasi resmi CodeIgniter, CI 4 membutuhkan dan menggunakan spesifikasi PHP >= 7.2 , bila anda masih menggunakan PHP < 7.2 disarankan untuk melakukan Update.
