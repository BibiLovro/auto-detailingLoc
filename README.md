# auto-detailingLoc<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <title>Auto Detailing</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            background-color: #111;
            color: white;
        }

        header {
            background: black;
            padding: 20px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
        }

        .hero {
            height: 400px;
            background: url('https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero h1 {
            background: rgba(0,0,0,0.6);
            padding: 20px;
        }

        .section {
            padding: 40px;
            text-align: center;
        }

        .services {
            display: flex;
            justify-content: space-around;
        }

        .box {
            background: #222;
            padding: 20px;
            width: 30%;
        }

        footer {
            background: black;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

<header>
    <h2>Auto Detailing</h2>
    <nav>
        <a href="#">Početna</a>
        <a href="#">Usluge</a>
        <a href="#">Kontakt</a>
    </nav>
</header>

<div class="hero">
    <h1>Profesionalni Auto Detailing</h1>
</div>

<div class="section">
    <h2>Naše usluge</h2>
    <div class="services">
        <div class="box">Vanjsko pranje</div>
        <div class="box">Poliranje</div>
        <div class="box">Keramika</div>
    </div>
</div>

<footer>
    <p>Kontakt: 099 123 456</p>
</footer>

</body>
</html>
