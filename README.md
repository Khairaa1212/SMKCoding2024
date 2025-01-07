!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Halaman Perkenalan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            line-height: 1.6;
        }
        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 30px;
            text-align: center;
            max-width: 500px;
            width: 90%;
        }
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #3498db;
        }
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        .subtitle {
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        .contact {
            margin-top: 20px;
            color: #34495e;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="/api/placeholder/200/200" alt="Foto Profil" class="profile-img">
        <h1>Khaira</h1>
        <p class="subtitle">siswa</p>
        <p>Hai! Saya adalah seorang siswa dari smkn 1 balikpapan. saya berniat dan belajar tentang codingan dari smkcoding website</p>
        <div class="contact">
            <p>📧 khairasmk1bpn@gmail.com</p>
            <p>📱 +62 81649483834</p>
        </div>
    </div>
</body>
</html>
