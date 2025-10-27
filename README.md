## Codingan
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Layout Bootstrap Sederhana</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <header class="bg-primary text-white text-center p-3">
    <h1>Website Sederhana</h1>
    <p>Menggunakan CSS Framework - Bootstrap</p>
  </header>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Beranda</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Profil</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Galeri</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container mt-4">
    <div class="row">
      <div class="col-md-8">
        <h2>Fans pada kecewa?</h2>
        <img src="C:\Users\vitoa\Downloads\opm 1.jpg" alt="foto opm" width="350" >
        <p style="max-width: 550px; text-align: justify;">
          Masih banyak fans yang masih belom bisa move on dari one punch man season 1. Hal ini tidak mengagetkan karena bisa di lihat dari perbedaan gaya animasinya yang dimana di season satu one punch man di adaptasi oleh "MadHouse Studio" yang dimana di seaon 1 para fans dimanjakan oleh animasi dari pihak MadHouse studio. Berbanding terbalik di soason 2 one punch man mengalami kemunduran dalam animasinya. Banyak yang bilang perbedaan animasi season 1 dan season 2 bagaikan bumi dan langit. yang di mana season 2 dari anime one punch man di adaptasi oleh "J.C. STAFF".</p>
      </div>
      <div class="col-md-4">
        <h3>Ada Perkembangan animasi di season 3? </h3>
        <img src="C:\Users\vitoa\Downloads\opm 3.webp" alt="foto opm" width="350">
        <p style="max-width: 550px; text-align: justify;"
        >Setelah mendapatkan banyaknya komentar negatif tentang animasinya yang menurun nampaknya sekarang J.C. STAFF berbenah untuk mengupgrade gaya animasinya. Meskipun jika di bandingkan dengan season 2 kemaren sudah terlihat adanya perbedaan animasi meskipun posisi animenya masih on going nampaknya studio J.C. STAFF mulai menunjukan keseriuannya dalam menggarap anime ini. </p>
      </div>
    </div>
  </div>

  <footer class="bg-secondary text-white text-center p-3 mt-4">
    <p>&copy; 2025 Praktikum Web Framework</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## Penjelasan 
```
<!DOCTYPE html> → menandakan dokumen ini adalah HTML5.

<html lang="en"> → awal dokumen HTML dengan bahasa Inggris.

<head> → berisi informasi seperti judul, meta, dan link CSS/Bootstrap.

<meta charset="UTF-8"> → supaya semua karakter bisa tampil dengan benar.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> → agar tampilan web menyesuaikan ukuran layar HP.

<title> → judul yang muncul di tab browser.

<link href="...bootstrap.min.css"> → menghubungkan CSS Bootstrap dari internet.

<body> → tempat semua isi web yang ditampilkan di layar.

<header> → bagian atas halaman yang berisi judul dan deskripsi situs.

<nav> → membuat menu navigasi (beranda, profil, galeri, kontak).

<div class="container"> → wadah utama untuk mengatur tata letak konten agar rapi di tengah.

<div class="row"> → membuat satu baris layout untuk kolom-kolom di dalamnya.

<div class="col-md-8"> → kolom kiri (isi utama) dengan lebar 8 dari total 12 kolom.

<div class="col-md-4"> → kolom kanan (konten tambahan) dengan lebar 4 kolom.

<img> → menampilkan gambar dengan ukuran tertentu.

<p> → menampilkan paragraf teks.

<footer> → bagian bawah halaman berisi hak cipta atau catatan kecil.

<script src="...bootstrap.bundle.min.js"> → menambahkan file JavaScript Bootstrap agar fitur seperti tombol menu bisa berfungsi.
```

<img src="https://raw.githubusercontent.com/username/repository/main/images/foto.jpg" alt="Deskripsi gambar">



