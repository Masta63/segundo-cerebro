<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Dark Mode SaaS</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background-color: #0d001e; /* fondo principal */
      color: #E5E7EB; /* texto claro suave */
    }

    /* Navbar */
    .navbar {
      background-color: #14183d;
      padding: 15px 30px;
      font-size: 18px;
      color: white;
      border-bottom: 1px solid rgba(255,255,255,0.05);
    }

    /* Layout */
    .container {
      padding: 30px;
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 20px;
    }

    /* Cards */
    .card {
      background: #14183d; /* NO negro puro */
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
      border: 1px solid rgba(255,255,255,0.05);
    }

    h3 {
      margin-top: 0;
      color: #3fa9f5; /* acento */
    }

    p {
      color: #9CA3AF;
    }

    /* Botón */
    .btn {
      background: #3179b8;
      color: white;
      padding: 10px 14px;
      border-radius: 8px;
      display: inline-block;
      margin-top: 10px;
      transition: 0.2s;
    }

    .btn:hover {
      background: #3fa9f5;
    }

    /* Chart fake (mejor en dark) */
    .chart {
      height: 200px;
      border-radius: 10px;
      background: linear-gradient(
        to right,
        #3fa9f5,
        #3179b8,
        #22487a,
        #14183d,
        #0d001e
      );
      opacity: 0.9;
    }

    /* Stats */
    .stat {
      font-size: 26px;
      font-weight: bold;
      color: white;
    }

    .positive {
      color: #22c55e;
    }

    .negative {
      color: #ef4444;
    }

  </style>
</head>
<body>

  <div class="navbar">
    Dashboard (Dark Mode)
  </div>

  <div class="container">

    <div class="card">
      <h3>Rendimiento</h3>
      <div class="chart"></div>
    </div>

    <div class="card">
      <h3>Balance</h3>
      <p class="stat">$24,320</p>
      <p class="positive">+6.8% este mes</p>
      <div class="btn">Ver detalles</div>
    </div>

    <div class="card">
      <h3>Operaciones</h3>
      <p class="positive">✔ Ganadas: 18</p>
      <p class="negative">✖ Perdidas: 5</p>
    </div>

    <div class="card">
      <h3>Resumen</h3>
      <p>Portfolio diversificado en acciones y crypto.</p>
    </div>

  </div>

</body>
</html>

"💡 Ajuste fino (te lo dejo picando)

Si querés llevarlo a nivel PRO de verdad:

Agregar:
blur + glassmorphism leve
bordes con rgba(255,255,255,0.08)
sombras más suaves"