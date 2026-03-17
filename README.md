<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>SG Clean Cars</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(black, #001f2f);
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
  font-size: 45px;
  color: #00bfff;
  text-shadow: 0 0 20px #00bfff;
  margin-top: 30px;
}

/* SEKCJE */
.section {
  margin: 20px;
  padding: 20px;
  border-radius: 15px;
  background: rgba(0,0,0,0.6);
  box-shadow: 0 0 15px #00bfff;
}

/* PRZYCISK */
.button {
  display: inline-block;
  padding: 12px 25px;
  margin-top: 10px;
  border-radius: 10px;
  background: #00bfff;
  color: black;
  text-decoration: none;
  font-weight: bold;
}

.button:hover {
  background: white;
}
</style>

</head>

<body>

<h1>SG Clean Cars</h1>

<div class="section">
  <h2>🚗 Nasze usługi</h2>
  <p>✔ Mycie auta</p>
  <p>✔ Czyszczenie wnętrza</p>
  <p>✔ Polerowanie</p>
</div>

<div class="section">
  <h2>📞 Kontakt</h2>
  <p>Telefon: 123 456 789</p>
  <a class="button" href="#">Napisz do nas</a>
</div>

</body>
</html>
