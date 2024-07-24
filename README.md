# Pensiunea-Carla
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pensiunea Carla - Poiana mărului</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #6db3f2;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #4a90e2;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .activities, .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin: 10px;
            padding: 20px;
            width: 30%;
        }
        .card img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #6db3f2;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pensiunea Carla</h1>
        <p>Poiana mărului</p>
    </header>
    <nav>
        <a href="#about">Despre noi</a>
        <a href="#activities">Activități</a>
        <a href="#services">Servicii</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>Despre noi</h2>
            <p>Bine ați venit la Pensiunea Carla, situată pe marginea unui lac superb, unde vă puteți bucura de natură și relaxare. Oferim cazare confortabilă și o varietate de activități pentru a vă asigura că aveți o vacanță de neuitat.</p>
        </section>
        <section id="activities" class="activities">
            <h2>Activități</h2>
            <div class="card">
                <img src="atv.jpg" alt="Mersul cu ATV-ul">
                <h3>Mersul cu ATV-ul</h3>
                <p>Explorați împrejurimile cu ATV-urile noastre moderne și bucurați-vă de aventură în natură.</p>
            </div>
            <div class="card">
                <img src="barca.jpg" alt="Barca cu pedale">
                <h3>Barca cu pedale</h3>
                <p>Bucurați-vă de o plimbare relaxantă cu barca cu pedale pe lacul nostru minunat.</p>
            </div>
            <div class="card">
                <img src="loc_de_joaca.jpg" alt="Loc de joacă pentru copii">
                <h3>Loc de joacă pentru copii</h3>
                <p>Copiii dvs. se pot distra în siguranță în locul nostru de joacă amenajat în grădina pensiunii.</p>
            </div>
        </section>
        <section id="services" class="services">
            <h2>Servicii</h2>
            <div class="card">
                <img src="restaurant.jpg" alt="Servicii de luat masa">
                <h3>Servicii de luat masa</h3>
                <p>Bucurați-vă de preparate delicioase în restaurantul nostru confortabil.</p>
            </div>
            <div class="card">
                <img src="drumetie.jpg" alt="Drumeții">
                <h3>Drumeții</h3>
                <p>Explorați traseele noastre amenajate și descoperiți frumusețea pădurii înconjurătoare.</p>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Pensiunea Carla. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
