<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SG Clean Cars</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: black;
    color: white;
    text-align: center;
}

/* TŁO */
body::before {
    content: "";
    position: fixed;
    width: 100%;
    height: 100%;
    background: url('https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2');
    background-size: cover;
    background-position: center;
    opacity: 0.25;
    z-index: -1;
}

/* LOGO */
h1 {
    font-size: 40px;
    color: #00bfff;
    text-shadow: 0 0 15px #00bfff;
    margin-top: 30px;
}

/* SEKCJE */
.section {
    margin: 20px;
    padding: 20px;
    border-radius: 15px;
    background: rgba(0,0,0,0.7);
    box-shadow: 0 0 20px #00bfff33;
}

/* NAGŁÓWKI */
h2 {
    color: #00bfff;
    text-shadow: 0 0 10px #00bfff;
}

/* CENA */
.price {
    font-size: 24px;
    color: #00bfff;
    margin-top: 10px;
}

/* PRZYCISK */
button {
    margin-top: 20px;
    padding: 15px 25px;
    background: #00bfff;
    border: none;
    border-radius: 10px;
    font-size: 18px;
    color: black;
    box-shadow: 0 0 15px #00bfff;
}

/* BONUS */
.bonus {
    margin: 20px;
    padding: 15px;
    border-radius: 50px;
    background: #00bfff;
    color: black;
    font-weight: bold;
}
</style>
</head>

<body>

<h1>SG Clean Cars</h1>
<p>Auto Detailing</p>

<div class="section">
<h2>Pakiet BASIC</h2>
<p>Mycie zewnętrzne + wnętrze</p>
<p class="price">100 – 200 zł</p>
</div>

<div class="section">
<h2>Pakiet PREMIUM</h2>
<p>Kompleksowy detailing</p>
<p class="price">350 – 550 zł</p>
</div>

<div class="section">
<h2>Usługi dodatkowe</h2>
<p>Fotel – 20 zł</p>
<p>Komplet – 80 zł</p>
<p>Kanapa – 40 zł</p>
<p>Dywaniki – 20–30 zł</p>
</div>

<div class="bonus">
🔥 5 mycie GRATIS!
</div>

<h2>Zadzwoń i umów termin</h2>

<a href="tel:+48729638800">
<button>+48 729 638 800</button>
</a>

<p>Dojazd do 30 km GRATIS</p>

</body>
</html>
