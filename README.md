<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            color: #333;
        }
        .project {
            display: flex;
            flex-wrap: wrap;
        }
        .project-item {
            flex: 1;
            padding: 10px;
            margin: 10px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Portfolio Saya</h1>
</header>

<div class="container">
    <div class="section" id="about">
        <h2>Tentang Saya</h2>
        <p>Halo, nama saya [Nama Anda]. Saya adalah seorang pengembang web dengan keahlian dalam HTML, CSS, dan JavaScript. Saya suka menciptakan solusi web yang menarik dan fungsional.</p>
    </div>

    <div class="section" id="projects">
        <h2>Proyek</h2>
        <div class="project">
            <div class="project-item">
                <h3>Proyek 1</h3>
                <p>Deskripsi singkat tentang proyek 1.</p>
            </div>
            <div class="project-item">
                <h3>Proyek 2</h3>
                <p>Deskripsi singkat tentang proyek 2.</p>
            </div>
            <div class="project-item">
                <h3>Proyek 3</h3>
                <p>Deskripsi singkat tentang proyek 3.</p>
            </div>
        </div>
    </div>

    <div class="section" id="contact">
        <h2>Kontak</h2>
        <p>Anda dapat menghubungi saya melalui email: <a href="mailto:email@example.com">email@example.com</a></p>
    </div>
</div>

<footer>
    &copy; 2024 Portfolio Saya
</footer>

</body>
</html>
