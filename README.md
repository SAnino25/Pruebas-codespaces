# Pruebas-codespaces<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Pruebas Codespaces</title>
  <style>
    :root{--bg:#f6f8fa;--card:#fff;--accent:#0366d6;--muted:#6b7280}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial}
    body{background:var(--bg);color:#111;display:flex;align-items:center;justify-content:center;padding:32px}
    .page{max-width:900px;width:100%;background:var(--card);border-radius:12px;box-shadow:0 6px 24px rgba(15,23,42,.08);overflow:hidden}
    header{display:flex;align-items:center;justify-content:space-between;padding:20px 28px;border-bottom:1px solid #eef2f6}
    h1{font-size:1.125rem;margin:0}
    nav a{color:var(--accent);text-decoration:none;margin-left:14px;font-weight:600}
    main{display:grid;grid-template-columns:1fr 320px;gap:20px;padding:28px}
    .hero{padding-right:8px}
    .card{background:#fbfcfd;padding:18px;border-radius:8px;border:1px solid #eef2f6}
    .cta{display:inline-block;margin-top:12px;padding:10px 14px;background:var(--accent);color:#fff;border-radius:8px;text-decoration:none}
    footer{padding:14px 28px;border-top:1px solid #eef2f6;color:var(--muted);font-size:.9rem;text-align:center}
    @media (max-width:820px){main{grid-template-columns:1fr;}}
  </style>
</head>
<body>
  <div class="page" role="application">
    <header>
      <h1>Pruebas Codespaces</h1>
      <nav>
        <a href="#inicio">Inicio</a>
        <a href="#acerca">Acerca</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="card">
          <h2 id="inicio">Página de ejemplo</h2>
          <p>Esta es una página HTML simple preparada para pruebas en tu workspace. Puedes editarla y verla en un navegador.</p>
          <a class="cta" href="#" id="open">Abrir en el navegador</a>
        </div>
      </section>

      <aside>
        <div class="card">
          <h3>Detalles</h3>
          <p style="color:var(--muted)">Ruta: /workspaces/Pruebas-codespaces/index.html</p>
          <p style="margin-top:8px">Responsive, CSS integrado y ejemplo de estructura (header, main, footer).</p>
        </div>
      </aside>
    </main>

    <footer>
      Creada para pruebas • © 2025
    </footer>
  </div>

  <script>
    // Abre el archivo en el navegador del host (en el contenedor usa: "$BROWSER" file://... )
    document.getElementById('open').addEventListener('click', function(e){
      e.preventDefault();
      alert('Para abrir en el host: en la terminal del contenedor ejecuta: $BROWSER file://' + location.pathname);
    });
  </script>
</body>
</html>
```<!-- filepath: /workspaces/Pruebas-codespaces/index.html -->
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Pruebas Codespaces</title>
  <style>
    :root{--bg:#f6f8fa;--card:#fff;--accent:#0366d6;--muted:#6b7280}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial}
    body{background:var(--bg);color:#111;display:flex;align-items:center;justify-content:center;padding:32px}
    .page{max-width:900px;width:100%;background:var(--card);border-radius:12px;box-shadow:0 6px 24px rgba(15,23,42,.08);overflow:hidden}
    header{display:flex;align-items:center;justify-content:space-between;padding:20px 28px;border-bottom:1px solid #eef2f6}
    h1{font-size:1.125rem;margin:0}
    nav a{color:var(--accent);text-decoration:none;margin-left:14px;font-weight:600}
    main{display:grid;grid-template-columns:1fr 320px;gap:20px;padding:28px}
    .hero{padding-right:8px}
    .card{background:#fbfcfd;padding:18px;border-radius:8px;border:1px solid #eef2f6}
    .cta{display:inline-block;margin-top:12px;padding:10px 14px;background:var(--accent);color:#fff;border-radius:8px;text-decoration:none}
    footer{padding:14px 28px;border-top:1px solid #eef2f6;color:var(--muted);font-size:.9rem;text-align:center}
    @media (max-width:820px){main{grid-template-columns:1fr;}}
  </style>
</head>
<body>
  <div class="page" role="application">
    <header>
      <h1>Pruebas Codespaces</h1>
      <nav>
        <a href="#inicio">Inicio</a>
        <a href="#acerca">Acerca</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="card">
          <h2 id="inicio">Página de ejemplo</h2>
          <p>Esta es una página HTML simple preparada para pruebas en tu workspace. Puedes editarla y verla en un navegador.</p>
          <a class="cta" href="#" id="open">Abrir en el navegador</a>
        </div>
      </section>

      <aside>
        <div class="card">
          <h3>Detalles</h3>
          <p style="color:var(--muted)">Ruta: /workspaces/Pruebas-codespaces/index.html</p>
          <p style="margin-top:8px">Responsive, CSS integrado y ejemplo de estructura (header, main, footer).</p>
        </div>
      </aside>
    </main>

    <footer>
      Creada para pruebas • © 2025
    </footer>
  </div>

  <script>
    // Abre el archivo en el navegador del host (en el contenedor usa: "$BROWSER" file://... )
    document.getElementById('open').addEventListener('click', function(e){
      e.preventDefault();
      alert('Para abrir en el host: en la terminal del contenedor ejecuta: $BROWSER file://' + location.pathname);
    });
  </script>
</body>
</html>