<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marino</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav>
    <a href="index.html" class="nav-logo">Marino</a>
    <div class="nav-links">
      <a href="fotos.html">fotos</a>
      <a href="escrever.html">escritos</a>
      <a href="sobre.html">sobre</a>
    </div>
  </nav>

  <main>

    <!-- Hero -->
    <section class="hero">
      <div class="hero-text">
        <span class="hero-sub">são paulo</span>
        <h1 class="hero-title">Marino</h1>
        <p class="hero-desc">fotografia, histórias, <em>pensamentos</em></p>
      </div>
    </section>

    <!--
      GRADE DE FOTOS
      ─────────────────────────────────────────────────────────────────────
      Coloque as suas fotos na pasta /fotos/
      Troque "fotos/foto1.jpg" pelo nome real do seu arquivo.

      Classes disponíveis:
        .tall   → ocupa 2 linhas de altura (ótimo para fotos verticais)
        .wide   → ocupa 2 colunas (ótimo para fotos horizontais/panorâmicas)
        (sem classe) → tamanho normal

      Para adicionar mais fotos, copie um bloco <div class="grid-item">
      e cole dentro de <div class="grid">.
      ─────────────────────────────────────────────────────────────────────
    -->
    <section class="grid-section">
      <div class="grid">
        <div class="grid-item tall">
          <img src="fotos/foto1.jpg" alt="">
        </div>
        <div class="grid-item">
          <img src="fotos/foto2.jpg" alt="">
        </div>
        <div class="grid-item">
          <img src="fotos/foto3.jpg" alt="">
        </div>
        <div class="grid-item wide">
          <img src="fotos/foto4.jpg" alt="">
        </div>
        <div class="grid-item">
          <img src="fotos/foto5.jpg" alt="">
        </div>
        <div class="grid-item tall">
          <img src="fotos/foto6.jpg" alt="">
        </div>
      </div>
    </section>

    <!-- Escritos recentes -->
    <section class="writing-preview">
      <div class="section-header">
        <span class="section-label">escritos recentes</span>
        <a href="escrever.html" class="see-all">ver todos →</a>
      </div>
      <div class="posts-list">

        <!--
          POST ITEM — copie este bloco para adicionar um escrito novo
          Troque: href, post-date, post-title, post-excerpt
        -->
        <a href="post-exemplo.html" class="post-item">
          <span class="post-date">maio 2026</span>
          <h2 class="post-title">o que eu aprendi sobre silêncio</h2>
          <p class="post-excerpt">Tem dias que a cidade toda fala e você não ouve nada. Não porque está distraído — mas porque decidiu, de alguma forma, não estar lá.</p>
        </a>

        <a href="post-exemplo.html" class="post-item">
          <span class="post-date">abril 2026</span>
          <h2 class="post-title">notas de uma quinta-feira comum</h2>
          <p class="post-excerpt">Acordei pensando em café e terminei pensando em tudo que não disse.</p>
        </a>

        <a href="post-exemplo.html" class="post-item">
          <span class="post-date">março 2026</span>
          <h2 class="post-title">sobre começar de novo sem drama</h2>
          <p class="post-excerpt">Recomeço não precisa de cerimônia. Às vezes é só acordar diferente.</p>
        </a>

      </div>
    </section>

  </main>

  <footer>
    <span>Marino © 2026</span>
    <div class="footer-links">
      <a href="https://vsco.co/marinohs" target="_blank">vsco</a>
    </div>
  </footer>

</body>
</html>
