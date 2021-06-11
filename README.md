# Location-share
# USE HTML CSS RESPONSIVE



Cara membagikan Lokasi Alamat tempat kita di Website Dengan HTML DAN CSS.

1. Pertama buka dahulu situs Google Maps di  website ini http://maps.google.com, setelah itu masukan alamat perusahaan anda lihat tanda panah merah pada gambar dibawah ini. Bila sudah, google akan mengarahkan pointer pada peta sesuai alamat yang Anda buat. Jika Anda merasa sudah benar, tinggal melanjutkan ke langkah berikutnya.

2. Ambil kode alamat yang dibuat google maps. Caranya klik menu Bagikan. Setelah itu klik Tab "Sematkan Peta" (tanda panah gambar di bawah ini). Bila sudah, copy code yang ada (yang dilingkari merah pada gambar).

3. Selanjutnya, memasukkan peta ke dalam website Anda. Caranya  Paste  pada kode html halaman website yang Anda inginkan, misanya di halaman kontak.html. Buka file kontak.html web Anda, lalu paste kode yang kita copy dari google maps diantara tag body  seperti contoh di bawah ini:


  <!doctype html>
<html>
<head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title>Kontak Kami</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link rel="apple-touch-icon" href="img/apple-touch-icon.png">
		<link rel="shortcut icon" type="image/x-icon" href="img/icon/favicon.ico">
        <!-- Place favicon.ico in the root directory -->		
		<!-- all css here -->
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="css/responsive.css">
        <script src="js/vendor/modernizr-2.8.3.min.js"></script>
    </head>
    <body>
      <!-- google maps -->
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1991.5705267458372!2d114.57444712927017!3d-3.3152044552689253!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2de423d48a3dc841%3A0x1821d6c60c5a9a48!2sJasa+Pembuatan+Website+Banjarmasin!5e0!3m2!1sid!2sid!4v1527727490692" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
    
  </body>
  </html>
  
  Jika sudah maka peta alamat Anda akan tampil di website Anda. Demikian tutorial cara mudah memasukkan google maps ke dalam website, semoga bermanfaat.

