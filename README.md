<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CV Maulana</title>

  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background: #e9ecef;
      margin: 0;
      padding: 0;
    }

    .cv {
      max-width: 850px;
      background: #ffffff;
      margin: 25px auto;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    }

    /* HEADER */
    .header {
      display: flex;
      gap: 25px;
      align-items: center;
      border-bottom: 3px solid #1f3c88;
      padding-bottom: 20px;
      flex-wrap: wrap;
    }

    .photo {
      width: 140px;
      height: 180px;
      border: 2px solid #000;
      object-fit: cover;
      background: #fff;
    }

    .title h1 {
      margin: 0;
      font-size: 28px;
      color: #1f3c88;
    }

    .title p {
      margin: 5px 0 0;
      font-size: 16px;
      color: #333;
    }

    /* SECTION */
    h2 {
      margin-top: 25px;
      font-size: 20px;
      color: #1f3c88;
      border-left: 5px solid #1f3c88;
      padding-left: 10px;
    }

    p, li {
      font-size: 15px;
      color: #333;
      line-height: 1.6;
    }

    ul {
      padding-left: 20px;
      margin-top: 8px;
    }

    /* RESPONSIVE HP */
    @media (max-width: 600px) {
      .header {
        justify-content: center;
        text-align: center;
      }
      .title h1 {
        font-size: 24px;
      }
    }
  </style>
</head>

<body>

<div class="cv">

  <!-- HEADER -->
  <div class="header">
    <img src="foto.jpg" alt="Foto Maulana" class="photo">
    <div class="title">
      <h1>Maulana</h1>
      <p>Siswa SMK | Teknik Komputer dan Jaringan (TKJ)</p>
    </div>
  </div>

  <!-- DATA DIRI -->
  <h2>Data Diri</h2>
  <p>
    Nama Lengkap : Maulana<br>
    Tempat, Tanggal Lahir : …………………<br>
    Jenis Kelamin : Laki-laki<br>
    Alamat : …………………<br>
    Status : Pelajar
  </p>

  <!-- PENDIDIKAN -->
  <h2>Pendidikan</h2>
  <p>
    SMK Negeri …………………<br>
    Jurusan Teknik Komputer dan Jaringan
  </p>

  <!-- KEAHLIAN -->
  <h2>Keahlian</h2>
  <ul>
    <li>Instalasi dan konfigurasi jaringan LAN</li>
    <li>Subnetting IP Address (FLSM & VLSM)</li>
    <li>Crimping kabel UTP dan troubleshooting jaringan</li>
    <li>Konfigurasi dasar router & switch Cisco</li>
    <li>Sistem Operasi Windows dan Linux dasar</li>
  </ul>

  <!-- PENGALAMAN -->
  <h2>Pengalaman</h2>
  <ul>
    <li>Praktik kerja jaringan LAN di lingkungan sekolah</li>
    <li>Simulasi jaringan menggunakan Cisco Packet Tracer</li>
    <li>Perencanaan dan perhitungan IP Address jaringan</li>
  </ul>

  <!-- KONTAK -->
  <h2>Kontak</h2>
  <p>
    Email : maulana@email.com<br>
    GitHub : https://github.com/username
  </p>

</div>

</body>
</html>
