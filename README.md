<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title> HOME </title>
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
            <link rel="stylesheet" href="styles.css">
            
    </head>

    <body>
    <!-- Navbar Start --> 
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark text-light sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Juli Chairani (⁠つ⁠≧⁠▽⁠≦⁠)⁠つ</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="A1.html"></a>
          </li>
          

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
          Login
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="JP.html"> Selamat Mencoba! :> </a></li>
            <div> 
              <div class="login-container">
                <h2>Login akun</h2>
                <form id="loginForm" method="POST" action="login.php">
                    <div class="input-group">
                        <label for="username">Username:</label>
                        <input type="text" id="username" name="username">
                    </div>
                    <div class="input-group">
                        <label for="password">Password:</label>
                        <input type="password" id="password" name="password">
                    </div>
                    <button type="submit">Login</button>
                </form>
                <div id="message">
                </div>
            </div>
          </ul>  
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
          Form anggota
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="JP.html"> isi form berikut ya! :> </a></li>
            <div> 
              <!-- Form Start-->
            <section> 
              <h1> Formulir Anggota </h1> 
              <div id="formulir anggota perpustakaan;">
                <table border="1 text-align: center;">
                    <form action="" method="POST"
                <table>
                        <tr>
                             <td>Nama</td>
                             <td><input type="text"></td>
                         </tr>
                    
                          <tr>
                            <td>NIM</td>
                            <td><input type="number"></td>
                        </tr>
                    
                        <tr>
                            <td>Tanggal</td>
                            <td><input type="date"></td>
                        </tr>
                    
                        <tr>
                            <td>Jenis Kelamin</td>
                            <td><input type="radio" name="jk"> Pria
                                <input type="radio" name="jk"> Wanita
                            </td>
                        </tr>
                    
                        <tr>
                            <td>Alamat</td>
                            <td><textarea></textarea></td>
                        </tr>
                    
                        <tr>
                            <td></td>
                            <td><input type="submit" value="simpan">
                                <input type="reset" value="reset">
                                <input type="button" value="kembali">
                            </td>
                        </tr>
                </table>
             </div>
          <!-- Form End -->
            </ul>  
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Perpustakaan
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="JP.html"> perpustakaan UMSU </a></li>
              <div>
                <!-- content 1 -->
                <a href="https://perpustakaan.umsu.ac.id/">
                    <img src="perpus umsu.jpg" alt="foto perpustakaan umsu" width="100" height="50">
                <p style="color:rgb(17, 134, 76);margin-left:20px;">Perpustakaan UMSU</p>
                </a>
            </div>
                 <!-- content 1 end-->
              <li><a class="dropdown-item" href="AV.html">Audio dan Video</a></li>
              <h1> video</h1>
                   <video controls width="100" height="50">
    <source src="video perpus umsu.mp4" type="video/mp4">
              </video>
              <h1> audio</h1>
                  <audio controls>
                   <source src="duvet1.mp3" type="audio/mpeg">
              </audio>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
          Koleksi
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="JP.html"> bahan buku </a></li>
            <div>   
                <!-- Table Bordered Start-->
     <table class="table table-bordered border-danger-subtle">
        
        <thead>
          <tr class="text-center">
            <th scope="col">No</th>
            <th scope="col">Judul</th>
            <th scope="col">penulis</th>
            <th scope="col">Tahun</th>
            <th scope="col">No. Panggil</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row" class="text-center">1</th>
            <td>Hukum perkawinan indonesia</td>
                    <td>Refika Aditama</td>
                    <td>2016</td>
                    <td>364.016 Isn h</td>
          </tr>
          <tr>
            <th scope="row" class="text-center">2</th>
            <td>233 tanya jawab seputar hukum bisnis</td>
                    <td>Pustaka Utami Grafiti</td>
                    <td>2011</td>
                    <td>346.07 Pra d</td>
          </tr>
        </tbody>
      </table>
     <!-- Table Bordered End -->
    </ul>
  </li>
<li class="nav-item dropdown">
  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
Mini calculator
  </a>
  <ul class="dropdown-menu">
    <li><a class="dropdown-item" href="JP.html"> Selamat Mencoba! :> </a></li>
  <div> 
        <div class="calculator">
            <h2>perhitungan Sederhana</h2>
            <form method="post" action="<?php echo $_SERVER['PHP_SELF'];?>">
                <input type="number" name="number1" placeholder="Masukkan bilangan pertama" required>
                <input type="number" name="number2" placeholder="Masukkan bilangan kedua" required>
                <select name="operation" required>
                    <option value="add">Penjumlahan</option>
                    <option value="subtract">Pengurangan</option>
                    <option value="multiply">Perkalian</option>
                    <option value="divide">Pembagian</option>
                </select>
                <button type="submit">Hitung</button>
            </form>
        </div>
    </html>
  </ul>  
</li>
<li class="nav-item dropdown">
  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
Library Database
  </a>
  <ul class="dropdown-menu">
  <div> 
    <style>
      table {
          width: 5%;
          border-collapse: collapse;
          margin-top: 5px;
      }
      table, th, td {
          border: 1px solid rgb(255, 255, 255);
      }
      th, td {
          padding: 5px;
          text-align: left;
          background-color: #dabebe;
      }
      th {
          background-color: #f2f2f2;
      }
      form {
          margin-top: 5px;
      }
      input, button {
          padding: 4px;
          margin: 2px;
      }
      button {
          cursor: pointer;
      }
  </style>
    <table id="libraryTable">
        <thead>
            <tr>
                <th>Judul</th>
                <th>Penulis</th>
                <th>Tahun</th>
                <th>ISBN</th>
                <th>Edit</th>
            </tr>
        </thead>
        <tbody>
            <!-- Data rows will be inserted here by JavaScript -->
        </tbody>
    </table>

    <form id="libraryForm">
        <input type="hidden" id="editIndex">
        <input type="text" id="title" placeholder="Title" required>
        <input type="text" id="author" placeholder="Author" required>
        <input type="number" id="year" placeholder="Year" required>
        <input type="text" id="isbn" placeholder="ISBN" required>
        <button type="button" onclick="addOrUpdateBook()">Tambah/Perbarui</button>
    </form>

    <script>
        let libraryData = [
            { title: "Harry Potter and the Philosopher's Stone", author: "J.K. Rowling", year: 1997, isbn: "9780747532743" },
            { title: "To Kill a Mockingbird", author: "Harper Lee", year: 1960, isbn: "9780061120084" },
            { title: "1984", author: "George Orwell", year: 1949, isbn: "9780141036144" },
            { title: "The Great Gatsby", author: "F. Scott Fitzgerald", year: 1951, isbn: "9780743273565" },
        ];

        function displayLibrary() {
            const tbody = document.getElementById('libraryTable').getElementsByTagName('tbody')[0];
            tbody.innerHTML = "";
            libraryData.forEach((book, index) => {
                const row = tbody.insertRow();
                row.innerHTML = `
                    <td>${book.title}</td>
                    <td>${book.author}</td>
                    <td>${book.year}</td>
                    <td>${book.isbn}</td>
                    <td>
                        <button onclick="editBook(${index})">Edit</button>
                        <button onclick="deleteBook(${index})">Hapus</button>
                    </td>
                `;
            });
        }

        function addOrUpdateBook() {
            const title = document.getElementById('title').value;
            const author = document.getElementById('author').value;
            const year = document.getElementById('year').value;
            const isbn = document.getElementById('isbn').value;
            const editIndex = document.getElementById('editIndex').value;

            const book = { title, author, year, isbn };

            if (editIndex === "") {
                libraryData.push(book);
            } else {
                libraryData[editIndex] = book;
                document.getElementById('editIndex').value = "";
            }

            document.getElementById('libraryForm').reset();
            displayLibrary();
        }

        function editBook(index) {
            const book = libraryData[index];
            document.getElementById('title').value = book.title;
            document.getElementById('author').value = book.author;
            document.getElementById('year').value = book.year;
            document.getElementById('isbn').value = book.isbn;
            document.getElementById('editIndex').value = index;
        }

        function deleteBook(index) {
            libraryData.splice(index, 1);
            displayLibrary();
          }

displayLibrary();
</script>
      </div>
</ul>  
</li>
<li class="nav-item dropdown">
  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
Kepuasan Pengguna
  </a>
  <ul class="dropdown-menu">
  <div>
    <!DOCTYPE html>
    <html>
    <body>
    
    <h2>Apakah Layanan Kami Membantu Anda?</h2>
    
    <button type="button"
    onclick="document.getElementById('demo').innerHTML = Date()">
    ya</button>
    
    <button type="button"
    onclick="document.getElementById('demo').innerHTML = Date()">
    tidak </button>
    
    
    <p id="demo"></p>
    
    </body>
    </html> 
  </div>
</ul>  
</li>

    <form class="d-flex" role="search">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-light" type="submit">Search</button>
    </form>
</div>
</nav>
<!-- Navbar End --> 

     <!-- 3 Kolom Start--> 
  <div class="row text-center align-items-center">
    <div class="col-4">
      <h1 style="color: #1db461;"> ✧ Selamat Datang di Dr. Stone's Library✧ <style>
        Body {background-color:rgb(224, 241, 210)}
    </style></h1>
      </div>

      <div class="col-4">
        <img src="weoko.png" width="600" height="300" alt="logo">
      </div>
  </div>
</div>
     <!-- 3 Kolom End -->

     <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>  ABOUT HTML & CSS </title>
                <link rel="stylesheet" href="modul3.css">
        </head>
    
        <body>
            <h1> Tentang HTML (HyperText Markup Language) </h1>
            <p> HTML adalah bahasa markah yang digunakan untuk membuat struktur dan konten pada halaman web. 
                Dengan HTML, elemen-elemen seperti teks, gambar, hyperlink, dan video dapat ditempatkan dan diatur secara hierarkis. 
                Setiap elemen HTML didefinisikan oleh tag, yang menggambarkan fungsi dan tampilan elemen tersebut.</p>
    
            <h2> Tentang CSS (Cascading Style Sheets) </h2>
            <p> CSS adalah bahasa gaya yang digunakan untuk mengatur tampilan 
                dan tata letak elemen-elemen HTML pada halaman web. Dengan CSS, kita dapat mengontrol 
                warna, font, ukuran, jarak, dan banyak aspek visual lainnya dari elemen-elemen HTML. </p>
        </body>
    </html>
      
     <div>
      <div class="container-footer text-center">
        <h1 class="h1-footer"></h1>
     <h1>Pameran Buku</h1>
  <p>Klik tombol di bawah untuk melihat daftar buku yang tersedia di pameran ini.</p>
  <button onclick="displayBooks()">Tampilkan Buku</button>

  <div>
      <h2>Tambahkan Buku Baru</h2>
      <input type="text" id="newBookTitle" placeholder="Judul Buku" />
      <input type="text" id="newBookAuthor" placeholder="Penulis Buku" />
      <input type="text" id="newBookImage" placeholder="URL Gambar Buku" />
      <button onclick="addBook()">Tambahkan Buku</button>
  </div>

  <div id="bookList"></div>

  <script>
      let books = [
      { title: "Lady Baby", author: "Ju Hyeon, Pinkmint", image: "ladybaby.jpg" },
            { title: "Solo Leveling", author: "Chu-Gong", image: "sololave.jpeg" },
            { title: "Who Made Me a Princess", author: "Plutus", image: "who mademe.jpg" },
            { title: "Into The Light, Once Again", author: "Tikatika, Yuya", image: "intothelight.jpg" },
            ];
            
      function displayBooks() {
          let bookListDiv = document.getElementById("bookList");
          bookListDiv.innerHTML = ''; // Bersihkan daftar buku sebelum menampilkan

          // Struktur Perulangan
          for (let i = 0; i < books.length; i++) {
              let bookDiv = document.createElement("div");
              bookDiv.className = "book";

              let bookTitle = document.createElement("h3");
              bookTitle.textContent = books[i].title;

              let bookAuthor = document.createElement("p");
              bookAuthor.textContent = "Penulis: " + books[i].author;

              let bookImage = document.createElement("img");
              bookImage.src = books[i].image;
              bookImage.width = 400; // Tentukan ukuran lebar
              bookImage.height = 550; // Tentukan ukuran tinggi

              bookDiv.appendChild(bookImage);
              bookDiv.appendChild(bookTitle);
              bookDiv.appendChild(bookAuthor);

              bookListDiv.appendChild(bookDiv);
          }

          // Menambah event listener untuk menghapus buku ketika diklik
          let bookDivs = document.getElementsByClassName("book");
          for (let i = 0; i < bookDivs.length; i++) {
              bookDivs[i].addEventListener("click", function() {
                  this.remove();
              });
          }
      }

      function addBook() {
          let newBookTitle = document.getElementById("newBookTitle").value;
          let newBookAuthor = document.getElementById("newBookAuthor").value;
          let newBookImage = document.getElementById("newBookImage").value;

          if (newBookTitle && newBookAuthor && newBookImage) {
              books.push({
                  title: newBookTitle,
                  author: newBookAuthor,
                  image: newBookImage
              });
              displayBooks(); // Update tampilan buku setelah menambahkan buku baru
              document.getElementById("newBookTitle").value = ''; // Kosongkan input setelah menambahkan
              document.getElementById("newBookAuthor").value = '';
              document.getElementById("newBookImage").value = '';
          } else {
              alert("Semua kolom harus diisi!");
          }
      }

  </script> 
  </div>
          
    <!-- about -->
    <section class="about" id="about">
        <div class="container">
          <div class="row">
            <div class="col-sm-12">
              <h2 class="text-center">About us</h2>
            </div>
          </div>
    
              <p> Halo! Terima kasih telah mengunjungi website ini
    
                Website ini dibuat untuk memenuhi tugas pada mata kuliah Pemrograman Web Praktik dengan dosen pengampu Ibu Himma Dewiyana, S.T., M.Hum pada program studi S-1 Perpustakaan dan Sains Informasi, Fakultas Ilmu Budaya, Universitas Sumatera Utara.
               </p>

               <div class="container-footer text-center">
        <h1 class="h1-footer"></h1>
               +68-8765090
               Dr. stone library kontak
            </div>

    <div class="container-footer text-center">
        <h1 class="h1-footer"></h1>
        <p style="color:#1db461">Copyright © Juli Chairani Siagian - 210709022</p>
    </div>
</div>

      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
   
    </body>
</html>
