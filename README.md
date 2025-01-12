<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noctur - Negozio di Vestiti e Scarpe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #111;
            color: white;
            padding: 1em;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #222;
            padding: 0.5em 0;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .home-section, .category-section {
            padding: 2em;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1em;
        }

        .item {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1em;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            background-color: #f9f9f9;
        }

        .item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .item h3 {
            margin: 1em 0 0.5em;
        }

        .item p {
            color: #666;
        }

        .item button {
            background-color: #111;
            color: white;
            border: none;
            padding: 0.5em 1em;
            cursor: pointer;
            border-radius: 3px;
        }

        .item button:hover {
            background-color: #333;
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 1em;
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Benvenuti nel Negozio Noctur</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#scarpe">Scarpe</a>
        <a href="#felpe">Felpe</a>
        <a href="#pantaloni">Pantaloni</a>
    </nav>

    <main>
        <section class="home-section" id="home">
            <h2>Modelli Più Importanti</h2>
            <div class="container">
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe Noctur">
                    <h3>Scarpe Noctur Street</h3>
                    <p>Prezzo: €120.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa Noctur">
                    <h3>Felpa Noctur Casual</h3>
                    <p>Prezzo: €50.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni Noctur">
                    <h3>Pantaloni Noctur Slim</h3>
                    <p>Prezzo: €70.00</p>
                </div>
            </div>
        </section>

        <section class="category-section" id="scarpe">
            <h2>Scarpe Noctur</h2>
            <div class="container">
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 1">
                    <h3>Scarpe Running</h3>
                    <p>Prezzo: €90.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 2">
                    <h3>Scarpe Eleganti</h3>
                    <p>Prezzo: €110.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 3">
                    <h3>Scarpe Sportive</h3>
                    <p>Prezzo: €100.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 4">
                    <h3>Scarpe Casual</h3>
                    <p>Prezzo: €85.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 5">
                    <h3>Scarpe Noctur Urban</h3>
                    <p>Prezzo: €125.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 6">
                    <h3>Scarpe Hiking</h3>
                    <p>Prezzo: €140.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 7">
                    <h3>Scarpe Comfort</h3>
                    <p>Prezzo: €95.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 8">
                    <h3>Scarpe Design</h3>
                    <p>Prezzo: €130.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Scarpe 9">
                    <h3>Scarpe Lifestyle</h3>
                    <p>Prezzo: €110.00</p>
                </div>
            </div>
        </section>

        <section class="category-section" id="felpe">
            <h2>Felpe Noctur</h2>
            <div class="container">
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 1">
                    <h3>Felpa con Cappuccio</h3>
                    <p>Prezzo: €40.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 2">
                    <h3>Felpa Sportiva</h3>
                    <p>Prezzo: €55.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 3">
                    <h3>Felpa Oversize</h3>
                    <p>Prezzo: €60.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 4">
                    <h3>Felpa Urban</h3>
                    <p>Prezzo: €50.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 5">
                    <h3>Felpa Estiva</h3>
                    <p>Prezzo: €45.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 6">
                    <h3>Felpa Noctur Relax</h3>
                    <p>Prezzo: €70.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 7">
                    <h3>Felpa College</h3>
                    <p>Prezzo: €65.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 8">
                    <h3>Felpa Minimal</h3>
                    <p>Prezzo: €55.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Felpa 9">
                    <h3>Felpa Lifestyle</h3>
                    <p>Prezzo: €60.00</p>
                </div>
            </div>
        </section>

        <section class="category-section" id="pantaloni">
            <h2>Pantaloni Noctur</h2>
            <div class="container">
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 1">
                    <h3>Pantaloni Sportivi</h3>
                    <p>Prezzo: €50.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 2">
                    <h3>Pantaloni Eleganti</h3>
                    <p>Prezzo: €70.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 3">
                    <h3>Pantaloni Slim Fit</h3>
                    <p>Prezzo: €65.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 4">
                    <h3>Pantaloni Noctur Basic</h3>
                    <p>Prezzo: €55.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 5">
                    <h3>Pantaloni Cargo</h3>
                    <p>Prezzo: €75.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 6">
                    <h3>Pantaloni Estivi</h3>
                    <p>Prezzo: €60.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 7">
                    <h3>Pantaloni Relax Fit</h3>
                    <p>Prezzo: €70.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 8">
                    <h3>Pantaloni Noctur Comfort</h3>
                    <p>Prezzo: €80.00</p>
                </div>
                <div class="item">
                    <img src="https://via.placeholder.com/300x400" alt="Pantaloni 9">
                    <h3>Pantaloni Design</h3>
                    <p>Prezzo: €85.00</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Noctur. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
