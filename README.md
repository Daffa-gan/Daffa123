<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Portofolio saya</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-white fixed-top shadow-sm">
        <div class="container">
          <a class="navbar-brand fw-bold text-primary" href="#home">Portofolio</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link mx-2" aria-current="page" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#education">Education</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#find-me">Find Me</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-2" href="#contact">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>


      <!-- Hero -->
      <section id="home" class="pt-5 mt-5 bg-light">
      <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="me-removebg-preview.png" class="d-block mx-lg-auto img-fluid rounded-circle bg-primary" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">Muhammad Daffa Ramadansyah Alfahidi</h1>
            <p class="lead">XI Tel 12</p>
            <p class="lead">Saya adalah seorang pelajar di SMK Telkom Jakarta dan jurusan saya adalah Rekayasa Perangkat Lunak.</p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-start">
              <a type="button" class="btn btn-primary btn-lg px-4 me-md-2" fdprocessedid="6xcd1" href="#contact">Contact</a>
            </div>
          </div>
        </div>
      </div>
      </section>

      <!-- About -->
       <section id="about" class="py-5 mt-5">
        <div class="container">
            <h2 class="text-primary text-center mb-5">About me</h2>
            <div class="row justify-content-center">
                <div class="col-md-8">
                        <video class="w-100" controls poster="thumbnail.jpg">
                            <source src="perkenalan.mp4" type="video/mp4">
                        </video>
                </div>
            </div>
        </div>
        </section>

        <!-- Education -->
        <section id="education" class="bg-light mt-5 py-5">
          <div class="container">
              <h2 class="text-primary text-center mb-5">Education & Experience</h2>

              <!-- Organization Experience -->
              <div class="card mb-5 shadow-sm">
                  <div class="card-header bg-primary text-white">
                      <h4 class="mb-0">Organizational Experience</h4>
                  </div>
                  <div class="card-body">
                      <table class="table table-hover">
                          <thead class="table-light">
                              <tr>
                                  <th>#</th>
                                  <th>First</th>
                                  <th>Last</th>
                              </tr>
                          </thead>
                          <tbody>
                              <tr>
                                  <td>1</td>
                                  <td>Mark</td>
                                  <td>Otto</td>
                              </tr>
                              <tr>
                                  <td>2</td>
                                  <td>Jacob</td>
                                  <td>Thornton</td>
                              </tr>
                              <tr>
                                  <td>3</td>
                                  <td>Larry the Bird</td>
                                  <td>memimpin dan mengoordinasikan kegiatan organisasi siswa, mengadakan berbagai event sekolah dan program pengembangan siswa.</td>
                              </tr>
                          </tbody>
                      </table>
                  </div>
              </div>

              <!-- Educational Background -->
              <div class="card shadow-sm">
                  <div class="card-header bg-primary text-white">
                      <h4 class="mb-0">Educational Background</h4>
                  </div>
                  <div class="card-body">
                      <table class="table table-hover">
                          <thead class="table-light">
                              <tr>
                                  <th>#</th>
                                  <th>First</th>
                                  <th>Last</th>
                              </tr>
                          </thead>
                          <tbody>
                              <tr>
                                  <td>1</td>
                                  <td>Mark</td>
                                  <td>Otto</td>
                              </tr>
                              <tr>
                                  <td>2</td>
                                  <td>Jacob</td>
                                  <td>Thornton</td>
                              </tr>
                              <tr>
                                  <td>3</td>
                                  <td>Larry the Bird</td>
                                  <td>Bejat</td>
                              </tr>
                          </tbody>
                      </table>
                  </div>
              </div>
          </div>
        </section>

        <!-- Find me -->
        <section id="find-me" class="py-5 mt-5 text-center">
            <div class="container">
                <h2 class="text-primary mb-5">Find Me</h2>
                <p class="mb-4">
                    Email: muhammaddaffa2209206@gmail.com<br>
                    Telepon: 08111452297
                </p>
                <div class="justify-content-center d-flex gap-4">
                    <a href="#" target="_blank" class="fs-3">
                        <i class="fa-brands fa-whatsapp"></i>
                    </a>
                    <a href="#" target="_blank" class="fs-3">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                </div>
            </div>
        </section>

        <!-- Contact -->
         <section id="contact" class="bg-light mt-5 py-5">
            <div class="container">
                <h2 class="mb-0 text-primary text-center mb-5">Contact me</h2>
                    <div class="row justify-content-center">
                        <div class="col-md-6">
                            <div class="form-floating mb-3">
                                <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                                <label for="floatingInput">Email address</label>
                            </div>
                            <div class="form-floating mb-3">
                                <input type="text" class="form-control" id="floatingName" placeholder="Name">
                                <label for="floatingPassword">Your name</label>
                            </div>
                            <div class="form-floating mb-3">
                                <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px; resize: none;"></textarea>
                                <label for="floatingTextarea2">Comments</label>
                            </div>
                            <button type="submit" class="btn btn-primary w-100 rounded-pill" id="Submit">Submit</button>
                        </div>
                    </div>
                </div>
         </section>

         <!-- Toast -->
         <div class="toast-container position-fixed bottom-0 end-0 p-3">
            <div id="liveToast" class="toast" role="alert" aria-live="assertive" aria-atomic="true">
              <div class="toast-header">
                <strong class="me-auto text-primary">Notification</strong>
                <small>Now</small>
                <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
              </div>
              <div class="toast-body">
                Massage Sent Successfully
              </div>
            </div>
          </div>

          <!-- Footer -->
          <div class="container">
            <hr>
            <footer class="py-3 my-4">
              <p class="text-center text-body-secondary">© 2024 Muhammad Daffa</p>
            </footer>
          </div>

      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
      <script src="https://kit.fontawesome.com/55e841a649.js" crossorigin="anonymous"></script>
      <script>
      const toastTrigger = document.getElementById('Submit')
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
