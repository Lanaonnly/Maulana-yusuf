<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Curriculum Vitae</title>

<style>
body{
    margin:0;
    font-family: Arial, Helvetica, sans-serif;
    background:#f2f4f7;
}

.cv{
    max-width:900px;
    margin:30px auto;
    background:#fff;
    box-shadow:0 8px 25px rgba(0,0,0,0.1);
    border-radius:10px;
    overflow:hidden;
}

/* HEADER */
.header{
    background:#1f4fd8;
    color:white;
    padding:30px;
    display:flex;
    align-items:center;
    gap:25px;
}

.header img{
    width:140px;
    height:140px;
    border-radius:50%;
    border:5px solid #fff;
    object-fit:cover;
}

.header h1{
    margin:0;
    font-size:30px;
}

.header p{
    margin:5px 0 0;
    font-size:16px;
}

/* CONTENT */
.content{
    padding:30px;
}

.section{
    margin-bottom:25px;
}

.section h2{
    color:#1f4fd8;
    border-bottom:2px solid #1f4fd8;
    padding-bottom:5px;
    margin-bottom:10px;
}

.section p, .section li{
    font-size:15px;
    line-height:1.7;
}

ul{
    padding-left:20px;
}

/* GRID */
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:15px;
}

.box{
    background:#f6f8fc;
    padding:12px;
    border-radius:8px;
}
</style>
</head>

<body>

<div class="cv">

    <!-- HEADER + FOTO -->
    <div class="header">
        <img src="data:image/20251219_091344.jpg
" alt="Foto CV">
        <div>
            <h1>NAMA LENGKAP</h1>
            <p>Siswa SMK | Teknik Komputer dan Jaringan</p>
        </div>
    </div>

    <!-- ISI -->
    <div class="content">

        <div class="section">
            <h2>Profil Singkat</h2>
            <p>
                Saya adalah siswa SMK jurusan Teknik Komputer dan Jaringan yang
                memiliki motivasi tinggi untuk belajar dan bekerja. Terbiasa
                bekerja dengan disiplin, bertanggung jawab, serta mampu
                bekerja secara individu maupun tim. Memiliki minat di bidang
                IT, jaringan komputer, dan teknologi.
            </p>
        </div>

        <div class="section">
            <h2>Data Pribadi</h2>
            <div class="grid">
                <div class="box">👤 Nama: Nama Lengkap</div>
                <div class="box">🎂 Tempat/Tgl Lahir: -</div>
                <div class="box">👨‍🎓 Status: Pelajar SMK</div>
                <div class="box">📍 Alamat: Indonesia</div>
                <div class="box">🕌 Agama: Islam</div>
                <div class="box">🇮🇩 Kewarganegaraan: Indonesia</div>
            </div>
        </div>

        <div class="section">
            <h2>Pendidikan</h2>
            <ul>
                <li><b>SMK</b> – Teknik Komputer dan Jaringan (2023–Sekarang)</li>
                <li>SMP Negeri</li>
                <li>SD Negeri</li>
            </ul>
        </div>

        <div class="section">
            <h2>Pengalaman & Kegiatan</h2>
            <ul>
                <li>Praktik instalasi jaringan LAN dan troubleshooting</li>
                <li>Perakitan dan perawatan komputer</li>
                <li>Membuat website sederhana menggunakan HTML & CSS</li>
                <li>Mengerjakan tugas kelompok dan proyek sekolah</li>
            </ul>
        </div>

        <div class="section">
            <h2>Keahlian</h2>
            <ul>
                <li>Instalasi Jaringan LAN</li>
                <li>Perakitan Komputer</li>
                <li>HTML & CSS Dasar</li>
                <li>Microsoft Word, Excel</li>
                <li>Canva Dasar</li>
            </ul>
        </div>

        <div class="section">
            <h2>Karakter & Kelebihan</h2>
            <ul>
                <li>Disiplin dan jujur</li>
                <li>Cepat belajar</li>
                <li>Bertanggung jawab</li>
                <li>Mampu bekerja dalam tim</li>
            </ul>
        </div>

        <div class="section">
            <h2>Kontak</h2>
            <p>📞 No HP: 08xxxxxxxxxx</p>
            <p>✉️ Email: email@gmail.com</p>
            <p>💻 GitHub: github.com/username</p>
        </div>

        <div class="section">
            <h2>Pernyataan</h2>
            <p>
                Dengan ini saya menyatakan bahwa seluruh data yang saya
                sampaikan adalah benar. Saya siap dipanggil untuk tahapan
                selanjutnya.
            </p>
            <p><b>Hormat saya,</b><br>Nama Lengkap</p>
        </div>

    </div>

</div>

</body>
</html>
