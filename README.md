<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curriculum Vitae - Maulana</title>

  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #e6e6e6;
      margin: 0;
      padding: 0;
    }

    .cv {
      max-width: 900px;
      background: #ffffff;
      margin: 30px auto;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }

    .header {
      display: flex;
      gap: 25px;
      align-items: center;
      border-bottom: 3px solid #000;
      padding-bottom: 20px;
      flex-wrap: wrap;
    }

    .photo {
      width: 150px;
      height: 190px;
      border: 2px solid #000;
      object-fit: cover;
      background: #fff;
    }

    .header-text h1 {
      margin: 0;
      font-size: 30px;
      text-transform: uppercase;
    }

    .header-text p {
      margin: 5px 0 0;
      font-size: 16px;
    }

    h2 {
      margin-top: 25px;
      font-size: 20px;
      border-bottom: 2px solid #000;
      padding-bottom: 5px;
    }

    p, li {
      font-size: 15px;
      line-height: 1.6;
    }

    ul {
      padding-left: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }

    table td {
      padding: 6px;
      vertical-align: top;
    }

    @media (max-width: 600px) {
      .header {
        justify-content: center;
        text-align: center;
      }
    }
  </style>
</head>

<body>

<div class="cv">

  <!-- HEADER -->
  <div class="header">
    <img src="foto.jpg" alt="Foto Maulana" class="photo">
    <div class="header-text">
      <h1>Maulana</h1>
      <p>Siswa SMK – Teknik Komputer dan Jaringan</p>
    </div>
  </div>

  <!-- DATA PRIBADI -->
  <h2>Data Pribadi</h2>
  <table>
    <tr><td>Nama Lengkap</td><td>: Maulana</td></tr>
    <tr><td>Tempat, Tanggal Lahir</td><td>: lebak 27 oktober 2008</td></tr>
    <tr><td>Jenis Kelamin</td><td>: Laki-laki</td></tr>
    <tr><td>Agama</td><td>: islam</td></tr>
    <tr><td>Alamat</td><td>: kp.parage</td></tr>
    <tr><td>No. HP</td><td>: 083872161233</td></tr>
    <tr><td>Email</td><td>: maulana@email.com</td></tr>
  </table>

  <!-- PROFIL SINGKAT -->
  <h2>Profil Singkat</h2>
  <p>
    Saya adalah siswa SMK jurusan Teknik Komputer dan Jaringan yang memiliki
    minat di bidang jaringan komputer dan IT support. Terbiasa bekerja dengan
    perangkat jaringan, disiplin, dan siap belajar hal baru.
  </p>

  <!-- PENDIDIKAN -->
  <h2>Pendidikan</h2>
  <ul>
    <li>
      SMK Negeri 1 Rangkasbitung<br>
      Jurusan Teknik Komputer dan Jaringan (TKJ)
    </li>
  </ul>

  <!-- KEAHLIAN -->
  <h2>Keahlian</h2>
  <ul>
    <li>Instalasi dan konfigurasi jaringan LAN</li>
    <li>Perhitungan subnetting (FLSM & VLSM)</li>
    <li>Crimping kabel UTP dan pengecekan jaringan</li>
    <li>Konfigurasi dasar router dan switch Cisco</li>
    <li>Instalasi Windows dan Linux dasar</li>
  </ul>

  <!-- PENGALAMAN -->
  <h2>Pengalaman</h2>
  <ul>
    <li>Praktik kerja jaringan LAN di lingkungan sekolah</li>
    <li>Simulasi jaringan menggunakan Cisco Packet Tracer</li>
    <li>Perencanaan IP Address dan topologi jaringan</li>
  </ul>

  <!-- SERTIFIKAT -->
  <h2>Tempat PKL/h2>
  <ul>
    <li>Krakatau Sarana properti</li>
  </ul>

  <!-- HOBI -->
  <h2>Hobi</h2>
  <ul>
    <li>Belajar teknologi jaringan</li>
    <li>Membaca dan eksplorasi IT</li>
  </ul>

  <!-- PENUTUP -->
  <h2>Pernyataan</h2>
  <p>
    Saya menyatakan bahwa data yang saya tuliskan di atas adalah benar dan dapat
    dipertanggungjawabkan.
  </p>

</div>

</body>
</html>
