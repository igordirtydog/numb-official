<!DOCTYPE html>
<html lang="hr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>numb ili noć u e molu</title>
  <style>
    body {
      background-color: #121212;
      color: #e0e0e0;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header, section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    header {
      background-color: #1f1f1f;
      text-align: center;
      padding-top: 4rem;
    }
    h1 {
      font-size: 2.5rem;
      color: #ffffff;
    }
    h2 {
      color: #ffcc00;
      border-bottom: 1px solid #444;
      padding-bottom: 0.5rem;
    }
    a {
      color: #ffcc00;
      text-decoration: none;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 1rem;
      border: 2px solid #333;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #999;
    }
  </style>
</head>
<body>
  <header>
    <h1>numb ili noć u e molu</h1>
    <p><em>"Kad bi noć imala zvuk, bio bi to E-mol."</em></p>
  </header>

  <section>
    <h2>O knjizi</h2>
    <p>
      Ovo introspektivno i poetski nabijeno djelo vodi nas kroz tamne slojeve ovisnosti, unutarnjih borbi i potrage za smislom. Kroz sirovu i iskrenu naraciju, autor otkriva osobni pad i potragu za svjetlom u tami.
    </p>
  </section>

  <section>
    <h2>O autoru</h2>
    <p>
      Igor Šajnović, autor romana "numb ili noć u e molu", koristi vlastita iskustva i unutarnje borbe kako bi stvorio brutalno iskrenu ispovijest koja ne ostavlja čitatelja ravnodušnim.
    </p>
  </section>

  <section>
    <h2>Isječci iz knjige</h2>
    <p>Preuzmite izabrane dijelove knjige:</p>
    <ul>
      <li><a href="downloads/isjecak1.pdf" download>Isječak 1 (PDF)</a></li>
      <li><a href="downloads/isjecak2.pdf" download>Isječak 2 (PDF)</a></li>
    </ul>
  </section>

  <section>
    <h2>Recenzije i komentari</h2>
    <div id="disqus_thread"></div>
    <script>
      var disqus_config = function () {
        this.page.url = window.location.href;
        this.page.identifier = "numb-knjiga";
      };
      (function() {
        var d = document, s = d.createElement('script');
        s.src = 'https://YOUR_DISQUS_SHORTNAME.disqus.com/embed.js'; // Zamijeni YOUR_DISQUS_SHORTNAME
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
      })();
    </script>
    <noscript>Aktivirajte JavaScript za prikaz komentara.</noscript>
  </section>

  <section>
    <h2>Galerija</h2>
    <div class="gallery">
      <img src="img/naslovnica.jpg" alt="Naslovnica knjige" />
      <img src="img/promocija1.jpg" alt="Promocija knjige" />
    </div>
  </section>

  <section>
    <h2>Kontakt</h2>
    <p>Pišite mi na: <a href="mailto:igorsajnovic2@gmail.com">igorsajnovic2@gmail.com</a></p>
  </section>

  <footer>
    &copy; 2025 Igor Šajnović. Sva prava pridržana.
  </footer>
</body>
