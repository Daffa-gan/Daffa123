# Daffa123

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Saya</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body{
            overflow-x: hidden;
            position: relative;
            width: 100%;
        }
        .custom-btn {
            padding: 12px 30px;
            border-radius: 30px;
        }
        .custom-btn:hover {
            background: #0e5bff ;
        }
        .section {
            padding: 80px 0;
        }
        .section-title {
            color: #0066ff;
            margin-bottom: 50px ;
        }
        .icons{
            font-size: 30px; margin: 0 10px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary fixed-top shadow-sm">
        <div class="container">
          <a class="navbar-brand fw-bold" style="color: #0066ff;" href="#home">Portofolio</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link mx-2" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#education">Education</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#find-me">FindMe</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#contact">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

    <!-- Hero Section -->
    <section id="home">
            <div class="p-5 text-center bg-body-tertiary">
              <div class="container py-5">
                <img src="me-removebg-preview.png" alt="Muhammad Daffa" width="300" class="rounded-circle">
                <h1 class="text-body-emphasis" style=" color: #0066ff !important;">Halo, semuanya</h1>
                <h1 class="text-body-emphasis" style=" color: #0066ff !important;">Perkenalkan nama saya Muhammad Daffa</h1>
                <p class="col-lg-8 mx-auto lead">
                    XI Tel 12
                </p>
                <p class="col-lg-8 mx-auto lead" style=" margin-top: 30px;">
                  Saya adalah seorang pelajar di SMK Telkom Jakarta dan jurusan saya adalah Rekayasa Perangkat Lunak
                </p>
              </div>
            </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section bg-light">
        <div class="container">
            <h2 class="text-center section-title">About Me</h2>
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="ratio ratio-16x9 shadow rounded">
                        <video 
                            class="w-100" 
                            controls
                            poster="thumbnail.jpg">
                            <source src="perkenalan.mp4" type="video/mp4">
                            Your browser does not support the video tag.
                        </video>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="section ">
        <div class="container">
            <h2 class="text-center section-title">Education & Experience</h2>
            
            <!-- Organizational Experience -->
            <div class="card shadow-sm mb-5">
                <div class="card-header bg-primary text-white">
                    <h4 class="mb-0">Organizational Experience</h4>
                </div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-hover">
                            <thead class="table-light">
                                <tr>
                                    <th>Tahun</th>
                                    <th>Peran/Posisi</th>
                                    <th>Deskripsi</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>2023 - Sekarang</td>
                                    <td>Ketua OSIS</td>
                                    <td>Memimpin dan mengoordinasikan kegiatan organisasi siswa, mengadakan berbagai event sekolah dan program pengembangan siswa.</td>
                                </tr>
                                <tr>
                                    <td>2022 - 2023</td>
                                    <td>Anggota Ekskul Robotik</td>
                                    <td>Berpartisipasi dalam kompetisi robotik tingkat provinsi, mengembangkan prototype robot edukasi.</td>
                                </tr>
                                <!-- Tambahkan baris sesuai pengalaman -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>

            <!-- Educational Background -->
            <div class="card shadow-sm">
                <div class="card-header bg-primary text-white">
                    <h4 class="mb-0">Educational Background</h4>
                </div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-hover">
                            <thead class="table-light">
                                <tr>
                                    <th>Sekolah</th>
                                    <th>Tahun</th>
                                    <th>Deskripsi</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>[Nama SMK]</td>
                                    <td>2021 - Sekarang</td>
                                    <td>Jurusan RPL dengan fokus pada pengembangan aplikasi web dan mobile. Aktif dalam berbagai proyek sekolah.</td>
                                </tr>
                                <tr>
                                    <td>[Nama SMP]</td>
                                    <td>2018 - 2021</td>
                                    <td>Aktif dalam kegiatan akademik dan non-akademik. Meraih peringkat 3 besar paralel.</td>
                                </tr>
                                <!-- Tambahkan baris sesuai riwayat pendidikan -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Find Me Section -->
    <section id="find-me" class="section">
        <div class="container text-center">
            <h2 class="section-title">Find Me</h2>
            <p>
                Email: your.email@example.com<br>
                Telepon: +62 xxx-xxxx-xxxx
            </p>
            <a href="https://wa.me/628111452297" target="_blank" class="icons"><i class="fa-brands fa-whatsapp"></i></a>
            <a href="#" target="_blank" class="icons"><i class="fa-brands fa-instagram"></i></a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2 class="text-center section-title">Contact Me</h2>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <form class="p-4 shadow-sm rounded bg-white">
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Your Email" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="4" placeholder="Your Message" style="resize: none;" required></textarea>
                        </div>
                        <button type="button" class="btn btn-primary w-100 custom-btn" id="liveToastBtn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>

        <!-- Toast -->
        <div class="toast-container position-fixed bottom-0 end-0 p-3">
            <div id="liveToast" class="toast" role="alert" aria-live="assertive" aria-atomic="true">
              <div class="toast-header">
                <strong class="me-auto" style="color: #60a5fa;">Notification</strong>
                <small>Now</small>
                <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
              </div>
              <div class="toast-body">
                Massage Sent Successfully
              </div>
            </div>
          </div>
    </section>

    <!-- Footer -->
    <div class="container">
        <hr>
        <footer class="py-3 my-4">
          <p class="text-center text-body-secondary">© 2024 Muhammad Daffa</p>
        </footer>
      </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/js/bootstrap.bundle.min.js"></script>
    <script src="https://kit.fontawesome.com/55e841a649.js" crossorigin="anonymous"></script>
    <script>
        const toastTrigger = document.getElementById('liveToastBtn')
        const toastLiveExample = document.getElementById('liveToast')

        if (toastTrigger) {
            const toastBootstrap = bootstrap.Toast.getOrCreateInstance(toastLiveExample)
            toastTrigger.addEventListener('click', () => {
                toastBootstrap.show()
            })
    }
    </script>
</body>
</html>
