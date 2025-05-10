# BM
# unique
nike_style_html = """<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BM - Unique</title>
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Oswald', sans-serif;
      background: #fff;
      color: #000;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background-color: #000;
    }

    .logo {
      color: white;
      font-size: 2em;
      font-weight: bold;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1606811842773-6d51c606fc94?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }

    .hero h1 {
      font-size: 5em;
      background: rgba(0, 0, 0, 0.6);
      padding: 10px 30px;
    }

    .hero p {
      font-size: 1.8em;
      margin-top: 15px;
      background: rgba(0, 0, 0, 0.5);
      padding: 5px 20px;
      color: #F2994B;
    }

    .btn {
      margin-top: 30px;
      padding: 15px 30px;
      background-color: white;
      color: black;
      text-decoration: none;
      font-weight: bold;
      text-transform: uppercase;
      border-radius: 3px;
      transition: 0.3s ease;
    }

    .btn:hover {
      background-color: #F2994B;
      color: white;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 3em;
      }
      .hero p {
        font-size: 1.2em;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">BM</div>
    <nav>
      <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Produits</a></li>
       
