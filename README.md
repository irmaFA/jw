
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Materi Sistem Persamaan Linear Dua Variabel</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Mengatur desain global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            justify-content: space-between;
        }

        /* Mengatur lebar konten utama */
        .container {
            max-width: 1200px;
            width: 100%;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 26px;
            color: #1757fa;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }

        /* Section konten utama */
        h2 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #111111;
            border-bottom: 2px solid #a05c04e7;
            padding-bottom: 5px;
        }

        h3 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #2c1c07e7;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 15px;
            text-align: justify;
            color: #000000;
        }

        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }

        li {
            font-size: 16px;
            margin-bottom: 8px;
            color: #000000;
        }

        /* Responsif untuk tampilan mobile */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 22px;
            }

            h2 {
                font-size: 18px;
            }

            h3 {
                font-size: 16px;
            }

            p, li {
                font-size: 14px;
            }

            .container {
                padding: 10px;
            }

            iframe {
                min-height: 200px;
            }
        }

        /* Responsif untuk iframe video */
        iframe {
            max-width: 100%;
            height: auto;
            border: 0;
            border-radius: 8px;
        }

        /* Footer diatur dengan flexbox agar selalu di tengah halaman */
        footer {
            text-align: center;
            margin: 20px auto;
            font-size: 14px;
            color: #000;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-shrink: 0;
        }

        /* Navbar Responsif */
        .navbar-nav {
            display: flex;
            justify-content: center;
        }

        .navbar-nav .nav-item {
            padding: 10px 15px;
        }

        /* Memperbaiki tampilan kontainer dalam berbagai ukuran layar */
        .container-fluid {
            padding: 0 20px;
        }

        /* Meningkatkan keselarasan pada tampilan konten */
        .steps ol, .example p {
            margin-left: 20px;
        }

        /* Penataan untuk Card */
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }

        .card-body {
            padding: 20px;
        }

        .card-title {
            font-size: 18px;
            font-weight: bold;
            color: #333;
        }

        .card-text {
            font-size: 16px;
            color: #555;
        }

        .btn {
            background-color: #4CAF50;
            color: white;
            border: none;
        }

        /* Mengatur jarak antara konten */
        .row {
            gap: 20px;
        }

    </style>
</head>

<body>

  <!-- Content Section -->
<div class="container my-5">
    <div class="row">
        <!-- Materi Pembelajaran Card -->
        <div class="col-lg-3 col-md-4 mb-4"> <!-- Smaller columns -->
            <div class="card h-100">
                <img src="home1.jpg" class="card-img-top" alt="Materi Image" style="max-height: 150px; object-fit: cover;" /> <!-- Smaller image -->
                <div class="card-body p-3"> <!-- Reduced padding -->
                    <h5 class="card-title">Sistem Persamaan Linear Dua Variabel</h5>
                    <ul class="card-text">
                        <li>Konsep Persamaan Linear Dua Variabel</li>
                        <li>System Persamaan Linear Dua Variabel</li>
                        <li>Penyelesaian System Persamaan Linear Dua Variabel</li>
                    </ul>
                    <a href="materi.html" class="btn btn-primary">Lihat Materi</a>
                </div>
            </div>
        </div>

        <!-- Quiz Interaktif Card -->
        <div class="col-lg-3 col-md-4 mb-4"> <!-- Smaller columns -->
            <div class="card h-100">
                <img src="home3.png" class="card-img-top" alt="Quiz Image" style="max-height: 150px; object-fit: cover;" /> <!-- Smaller image -->
                <div class="card-body p-3"> <!-- Reduced padding -->
                    <h5 class="card-title">Media Pembelajaran</h5>
                    <p class="card-text">Uji kemampuanmu dengan serangkaian kuis interaktif yang seru dan menantang! Setiap pertanyaan dirancang khusus untuk membantumu semakin jago dan percaya diri dalam memahami materi.</p>
                </div>
            </div>
        </div>

        <!-- Fitur Lain Card -->
        <div class="col-lg-3 col-md-4 mb-4"> <!-- Smaller columns -->
            <div class="card h-100">
                <img src="latihan.png" class="card-img-top" alt="Fitur Image" style="max-height: 150px; object-fit: cover;" /> <!-- Smaller image -->
                <div class="card-body p-3"> <!-- Reduced padding -->
                    <h5 class="card-title">Latihan</h5>
                    <p class="card-text">Kami menyediakan fitur-fitur tambahan seperti video tutorial, diskusi online, dan banyak lagi untuk mendukung proses belajar Anda.</p>
                    <a href="kuis.html" class="btn btn-primary">Mulai Kuis</a>
                </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-B4gt1jrGC7Jh4AgR6a3gtE8z7s6jsl2kwFfD3tKZolTl08jYRTfzzRPzW5Yf3BnlN" crossorigin="anonymous"></script>
</body>

</html>

