;
    }

    .logo {
      height: 50px;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      font-size: 34px;
      margin-bottom: 10px;
    }

    .hero p {
      opacity: 0.8;
      font-size: 16px;
    }

    .btn {
      background: #fcbf49;
      color: black;
      padding: 12px 22px;
      border-radius: 8px;
      text-decoration: none;
      display: inline-block;
      margin-top: 20px;
      font-weight: bold;
    }

    .section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .section h2 {
      margin-bottom: 25px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1b263b;
      padding: 20px;
      border-radius: 12px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      color: #fcbf49;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 12px 16px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      font-size: 14px;
    }
  </style>
</head>

<body>

<header>
  <img src="logo.png" class="logo">
</header>

<section class="hero">
  <h2>Tu carga en movimiento 🚛</h2>
  <p>Logística confiable en todo Uruguay</p>
  <a class="btn" href="https://wa.me/598XXXXXXXX">Cotizar ahora</a>
</section>

<section class="section">
  <h2>Servicios</h2>
  <div class="cards">
    <div class="card">
      <h3>📦 Encomiendas</h3>
      <p>Envíos rápidos y seguros</p>
    </div>
    <div class="card">
      <h3>🌾 Transporte de granos</h3>
      <p>Especialistas en cargas agrícolas</p>
    </div>
    <div class="card">
      <h3>🌎 Internacional</h3>
      <p>Conectamos fronteras</p>
    </div>
    <div class="card">
      <h3>🏢 Depósitos</h3>
      <p>Espacios disponibles</p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Rutas</h2>
  <p>Montevideo - Cardona - Rodó - Palmitas - Mercedes</p>
</section>

<section class="section">
  <h2>Contacto</h2>
  <p>📲 WhatsApp: +598 XXX XXX XXX</p>
</section>

<a class="whatsapp" href="https://wa.me/598XXXXXXXX">WhatsApp</a>

<footer>
  © 2026 RF
