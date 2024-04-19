# TUGAS-PWEB
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TUGAS PEMROGRAMAN WEB</title>
 
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .jumbotron {
      background-color: #343a40;
      color: #fff;
      padding: 100px 25px;
      margin-bottom: 0;
    }
    .feature {
      background-color: #fff;
      padding: 50px 25px;
      border-radius: 5px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .navbar-brand {
      font-weight: bold;
    }
    .feature img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Beranda</a>
    </div>
  </nav>
  
  </script>

  <div class="jumbotron text-center">
    <h1 class="display-4">Selamat Datang</h1>
    <p class="lead">DAFFA ARYA SYAHPUTRA</p>
  </div>

  <div class="container mt-5">
    <div class="row">
      <div class="col-md-4">
        <div class="feature">
          <h2>BIODATA</h2>
          <p>Nama: DAFFA ARYA SYAHPUTRA</p>
          <p>Umur: 22 TAHUN </p>
          <p>Alamat: JALAN SAPTA PRASETYA UTARA 3 NOMOR 63 PEDURUNGAN KIDUL</p>
          <p>Email: CENDOLDAFFA@GMAIL.COM</p>
          <p>Asli : SEMARANG </p>
          <p>Hobi : MODIFIKASI MOTOR</p>
          <p>Jurusan : SISTEM INFORMASI</p>
          <p>Nomor HP : 081393603376</p>
          <p>Kampus : UDINUS SEMARANG</p>
          <P>Warna Favorit : HITAM</P>
          <p></p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="feature">
          <h2>FOTO PROFIL</h2>
          <img src="images/daffa1.jpeg" class="img-fluid mb-3" alt="Gambar Fitur 2">
          
        </div>
      </div>
      <div class="col-md-4">
        <div class="feature">
          <h2>DESKRIPSI PROFIL</h2>
          <img src="images/WhatsApp Image 2024-04-19 at 21.55.53.jpeg" class="img-fluid mb-3"
          <p>Ini adalah foto motor saya dan saya sangat suka memodifikasi motor sejak saat SMP</p>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-5">
    <button id="jadwalButton" class="btn btn-primary">
        Klik Di Sini Untuk Melihat Jadwal Kuliah
    </button>
    <p id="jadwalTagline" style="display: none;"></p>
    <ul id="jadwalList" style="display: none;">
        <div class="container mt-5">
            <div class="row">
        
              
                <div class="col-md-9">
                    <h1>Jadwal Kuliah</h1>
                    <div class="table-responsive mt-4">
                        <table class="table table-bordered">
                            <thead>
                                <tr>
                                    <th>Hari</th>
                                    <th>Jam</th>
                                    <th>Mata Kuliah</th>
                                    <th>Ruang</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>Senin</td>
                                    <td>08.00 - 10.00</td>
                                    <td>Pemrograman Web</td>
                                    <td>301</td>
                                </tr>
                                <tr>
                                    <td>Rabu</td>
                                    <td>10.00 - 12.00</td>
                                    <td>Basis Data</td>
                                    <td>203</td>
                                </tr>
                                <tr>
                                    <td>Jumat</td>
                                    <td>13.00 - 15.00</td>
                                    <td>Statistika</td>
                                    <td>102</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
       
        </body>
        </html>
  </div>

 
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

  
  <script>
    document.getElementById("jadwalButton").addEventListener("click", function() {
      document.getElementById("jadwalTagline").style.display = "block";
      document.getElementById("jadwalList").style.display = "block";
    });
  </script>
</body>
</html>

