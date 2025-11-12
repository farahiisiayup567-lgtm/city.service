<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>City Service für Reinigung</title>
    <style>
        body {
            font-family: "Tahoma", sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            background: white;
            width: 80%;
            margin: 50px auto;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #2c7a7b;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        a.button {
            background-color: #2c7a7b;
            color: white;
            text-decoration: none;
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 10px;
        }
        a.button:hover {
            background-color: #225e5e;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .service {
            background: #e8f0f0;
            border-radius: 15px;
            width: 250px;
            padding: 15px;
            margin: 10px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }
        .service img {
            width: 100%;
            border-radius: 10px;
        }
        .service h3 {
            color: #2c7a7b;
            margin: 10px 0 5px;
        }
        .service p {
            font-size: 16px;
            color: #555;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="container">
        <h1>City Service für Reinigung</h1>
        <p>Wir bieten professionelle Reinigung für Wohnungen, Büros und Häuser zu fairen Preisen.</p>
        <p>📞 Kontakt: 017661815287</p>
        <a class="button" href="https://wa.me/4917661815287" target="_blank">Jetzt über WhatsApp kontaktieren</a>
		<a class="button" href="mailto:cityservice.fuer.reinigung@gmail.com" target="_blank">Jetzt per E-Mail kontaktieren</a>
    </div>
	


    <!-- Services Section -->
    <div class="container">
        <h2>Unsere Dienstleistungen</h2>
        <div class="services">
            <div class="service">
                <img src="https://i.pinimg.com/1200x/02/e4/13/02e413ffda63af7c548cfa3128373ec2.jpg">
                <h3>Wohnungsreinigung</h3>
                <p>Gründliche Reinigung von Wohnungen aller Größen.</p>
            </div>
            <div class="service">
                <img src="https://i.pinimg.com/736x/5c/98/f2/5c98f27fed660cf5c3f6e97796ddda89.jpg" alt="Büroreinigung">
                <h3>Büroreinigung</h3>
                <p>Saubere und gepflegte Arbeitsplätze für Ihr Büro.</p>
            </div>
            <div class="service">
                <img src="https://i.pinimg.com/736x/9b/94/04/9b9404ab2d73520e2389503a136fb337.jpg" alt="Fensterputzen">
                <h3>Fensterputzen</h3>
                <p>Glasklare Fenster für ein strahlendes Zuhause.</p>
            </div>
        </div>
    </div>
</body>
</html>
