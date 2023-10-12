<h1>DOKUMENTASI PROJECT POSTTEST 2 PBO</h1>

<P>Nama : Gunawan <br>NIM : 2209116066 <br>Kelas : Sistem Informasi B 2022</P>

<h2>A. Screenshot Source Code</h2>

<ol>
  <li>Class Main</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/e8877a3c-ecd6-4f4d-a6ff-9da5c63f9b1f)
  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/89e73895-20ab-412d-9acd-cae056a50ab6)
  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/920995b9-2c43-4d32-9727-7163e3730f17)
  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/5aa11923-97ff-49ac-b48d-c4f5846a2f35)

  <li>Class Person</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/a271634f-2e27-4c73-a4f2-3b93bf96a5c6)

  <li>Class Employee</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/5d2acab1-a01f-40aa-98a1-89b798719a58)

  <li>Class Product</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/9d80da21-6afb-47de-815d-05ac936d0ec5)

  <li>Class Manajer</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/4b588905-67d8-462d-835c-2d4cc5085368)

  <li>Class Customer</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/add683d2-943d-4ae5-9857-7c10a945bc1b)

  <li>Class Cashier</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/6a9b78f7-9d6a-448c-a14a-a531e5f504eb)

</ol>

<h2>B. Penjelasan Source Code</h2>

<ol>
  <li>Class Main</li>
  <p>Class Main adalah class manajemen entitas (karyawan, manajer, kasir, pelanggan, dan produk) yang dapat melakukan berbagai tugas, seperti menambahkan, menampilkan, memperbarui, dan menghapus informasi. Di bawah ini adalah penjelasan fungsionalitas dari berbagai pilihan menu dalam class:</p>
  <ol>
    <li>Tambah Karyawan (1):</li>
    <p>Pengguna diminta untuk memasukkan nama dan gaji karyawan baru. Informasi ini kemudian digunakan untuk membuat objek Employee yang kemudian ditambahkan ke dalam daftar orang (peopleList).</p>
    <li>Tambah Manager (2):</li>
    <p>Pengguna diminta untuk memasukkan nama dan gaji manager baru. Informasi ini kemudian digunakan untuk membuat objek Manajer yang kemudian ditambahkan ke dalam daftar orang (peopleList).</p>
    <li>Tambah Kasir (3):</li>
    <p>Pengguna diminta untuk memasukkan nama dan gaji kasir baru. Informasi ini kemudian digunakan untuk membuat objek Cashier yang kemudian ditambahkan ke dalam daftar orang (peopleList).</p>
    <li>Tambah Pelanggan (4):</li>
    <p>Pengguna diminta untuk memasukkan nama dan jumlah uang di dompet pelanggan baru. Informasi ini kemudian digunakan untuk membuat objek Customer yang kemudian ditambahkan ke dalam daftar orang (peopleList).</p>
    <li>Tambah Produk Olahraga (5):</li>
    <p>Pengguna diminta untuk memasukkan nama dan harga produk olahraga baru. Informasi ini kemudian digunakan untuk membuat objek Product yang kemudian ditambahkan ke dalam daftar orang (peopleList).</p>
    <li>Tampilkan Semua Informasi (6):</li>
    <p>Program akan menampilkan semua informasi dari setiap orang atau produk di dalam daftar.</p>
    <li>Perbarui Informasi (7):</li>
    <p>Pengguna diminta untuk memasukkan nama orang atau produk yang ingin diperbarui. Jika nama tersebut cocok dengan nama di dalam daftar, pengguna dapat memperbarui informasi terkait (gaji, dompet, atau harga).</p>
    <li>Hapus Informasi (8):</li>
    <p>Pengguna diminta untuk memasukkan nama orang atau produk yang ingin dihapus. Jika nama tersebut cocok dengan nama di dalam daftar, orang atau produk akan dihapus dari daftar.</p>
    <li>Keluar (0):</li>
    <p>Program akan selesai.</p>
  </ol>
  <p>Penting untuk diingat bahwa program ini berjalan dalam loop tak terbatas (while (true)) sehingga pengguna dapat terus melakukan operasi hingga memilih untuk keluar (menu 0). Selain itu, aplikasi juga memastikan bahwa setiap kali pengguna memasukkan angka, newline yang mungkin ada di buffer dibersihkan menggunakan scanner.nextLine() sebelum melanjutkan.</p>
  <li>Class Person</li>
  <p>kelas Person adalah kelas dasar atau induk dari hierarki kelas yang lebih spesifik. Itu menyediakan kerangka dasar yang dibutuhkan untuk mewakili individu dalam sistem atau aplikasi yang lebih besar. Namun, karena kelas ini bersifat abstrak, maka tidak dapat diinstansiasi secara langsung, melainkan digunakan sebagai kerangka untuk kelas-kelas turunannya.</p>
  <li>Class Employee</li>
  <p>kelas Employee adalah kelas yang merepresentasikan seorang karyawan, dengan atribut nama dan gaji, serta memiliki kemampuan untuk menampilkan informasi tersebut.</p>
  <li>Class Product</li>
  <p>kelas Product adalah kelas yang merepresentasikan sebuah produk, dengan atribut nama dan harga, serta memiliki kemampuan untuk menampilkan informasi tersebut</p>
  <li>Class Manajer</li>
  <p>kelas Manajer adalah turunan dari kelas Employee yang merepresentasikan seorang manajer. Itu memiliki atribut nama dan gaji, serta memiliki kemampuan untuk menampilkan informasi tersebut.</p>
  <li>Class Customer</li>
  <p>kelas Customer adalah turunan dari kelas Person yang merepresentasikan seorang pelanggan. Itu memiliki atribut nama dan jumlah uang dalam dompet, serta memiliki kemampuan untuk menampilkan informasi tersebut.</p>
  <li>Class Cashier</li>
  <p>kelas Cashier adalah turunan dari kelas Employee yang merepresentasikan seorang kasir. Itu memiliki atribut nama dan gaji, serta memiliki kemampuan untuk menampilkan informasi tersebut.</p>
</ol>

<h2>C. Penjelasan Output</h2>
<ol>
  <li>Tambah karyawan</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/973ef381-d98b-4d27-83ff-e2b4f8461dab)

  <li>Tambah manajer</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/16a07a45-90b3-4927-9319-f197a9b2c8e0)

  <li>Tambah kasir</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/b48066f6-72ff-40fd-8f64-64550d27ce0a)

  <li>Tambah pelanggan</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/512e2f03-8862-4299-87ea-bd06cf1acfaf)

  <li>Tambah produk olahraga</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/3699ee51-2a18-4714-affe-19e4ee8f44eb)

  <li>Tampilkan semua informasi</li>

  ![image](https://github.com/GUNAWAN2209116066/-pbo-post-test-2/assets/127533024/58f34e74-6111-4a56-9d43-630b2d2dfd14)

  <li>Perbarui informasi</li>
  <li>Hapus informasi</li>
  <li>Exit</li>
</ol>
