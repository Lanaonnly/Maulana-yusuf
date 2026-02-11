
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Maulana Yusuf - XII TJKT 2</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: #161b22;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            border: 1px solid #30363d;
        }
        
        /* Header & Profile */
        .header {
            background: linear-gradient(135deg, #1f6feb 0%, #0d419d 100%);
            padding: 30px;
            text-align: center;
            position: relative;
        }
        
        .profile-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }
        
        @media (min-width: 768px) {
            .profile-container {
                flex-direction: row;
                text-align: left;
                gap: 30px;
            }
        }
        
        .profile-img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid #30363d;
            object-fit: cover;
            background-color: #0d1117;
            padding: 5px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }
        
        .profile-text h1 {
            font-size: 2.2rem;
            margin-bottom: 5px;
            color: white;
        }
        
        .profile-text h2 {
            font-size: 1.3rem;
            color: #8b949e;
            margin-bottom: 15px;
            font-weight: normal;
        }
        
        .tag {
            display: inline-block;
            background-color: #238636;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            margin-right: 10px;
            margin-bottom: 10px;
        }
        
        /* Content Layout */
        .content {
            display: grid;
            grid-template-columns: 1fr;
            gap: 30px;
            padding: 30px;
        }
        
        @media (min-width: 992px) {
            .content {
                grid-template-columns: 2fr 1fr;
            }
        }
        
        /* Sections */
        .section {
            margin-bottom: 25px;
        }
        
        .section-title {
            color: #58a6ff;
            font-size: 1.5rem;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #30363d;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section-title i {
            font-size: 1.3rem;
        }
        
        /* About Section */
        .about-text {
            background-color: #21262d;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #1f6feb;
        }
        
        /* Experience & Education */
        .timeline-item {
            margin-bottom: 20px;
            padding-left: 20px;
            border-left: 2px solid #30363d;
            position: relative;
        }
        
        .timeline-item:before {
            content: "";
            position: absolute;
            left: -7px;
            top: 0;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background-color: #1f6feb;
        }
        
        .timeline-item h3 {
            color: #c9d1d9;
            font-size: 1.1rem;
            margin-bottom: 5px;
        }
        
        .timeline-item .date {
            color: #8b949e;
            font-size: 0.9rem;
            margin-bottom: 8px;
            display: block;
        }
        
        /* Skills */
        .skill-item {
            margin-bottom: 15px;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .skill-bar {
            height: 10px;
            background-color: #30363d;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .skill-level {
            height: 100%;
            background-color: #238636;
            border-radius: 5px;
        }
        
        /* Contact Info */
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            gap: 12px;
        }
        
        .contact-item i {
            color: #58a6ff;
            width: 20px;
        }
        
        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #0d1117;
            border-top: 1px solid #30363d;
            color: #8b949e;
            font-size: 0.9rem;
        }
        
        .github-link {
            color: #58a6ff;
            text-decoration: none;
            margin-top: 10px;
            display: inline-block;
        }
        
        .github-link:hover {
            text-decoration: underline;
        }
        
        /* GitHub Stats */
        .github-stats {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin-top: 20px;
        }
        
        .stat-box {
            background-color: #21262d;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            border: 1px solid #30363d;
        }
        
        .stat-number {
            font-size: 1.8rem;
            font-weight: bold;
            color: #58a6ff;
            display: block;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #8b949e;
        }
        
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .header {
                padding: 20px;
            }
            
            .content {
                padding: 20px;
            }
            
            .github-stats {
                grid-template-columns: 1fr;
            }
        }
        
        /* Photo placeholder styling */
        .photo-placeholder {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid #30363d;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #0d1117;
            color: #8b949e;
            text-align: center;
            padding: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }
        
        .photo-placeholder i {
            font-size: 3rem;
            margin-bottom: 10px;
            color: #30363d;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <header class="header">
            <div class="profile-container">
                <!-- Photo placeholder - replace with actual photo -->
                <div class="photo-placeholder">
                    <i class="fas fa-user-circle"></i>
                    <span>Foto <img src="IMG_20250507_134840.jpg"></span>
        
                </div>
                
                <!-- Profile Text -->
                <div class="profile-text">
                    <h1>Maulana Yusuf</h1>
                    <h2>Pelajar TJKT | XII TJKT 2</h2>
                    <p>Seorang pelajar Teknik Jaringan Komputer dan Telekomunikasi yang bersemangat dalam pengembangan jaringan, pemrograman, dan teknologi terkini. Aktif dalam ekstrakurikuler IT dan pengembangan proyek jaringan.</p>
                    
                    <div class="tags">
                        <span class="tag">Jaringan Komputer</span>
                        <span class="tag">SysAdmin</span>
                        <span class="tag">Cybersecurity</span>
                        <span class="tag">Web Development</span>
                    </div>
                </div>
            </div>
        </header>
        
        <!-- Main Content -->
        <div class="content">
            <!-- Left Column -->
            <div class="left-column">
                <!-- About Me -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-user"></i> Tentang Saya</h2>
                    <div class="about-text">
                        <p>Saya adalah siswa kelas XII TJKT 2 dengan minat kuat di bidang jaringan komputer, administrasi sistem, dan keamanan siber. Memiliki pengalaman praktik dalam konfigurasi router, switch, dan troubleshooting jaringan.</p>
                        <p>Selain fokus pada studi, saya juga aktif dalam ekskul IT dan sering berpartisipasi dalam workshop teknologi. Saya tertarik dengan perkembangan dunia IT dan selalu berusaha mengikuti tren terbaru.</p>
                    </div>
                </section>
                
                <!-- Experience -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-briefcase"></i> Pengalaman</h2>
                    
                    <div class="timeline-item">
                        <h3>Praktik Kerja Lapangan - PT. Jaringan Indonesia</h3>
                        <span class="date">Januari 2024 - Maret 2024</span>
                        <p>Membantu tim IT dalam maintenance jaringan, konfigurasi perangkat jaringan, dan monitoring koneksi internet perusahaan.</p>
                    </div>
                    
                    <div class="timeline-item">
                        <h3>Asisten Lab Komputer Sekolah</h3>
                        <span class="date">Agustus 2023 - Sekarang</span>
                        <p>Bertanggung jawab atas maintenance komputer lab, troubleshooting hardware/software, dan membantu persiapan praktikum jaringan.</p>
                    </div>
                    
                    <div class="timeline-item">
                        <h3>Peserta Workshop Keamanan Jaringan</h3>
                        <span class="date">Oktober 2023</span>
                        <p>Mengikuti workshop selama 3 hari tentang dasar-dasar keamanan jaringan dan teknik pengamanan sistem.</p>
                    </div>
                </section>
                
                <!-- Education -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-graduation-cap"></i> Pendidikan</h2>
                    
                    <div class="timeline-item">
                        <h3>SMK Negeri 1 Teknologi</h3>
                        <span class="date">2022 - Sekarang</span>
                        <p>Jurusan Teknik Jaringan Komputer dan Telekomunikasi (TJKT)</p>
                        <p>Konsentrasi: Administrasi Infrastruktur Jaringan</p>
                    </div>
                    
                    <div class="timeline-item">
                        <h3>SMP Negeri 5 Digital</h3>
                        <span class="date">2019 - 2022</span>
                        <p>Jurusan Umum dengan minat khusus di bidang Teknologi Informasi</p>
                    </div>
                </section>
            </div>
            
            <!-- Right Column -->
            <div class="right-column">
                <!-- Contact -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-address-book"></i> Kontak</h2>
                    
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <span>maulanayusuf@example.edu</span>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <span>+62 812 3456 7890</span>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Kota Teknologi, Jawa Barat</span>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fab fa-github"></i>
                        <span>github.com/maulanayusuf</span>
                    </div>
                    
                    <div class="contact-item">
                        <i class="fab fa-instagram"></i>
                        <span>@maulanayusuf.tjkt</span>
                    </div>
                </section>
                
                <!-- Skills -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-code"></i> Keahlian Teknis</h2>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Jaringan Komputer</span>
                            <span>85%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 85%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Konfigurasi Router & Switch</span>
                            <span>80%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 80%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Administrasi Sistem</span>
                            <span>75%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 75%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>HTML/CSS</span>
                            <span>70%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 70%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Keamanan Jaringan</span>
                            <span>65%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 65%"></div>
                        </div>
                    </div>
                </section>
                
                <!-- GitHub Stats -->
                <section class="section">
                    <h2 class="section-title"><i class="fab fa-github"></i> Statistik GitHub</h2>
                    
                    <div class="github-stats">
                        <div class="stat-box">
                            <span class="stat-number">24</span>
                            <span class="stat-label">Repositori</span>
                        </div>
                        
                        <div class="stat-box">
                            <span class="stat-number">156</span>
                            <span class="stat-label">Commit</span>
                        </div>
                        
                        <div class="stat-box">
                            <span class="stat-number">12</span>
                            <span class="stat-label">Proyek</span>
                        </div>
                        
                        <div class="stat-box">
                            <span class="stat-number">3</span>
                            <span class="stat-label">Kontribusi</span>
                        </div>
                    </div>
                </section>
                
                <!-- Interests -->
                <section class="section">
                    <h2 class="section-title"><i class="fas fa-star"></i> Minat</h2>
                    
                    <div class="tags">
                        <span class="tag">Networking</span>
                        <span class="tag">Cybersecurity</span>
                        <span class="tag">Game Development</span>
                        <span class="tag">IoT</span>
                        <span class="tag">Cloud Computing</span>
                    </div>
                </section>
            </div>
        </div>
        
        <!-- Footer -->
        <footer class="footer">
            <p>CV Maulana Yusuf - XII TJKT 2 | Tema GitHub</p>
            <p>Terakhir diperbarui: Juni 2024</p>
            <a href="https://github.com/maulanayusuf" class="github-link" target="_blank">
                <i class="fab fa-github"></i> Kunjungi Profil GitHub Saya
            </a>
        </footer>
    </div>
    
    <script>
        // Simple animation for skill bars on page load
        document.addEventListener('DOMContentLoaded', function() {
            const skillBars = document.querySelectorAll('.skill-level');
            
            skillBars.forEach(bar => {
                const width = bar.style.width;
                bar.style.width = '0';
                
                setTimeout(() => {
                    bar.style.transition = 'width 1.5s ease-in-out';
                    bar.style.width = width;
                }, 300);
            });
            
            // Update current year in footer
            const currentYear = new Date().getFullYear();
            document.querySelector('.footer p:last-of-type').innerHTML = `Terakhir diperbarui: Juni ${currentYear}`;
        });
    </script>
</body>
</html>
