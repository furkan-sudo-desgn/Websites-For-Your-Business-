# Websites-For-Your-Business-
<!DOCTYPE html>

<html lang="de">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>W. Studio — Premium Webdesign</title>

<style>

:root {

  --bg: #080808;

  --gold: #d6b56d;

  --text: #f5f2e9;

  --muted: #aaa69b;

}

* { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {

  margin: 0;

  background: var(--bg);

  color: var(--text);

  font-family: Arial, sans-serif;

}

nav {

  padding: 24px 7%;

  display: flex;

  justify-content: space-between;

  align-items: center;

  border-bottom: 1px solid #ffffff18;

}

.logo { font-size: 23px; font-weight: bold; }

.logo span { color: var(--gold); }

a { color: inherit; text-decoration: none; }

.btn {

  display: inline-block;

  padding: 14px 20px;

  border: 1px solid #ffffff35;

  border-radius: 30px;

  margin: 6px 5px 6px 0;

  transition: .2s;

}

.btn:hover {

  border-color: var(--gold);

  transform: translateY(-2px);

}

.primary {

  color: #080808;

  background: linear-gradient(110deg, #f0dca8, #b28a3d);

  font-weight: bold;

}

.hero {

  min-height: 75vh;

  padding: 90px 7%;

  display: grid;

  grid-template-columns: 1fr 1fr;

  gap: 35px;

  align-items: center;

}

.tag {

  color: var(--gold);

  letter-spacing: 3px;

  font-size: 12px;

}

h1 {

  font-size: clamp(45px, 7vw, 82px);

  line-height: 1;

  letter-spacing: -4px;

}

.gold {

  color: var(--gold);

}

p {

  color: var(--muted);

  line-height: 1.8;

}

.visual {

  min-height: 390px;

  display: grid;

  place-items: center;

  border: 1px solid #ffffff15;

  border-radius: 30px;

  background: radial-gradient(circle, #d6b56d24, #080808 70%);

}

.can {

  width: 150px;

  height: 280px;

  border-radius: 30px;

  background: linear-gradient(90deg,#42351e,#e7d4a1,#a78035,#302617);

  box-shadow: 0 25px 60px #000;

  display: grid;

  place-items: center;

  text-align: center;

  color: #17130b;

  transform: rotate(-7deg);

  animation: float 4s ease-in-out infinite;

}

.can strong { font-size: 28px; }

.can small { letter-spacing: 2px; }

@keyframes float {

  0%,100% { transform: translateY(0) rotate(-7deg); }

  50% { transform: translateY(-15px) rotate(3deg); }

}

section.content {

  padding: 70px 7%;

}

h2 {

  font-size: clamp(32px,5vw,55px);

  letter-spacing: -2px;

}

.cards {

  display: grid;

  grid-template-columns: repeat(3,1fr);

  gap: 18px;

}

.card {

  padding: 25px;

  border: 1px solid #ffffff20;

  border-radius: 20px;

  background: #ffffff06;

}

.card h3 { color: var(--gold); }

.showcase {

  padding: 35px;

  border: 1px solid #ffffff20;

  border-radius: 24px;

  background: linear-gradient(130deg,#211b10,#101010);

}

.steps {

  display: grid;

  grid-template-columns: repeat(4,1fr);

  gap: 20px;

}

.step {

  border-top: 1px solid #ffffff40;

  padding-top: 18px;

}

.step b { color: var(--gold); }

.contact {

  text-align: center;

  padding: 55px 25px;

  border: 1px solid #d6b56d55;

  border-radius: 25px;

  background: radial-gradient(ellipse at top,#d6b56d20,#080808 70%);

}

footer {

  padding: 25px 7%;

  border-top: 1px solid #ffffff20;

  color: var(--muted);

  font-size: 12px;

}

@media(max-width:750px) {

  .hero { grid-template-columns: 1fr; padding-top: 55px; }

  .cards { grid-template-columns: 1fr; }

  .steps { grid-template-columns: 1fr 1fr; }

  nav { padding: 20px 6%; }

}

</style>

</head>

<body>

<nav>

  <a class="logo" href="#home">W<span>.</span> STUDIO</a>

  <a class="btn" href="#kontakt">Projekt anfragen ↗</a>

</nav>

<main id="home">

<section class="hero">

  <div>

    <div class="tag">✦ PREMIUM WEBDESIGN</div>

    <h1>Websites, die<br><span class="gold">anders wirken.</span></h1>

    <p>Ich gestalte moderne, hochwertige Websites für Unternehmen, die online professionell auftreten und im Kopf bleiben wollen. Klar im Design. Stark im Eindruck. Für jedes Display gemacht.</p>

    <a class="btn primary" href="#kontakt">Kostenlose Beratung ↗</a>

    <a class="btn" href="#arbeiten">Showcase ansehen ↓</a>

    <p>✦ Individuelles Design · Mobile-first · Mit Liebe zum Detail</p>

  </div>

  <div class="visual">

    <div class="can">

      <div>

        <small>W. STUDIO PRESENTS</small>

        <br><br>

        <strong>MAKE<br>IT BOLD</strong>

        <br><br>✳<br>

        <small>ENERGY / DESIGN</small>

      </div>

    </div>

  </div>

</section>

<section class="content" id="leistungen">

  <div class="tag">WAS ICH MACHE</div>

  <h2>Digital. Durchdacht.<br>Unverwechselbar.</h2>

  <p>Ein starker erster Eindruck für dein Unternehmen – online genauso überzeugend wie vor Ort.</p>

  <div class="cards">

    <article class="card">

      <h3>✳ Moderne Websites</h3>

      <p>Individuelle Seiten mit klarer Navigation, moderner Typografie und einem hochwertigen Look.</p>

    </article>

    <article class="card">

      <h3>◈ Animation & Details</h3>

      <p>Bewegte Elemente und besondere Details, die Aufmerksamkeit schaffen.</p>

    </article>

    <article class="card">

      <h3>↗ Mobile-first</h3>

      <p>Ein professioneller Auftritt auf Smartphone, Tablet und Desktop.</p>

    </article>

  </div>

</section>

<section class="content" id="arbeiten">

  <div class="tag">KONZEPT / 001</div>

  <h2>So könnte deine<br><span class="gold">Marke aussehen.</span></h2>

  <div class="showcase">

    <h3>Nicht einfach online. Unübersehbar.</h3>

    <p>Vom ersten Blick bis zum Kontakt: Jeder Abschnitt hat einen Zweck. Das Ergebnis ist ein digitaler Auftritt mit Charakter.</p>

  </div>

</section>

<section class="content" id="ablauf">

  <div class="tag">DER ABLAUF</div>

  <h2>Von der Idee<br>zum Auftritt.</h2>

  <div class="steps">

    <div class="step"><b>01 / VERSTEHEN</b><h3>Deine Idee</h3><p>Wir klären Ziel, Stil und Inhalte.</p></div>

    <div class="step"><b>02 / GESTALTEN</b><h3>Das Design</h3><p>Ich entwickle einen passenden Look.</p></div>

    <div class="step"><b>03 / UMSETZEN</b><h3>Die Website</h3><p>Die Seite wird für Geräte optimiert.</p></div>

    <div class="step"><b>04 / ONLINE</b><h3>Veröffentlichen</h3><p>Wir bereiten den Start der Website vor.</p></div>

  </div>

</section>

<section class="content" id="kontakt">

  <div class="contact">

    <div class="tag">DEIN NÄCHSTER SCHRITT</div>

    <h2>Bereit für einen<br><span class="gold">stärkeren Auftritt?</span></h2>

    <p>Erzähl mir von deinem Unternehmen und deiner Idee. Gemeinsam finden wir eine passende Richtung für deine Website.</p>

    <a class="btn primary"

       href="https://www.instagram.com/websites._for_your_business/"

       target="_blank" rel="noopener">

       Kostenlose Beratung per DM ↗

    </a>

    <p>Instagram: @websites._for_your_business</p>

  </div>

</section>

</main>

<footer>

  <strong>W. STUDIO</strong> — Webdesign & digitale Erlebnisse · 2026

</footer>

</body>

</html>
