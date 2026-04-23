
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Paleta Azul Test</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f7fa;
    }

    .title {
      padding: 20px;
      font-size: 22px;
      font-weight: bold;
    }

    /* Paleta */
    .palette {
      display: flex;
      height: 120px;
    }

    .color {
      flex: 1;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      color: white;
      font-size: 12px;
      padding-bottom: 10px;
    }

    /* Colores */
    .c1 { background: #3fa9f5; }
    .c2 { background: #3891d6; }
    .c3 { background: #3179b8; }
    .c4 { background: #2a6199; }
    .c5 { background: #22487a; }
    .c6 { background: #1b305b; }
    .c7 { background: #14183d; }
    .c8 { background: #0d001e; }

    /* UI Preview */
    .ui {
      padding: 30px;
      display: flex;
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .btn {
      background: #3179b8;
      color: white;
      padding: 10px;
      border-radius: 6px;
      text-align: center;
      margin-top: 10px;
    }

    .btn:hover {
      background: #3fa9f5;
    }

    .dark {
      background: #0d001e;
      color: white;
    }
  </style>
</head>
<body>

  <div class="title">Paleta Azul (Preview)</div>

  <!-- Paleta pura -->
  <div class="palette">
    <div class="color c1">#3fa9f5</div>
    <div class="color c2">#3891d6</div>
    <div class="color c3">#3179b8</div>
    <div class="color c4">#2a6199</div>
    <div class="color c5">#22487a</div>
    <div class="color c6">#1b305b</div>
    <div class="color c7">#14183d</div>
    <div class="color c8">#0d001e</div>
  </div>

  <!-- Cómo se ve en UI -->
  <div class="ui">

    <div class="card">
      <h3 style="color:#22487a;">Card clara</h3>
      <p>Contenido simple</p>
      <div class="btn">Acción</div>
    </div>

    <div class="card dark">
      <h3 style="color:#3fa9f5;">Card oscura</h3>
      <p>Modo más premium</p>
      <div class="btn">Acción</div>
    </div>

  </div>

</body>
</html>

"que use como inspiracion :https://m3.material.io/styles"

"https://github.com/material-components/material-web/tree/main/docs"