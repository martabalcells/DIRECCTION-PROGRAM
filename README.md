<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Direction Program - Solucions IT Sanitàries</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f7fb;
            color: #333;
        }

        header {
            background-color: #0a3d62;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #145da0;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1586773860418-d37222d8fce3') no-repeat center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .hero h1 {
            background-color: rgba(0,0,0,0.6);
            padding: 15px;
            border-radius: 10px;
        }

        section {
            padding: 40px;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }

        .card h3 {
            margin-bottom: 10px;
            color: #145da0;
        }

        footer {
            background-color: #0a3d62;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>Direction Program</h1>
    <p>Solucions Tecnològiques per al Sector Sanitari</p>
</header>

<nav>
    <a href="#empresa">Empresa</a>
    <a href="#serveis">Serveis</a>
    <a href="#projecte">Projecte</a>
    <a href="#contacte">Contacte</a>
</nav>

<div class="hero">
    <h1>Innovació IT per Hospitals i Clíniques</h1>
</div>

<section id="empresa">
    <h2>Sobre nosaltres</h2>
    <p>
        Direction Program és una empresa IT especialitzada en el desenvolupament, 
        implementació i manteniment de sistemes tecnològics per hospitals i clíniques.
        Oferim solucions adaptades a les necessitats del sector sanitari, garantint
        seguretat, eficiència i innovació.
    </p>
</section>

<section id="serveis">
    <h2>Serveis</h2>
    <div class="services">

        <div class="card">
            <h3>Xarxes</h3>
            <p>Disseny i configuració de xarxes hospitalàries segures amb VLANs i control d'accés.</p>
        </div>

        <div class="card">
            <h3>Servidors</h3>
            <p>Instal·lació de servidors DHCP, DNS, Active Directory i Proxy.</p>
        </div>

        <div class="card">
            <h3>Web</h3>
            <p>Desenvolupament de plataformes per gestió de cites mèdiques i pacients.</p>
        </div>

        <div class="card">
            <h3>Seguretat</h3>
            <p>Protecció de dades mèdiques amb sistemes de seguretat activa i passiva.</p>
        </div>

    </div>
</section>

<section id="projecte">
    <h2>El nostre projecte</h2>
    <p>
        El projecte Direction Program consisteix en la creació d'una empresa IT capaç de dissenyar,
        desplegar i mantenir infraestructures informàtiques completes.
    </p>

    <ul>
        <li>Implementació de xarxes corporatives amb Cisco Packet Tracer</li>
        <li>Configuració de servidors i màquines virtuals</li>
        <li>Desenvolupament web corporatiu</li>
        <li>Aplicació de mesures de ciberseguretat</li>
        <li>Connexió entre seus i client hospitalari</li>
    </ul>
</section>

<section id="contacte">
    <h2>Contacte</h2>
    <p>Email: info@directionprogram.com</p>
    <p>Telèfon: 123 456 789</p>
</section>

<footer>
    <p>© 2026 Direction Program - Tots els drets reservats</p>
</footer>

</body>
</html>
