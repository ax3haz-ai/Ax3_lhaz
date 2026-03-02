<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🔥 ¡Vive la Pasión por las Motos! 🏍️</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
      color: #fff;
      min-height: 100vh;
      overflow-x: hidden;
    }
    
    header {
      position: relative;
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)), url('https://cloudfront-us-east-1.images.arcpublishing.com/octane/ZRVBVF37TBBLXBB7ZPLW5GEOT4.jpg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
    }
    
    .hero-content {
      max-width: 900px;
    }
    
    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: clamp(3.5rem, 10vw, 8rem);
      color: #ff2e63;
      text-shadow: 0 0 30px #ff2e63, 0 0 60px #ff2e63aa;
      margin-bottom: 1rem;
      letter-spacing: 4px;
      animation: glow 3s ease-in-out infinite alternate;
    }
    
    .subtitle {
      font-size: 1.8rem;
      margin: 1.5rem 0 2.5rem;
      color: #00f2ff;
      text-shadow: 0 0 15px #00f2ff88;
    }
    
    .btn {
      display: inline-block;
      padding: 18px 50px;
      font-size: 1.4rem;
      font-weight: bold;
      background: #ff2e63;
      color: white;
      text-decoration: none;
      border-radius: 50px;
      box-shadow: 0 0 40px #ff2e6388;
      transition: all 0.4s;
      border: 3px solid #00f2ff;
    }
    
    .btn:hover {
      transform: translateY(-8px) scale(1.08);
      background: #00f2ff;
      color: #000;
      box-shadow: 0 0 60px #00f2ffaa, 0 15px 40px rgba(0,0,0,0.6);
    }
    
    section {
      padding: 100px 5%;
      max-width: 1400px;
      margin: 0 auto;
    }
    
    h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3.5rem;
      text-align: center;
      margin-bottom: 60px;
      color: #00f2ff;
      text-shadow: 0 0 20px #00f2ff66;
    }
    
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
      gap: 30px;
    }
    
    .card {
      position: relative;
      overflow: hidden;
      border-radius: 20px;
      box-shadow: 0 15px 40px rgba(0,0,0,0.7);
      transition: all 0.5s;
      background: #111;
    }
    
    .card:hover {
      transform: translateY(-20px) scale(1.05);
      box-shadow: 0 30px 70px rgba(255,46,99,0.5);
    }
    
    .card img {
      width: 100%;
      height: 380px;
      object-fit: cover;
      transition: transform 0.8s;
    }
    
    .card:hover img {
      transform: scale(1.15);
    }
    
    .card-info {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      padding: 25px;
      background: linear-gradient(to top, rgba(0,0,0,0.95), transparent);
      transform: translateY(100%);
      transition: transform 0.5s;
    }
    
    .card:hover .card-info {
      transform: translateY(0);
    }
    
    .card h3 {
      font-size: 1.8rem;
      margin-bottom: 10px;
      color: #ff2e63;
    }
    
    @keyframes glow {
      from { text-shadow: 0 0 20px #ff2e63, 0 0 40px #ff2e63aa; }
      to   { text-shadow: 0 0 40px #ff2e63, 0 0 80px #ff2e63ff; }
    }
    
    @media (max-width: 768px) {
      h1 { font-size: 5rem; }
      .subtitle { font-size: 1.4rem; }
      h2 { font-size: 2.8rem; }
    }
  </style>
</head>
<body>

  <header>
    <div class="hero-content">
      <h1>🏍️ MOTOS LEGENDARIAS</h1>
      <p class="subtitle">Adrenalina, libertad y puro estilo en dos ruedas</p>
      <a href="#galeria" class="btn">¡Descubre más! 🔥</a>
    </div>
  </header>

  <section id="galeria">
    <h2>Estilos que Encienden el Asfalto</h2>
    
    <div class="gallery">
      <div class="card">
        <img src="https://cloudfront-us-east-1.images.arcpublishing.com/octane/ZRVBVF37TBBLXBB7ZPLW5GEOT4.jpg" alt="Sportbike naranja en pista">
        <div class="card-info">
          <h3>Sportbikes</h3>
          <p>Velocidad pura • Aerodinámica extrema • Circuito</p>
        </div>
      </div>
      
      <div class="card">
        <img src="https://www.gearpatrol.com/wp-content/uploads/sites/2/2025/09/suzuki-hayabusa-special-edition-action.webp?w=1500" alt="Suzuki Hayabusa azul en curva">
        <div class="card-info">
          <h3>Hyperbikes</h3>
          <p>Más de 300 km/h • Potencia brutal • Íconos</p>
        </div>
      </div>
      
      <div class="card">
        <img src="https://images.prismic.io/riders-sharecom/ZjDrcd3JpQ5PTRQD_AdobeStock_2784231.jpeg?auto=format,compress" alt="Chopper custom rojo">
        <div class="card-info">
          <h3>Choppers / Custom</h3>
          <p>Estilo único • Actitud rebelde • Show</p>
        </div>
      </div>
      
      <div class="card">
        <img src="https://mcn-images.bauersecure.com/wp-images/59233/1440x960/t7-11-2.jpg?mode=max&quality=90&scale=down" alt="Adventure bike en off-road">
        <div class="card-info">
          <h3>Adventure</h3>
          <p>Carretera + off-road • Viajes épicos • Aventura</p>
        </div>
      </div>
      
      <div class="card">
        <img src="http://www.vikingbags.com/cdn/shop/articles/top-10-retrostyle-motorcycles-to-purchase-in-2023.jpg?v=1740163035&width=2048" alt="Café racer plateada moderna">
        <div class="card-info">
          <h3>Café Racers / Retro</h3>
          <p>Clásico renovado • Minimalismo • Estilo</p>
        </div>
      </div>
      
      <div class="card">
        <img src="https://thumbs.dreamstime.com/b/colorful-digital-painting-yellow-sport-motorcycle-dynamic-action-artistic-rendering-motorcyclist-racing-bike-407043313.jpg" alt="Moto deportiva amarilla arte digital">
        <div class="card-info">
          <h3>Arte en Movimiento</h3>
          <p>Diseños explosivos • Colores vibrantes • Pasión</p>
        </div>
      </div>
    </div>
  </section>

  <footer style="text-align:center; padding:60px 20px; background:rgba(0,0,0,0.6);">
    <p style="font-size:1.3rem; margin-bottom:1rem;">¿Listo para acelerar tu vida? 🏍️💨</p>
    <p>© 2026 - Hecho con adrenalina por un apasionado de las motos</p>
  </footer>

</body>
</html>
