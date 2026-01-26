<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BACH: ULA VALLE - Avisos</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <header class="header">
    <h1>BACH: ULA VALLE</h1>
    <p>Avisos</p>
  </header>

  <div class="topbar">
    <nav class="nav">
      <a href="index.html">Inicio</a>

      <div class="dropdown">
        <button class="dropbtn">Contenido ▾</button>
        <div class="dropdown-content">
          <a href="avisos.html">Avisos</a>
          <a href="recordatorios.html">Recordatorios</a>
        </div>
      </div>
    </nav>
  </div>

  <main class="container">
    <section class="card">
      <h2>Avisos</h2>
      <p class="meta">Última actualización: <span id="lastUpdate"></span></p>

      <article class="card" style="margin-top:14px;">
        <h3>LLUVIAS/INUNDACIONES</h3>
        <p>Estimada comunidad estudiantil ULA, derivado de la condición climática y 
            sus respectivas repercusiones, el día de hoy 29 de septiembre 2025 se extiende
             el ingreso al campus y a sus respectivas clases hasta las 7:30 am. De antemano
              deseándoles que lleguen con bien. </p>

              <p>29.09.2025, 07:00 am</p>
      </article>

      <article class="card" style="margin-top:14px;">
        <h3>Aviso 2</h3>
        <p>Escribe aquí tu aviso.</p>
      </article>
    </section>
  </main>

  <footer class="footer">
    © 2026 BACH: ULA VALLE
  </footer>

  <script>
    document.getElementById("lastUpdate").textContent =
      new Date().toLocaleDateString("es-MX", { year: "numeric", month: "long", day: "numeric" });
  </script>

</body>
</html>
