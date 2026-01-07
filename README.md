<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PresiDent | Medicinske uniforme</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f8fb;
            color: #333;
        }
        header {
            background: #0d6efd;
            color: white;
            padding: 20px 40px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        .logo svg {
            width: 50px;
            height: 50px;
            fill: white;
        }
        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: white;
        }
        .hero h1 {
            font-size: 42px;
            margin-bottom: 15px;
        }
        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 30px;
        }
        .btn {
            background: #0d6efd;
            color: white;
            padding: 14px 28px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 16px;
        }
        .section {
            padding: 60px 40px;
            max-width: 1100px;
            margin: auto;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            text-align: center;
        }
        footer {
            background: #0d6efd;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">
        <!-- Logo zuba (SVG) -->
        <svg viewBox="0 0 64 64">
            <path d="M32 2C20 2 10 10 10 22c0 10 6 18 6 28 0 6 4 10 8 10 4 0 6-4 6-8 0-4 2-6 2-6s2 2 2 6c0 4 2 8 6 8 4 0 8-4 8-10 0-10 6-18 6-28C54 10 44 2 32 2z"/>
        </svg>
        <h2>PresiDent</h2>
    </div>
    <nav>
        <a href="#">Početna</a>
        <a href="#">Uniforme</a>
        <a href="#">O nama</a>
        <a href="#">Kontakt</a>
    </nav>
</header>

<section class="hero">
    <h1>Medicinske uniforme vrhunskog kvaliteta</h1>
    <p>
        PresiDent nudi moderne, udobne i izdržljive medicinske uniforme
        namijenjene doktorima, stomatolozima i medicinskom osoblju.
    </p>
    <a href="#" class="btn">Pogledaj ponudu</a>
</section>

<section class="section">
    <div class="cards">
        <div class="card">
            <h3>Premium materijali</h3>
            <p>Prozračne tkanine, lako održavanje i dug vijek trajanja.</p>
        </div>
        <div class="card">
            <h3>Moderan dizajn</h3>
            <p>Profesionalan izgled prilagođen savremenim ordinacijama.</p>
        </div>
        <div class="card">
            <h3>Za dentalne timove</h3>
            <p>Posebno dizajnirano za stomatologe i dentalne asistente.</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2026 PresiDent – Medicinske uniforme</p>
</footer>

</body>
</html>
