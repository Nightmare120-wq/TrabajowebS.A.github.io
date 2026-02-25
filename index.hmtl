<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Daily Tribune — Historia & Cultura</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;0,900;1,400;1,700&family=UnifrakturMaguntia&family=EB+Garamond:ital,wght@0,400;0,500;1,400&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --ink: #111111;
    --paper: #f8f4ed;
    --muted: #555;
    --rule: #222;
    --accent: #8B0000;
    --light-rule: #ccc;
  }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: 'EB Garamond', Georgia, serif;
    font-size: 17px;
    line-height: 1.65;
  }

  /* ─── MASTHEAD ─── */
  .masthead {
    border-top: 4px solid var(--rule);
    border-bottom: 1px solid var(--rule);
    text-align: center;
    padding: 10px 20px 14px;
    position: relative;
  }
  .masthead-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    color: var(--muted);
    border-bottom: 1px solid var(--light-rule);
    padding-bottom: 8px;
    margin-bottom: 8px;
    letter-spacing: 0.05em;
  }
  .masthead h1 {
    font-family: 'UnifrakturMaguntia', cursive;
    font-size: clamp(48px, 8vw, 90px);
    letter-spacing: -1px;
    line-height: 1;
    color: var(--ink);
  }
  .masthead-sub {
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 6px;
    border-top: 1px solid var(--light-rule);
    padding-top: 8px;
  }

  /* ─── NAV ─── */
  nav {
    border-top: 3px double var(--rule);
    border-bottom: 3px double var(--rule);
    display: flex;
    justify-content: center;
    gap: 32px;
    padding: 6px 20px;
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
  }
  nav a {
    color: var(--ink);
    text-decoration: none;
  }
  nav a:hover { text-decoration: underline; }

  /* ─── LAYOUT ─── */
  .container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 20px;
  }

  .edition-label {
    text-align: center;
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    padding: 14px 0 4px;
  }

  .main-headline {
    text-align: center;
    padding: 20px 40px 0;
    border-bottom: 1px solid var(--light-rule);
    margin-bottom: 24px;
  }
  .main-headline .section-tag {
    font-family: 'Libre Baskerville', serif;
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--accent);
    display: block;
    margin-bottom: 8px;
  }
  .main-headline h2 {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: clamp(28px, 5vw, 52px);
    font-weight: 900;
    line-height: 1.1;
    margin-bottom: 12px;
  }
  .main-headline .deck {
    font-family: 'EB Garamond', serif;
    font-style: italic;
    font-size: 18px;
    color: var(--muted);
    max-width: 600px;
    margin: 0 auto 16px;
  }
  .byline {
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 16px;
  }

  /* ─── THREE COLUMN GRID ─── */
  .columns {
    display: grid;
    grid-template-columns: 1fr 1.8fr 1fr;
    gap: 0;
    border-top: 2px solid var(--rule);
    border-bottom: 2px solid var(--rule);
    margin-bottom: 32px;
  }
  .col {
    padding: 24px 22px;
    border-right: 1px solid var(--light-rule);
  }
  .col:last-child { border-right: none; }
  .col-feature { border-left: 1px solid var(--light-rule); }

  .col h3 {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: 22px;
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 10px;
  }
  .col .col-deck {
    font-style: italic;
    color: var(--muted);
    font-size: 15px;
    margin-bottom: 12px;
    border-bottom: 1px solid var(--light-rule);
    padding-bottom: 10px;
  }
  .col p {
    font-size: 15.5px;
    line-height: 1.7;
    margin-bottom: 12px;
    text-align: justify;
    hyphens: auto;
  }
  .col .pull-quote {
    border-top: 3px solid var(--rule);
    border-bottom: 1px solid var(--rule);
    padding: 12px 0;
    margin: 16px 0;
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-size: 18px;
    line-height: 1.4;
    color: var(--accent);
  }
  .col .section-label {
    font-family: 'Libre Baskerville', serif;
    font-size: 9.5px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--accent);
    display: block;
    margin-bottom: 6px;
  }
  .read-more {
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--accent);
    text-decoration: none;
    border-bottom: 1px solid var(--accent);
  }

  /* ─── DIVIDER ARTICLES ─── */
  .section-divider {
    border-top: 3px double var(--rule);
    padding-top: 10px;
    margin-bottom: 28px;
  }
  .section-divider h2 {
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
    text-align: center;
  }

  /* ─── SECOND SECTION: two articles side by side ─── */
  .two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0;
    border-top: 2px solid var(--rule);
    margin-bottom: 32px;
  }
  .two-col .art {
    padding: 24px 26px;
    border-right: 1px solid var(--light-rule);
  }
  .two-col .art:last-child { border-right: none; }
  .two-col h3 {
    font-family: 'Playfair Display', serif;
    font-size: 26px;
    font-weight: 700;
    line-height: 1.15;
    margin-bottom: 8px;
  }
  .two-col .art-deck {
    font-style: italic;
    color: var(--muted);
    margin-bottom: 12px;
    border-bottom: 1px solid var(--light-rule);
    padding-bottom: 10px;
  }
  .two-col p {
    font-size: 16px;
    line-height: 1.7;
    margin-bottom: 12px;
    text-align: justify;
    hyphens: auto;
  }

  /* ─── FOOTER ─── */
  footer {
    border-top: 4px solid var(--rule);
    padding: 20px;
    text-align: center;
    font-family: 'Libre Baskerville', serif;
    font-size: 11px;
    color: var(--muted);
    letter-spacing: 0.06em;
  }

  /* ─── SURPRISE BUTTON ─── */
  .surprise-wrap {
    text-align: center;
    padding: 36px 20px 44px;
    border-top: 3px double var(--rule);
  }
  .surprise-wrap p {
    font-family: 'EB Garamond', serif;
    font-style: italic;
    font-size: 16px;
    color: var(--muted);
    margin-bottom: 18px;
  }
  .btn-surprise {
    font-family: 'Playfair Display', serif;
    font-size: 14px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    background: var(--ink);
    color: var(--paper);
    border: 2px solid var(--ink);
    padding: 14px 40px;
    cursor: pointer;
    transition: background 0.2s, color 0.2s;
    font-weight: 700;
  }
  .btn-surprise:hover {
    background: var(--paper);
    color: var(--ink);
  }

  /* ─── DECORATIVE INITIAL CAP ─── */
  .dropcap::first-letter {
    font-family: 'Playfair Display', serif;
    font-size: 4.5em;
    font-weight: 900;
    float: left;
    line-height: 0.75;
    padding-right: 8px;
    padding-top: 6px;
    color: var(--ink);
  }

  .rule-ornament {
    text-align: center;
    font-size: 18px;
    color: var(--muted);
    margin: 8px 0;
  }

  @media (max-width: 720px) {
    .columns, .two-col { grid-template-columns: 1fr; }
    .col, .two-col .art { border-right: none; border-bottom: 1px solid var(--light-rule); }
    nav { flex-wrap: wrap; gap: 12px; }
  }
</style>
</head>
<body>

<!-- MASTHEAD -->
<header class="masthead">
  <div class="masthead-top">
    <span>Miércoles, 25 de febrero de 2026</span>
    <span>Historia · Civilización · Cultura</span>
    <span>Vol. CLXXIV · No. 60,412</span>
  </div>
  <h1>The Daily Tribune</h1>
  <p class="masthead-sub">"Todo el conocimiento que vale la pena imprimir"</p>
</header>

<!-- NAV -->
<nav>
  <a href="#">Mundo Antiguo</a>
  <a href="#">Civilizaciones</a>
  <a href="#">Literatura</a>
  <a href="#">Filosofía</a>
  <a href="#">Arte</a>
  <a href="#">Archivo</a>
</nav>

<div class="container">

  <p class="edition-label">Edición Especial — Civilizaciones del Mediterráneo</p>

  <!-- MAIN HEADLINE: GRECIA -->
  <div class="main-headline">
    <span class="section-tag">✦ Historia Antigua ✦</span>
    <h2>La Cuna de Occidente:<br>La Antigua Grecia y su Legado Eterno</h2>
    <p class="deck">Desde las polis de Atenas hasta la conquista de Alejandro, la civilización helénica redefinió la política, el arte y el pensamiento humano para siempre.</p>
    <p class="byline">Por la Redacción de Historia &nbsp;·&nbsp; Atenas, Grecia</p>
  </div>

  <!-- THREE COLUMNS: GRECIA -->
  <div class="columns">
    <div class="col">
      <span class="section-label">Geografía & Orígenes</span>
      <h3>El Mar que Forjó una Civilización</h3>
      <p class="col-deck">Un territorio de montañas y costas que transformó el destino de Europa.</p>
      <p class="dropcap">El territorio griego, compuesto por montañas escarpadas, valles estrechos e incontables islas en el mar Egeo, fue determinante en la formación de una civilización única. Esta geografía accidentada impidió la unificación política bajo un solo soberano, dando lugar a las polis: ciudades-estado independientes con gobiernos, leyes y culturas propias.</p>
      <p>Entre ellas destacaron Atenas y Esparta, rivales en modelo político pero unidas por el idioma y la religión. El mar, lejos de ser un obstáculo, fue la gran autopista de los helenos, quienes establecieron colonias desde el mar Negro hasta las costas de Iberia.</p>
      <div class="pull-quote">"El territorio griego no limitó a los helenos; los lanzó al mundo."</div>
      <p>El clima templado favoreció cultivos esenciales como el olivo y la vid, pilares de su economía y del comercio mediterráneo.</p>
    </div>

    <div class="col col-feature">
      <span class="section-label">Etapas Históricas</span>
      <h3>De Creta a Alejandría: Cinco Siglos de Transformación</h3>
      <p class="col-deck">La historia griega es una sucesión de civilizaciones que se construyeron y destruyeron mutuamente.</p>
      <p class="dropcap">La primera gran cultura del Egeo floreció en Creta entre el 3000 y el 1450 a.C. Los minoicos construyeron el asombroso palacio de Cnosos, desarrollaron el sistema de escritura Lineal A y mantuvieron rutas comerciales con Egipto. Su arte, lleno de colores vivos y escenas marinas, refleja una sociedad próspera y relativamente pacífica.</p>
      <p>Los micénicos, en la Grecia continental, representaron el polo opuesto: guerreros organizados en ciudades amuralladas que escribieron en Lineal B y cuyas hazañas inspirarían la épica griega. La Guerra de Troya, narrada por Homero siglos después, probablemente tenga raíces en conflictos de esta época.</p>
      <p>Tras el colapso de la civilización micénica, la Edad Oscura (1100–800 a.C.) sumió a Grecia en el silencio: desapareció la escritura, el comercio decayó y las ciudades fueron abandonadas. Sin embargo, las tradiciones orales sobrevivieron, portando en su seno los gérmenes de los grandes poemas épicos.</p>
      <div class="pull-quote">"La Edad Oscura no fue el fin; fue el silencio antes de la sinfonía."</div>
      <p>La Época Arcaica (800–500 a.C.) trajo el renacer: surgieron formalmente las polis, se adoptó el alfabeto fenicio y se redactaron las primeras leyes escritas. Los griegos comenzaron a preguntarse no solo cómo vivir, sino por qué.</p>
      <p>La Época Clásica (500–323 a.C.) fue el cénit: democracia ateniense, Guerras Médicas contra Persia, y el florecimiento de Sócrates, Platón y Aristóteles. Finalmente, Alejandro Magno extendió la cultura griega hasta la India, inaugurando la Época Helenística y centros del saber como la Biblioteca de Alejandría.</p>
      <a href="#" class="read-more">Continúa en página B4 →</a>
    </div>

    <div class="col">
      <span class="section-label">Literatura Griega</span>
      <h3>Homero, el Teatro y la Palabra Inmortal</h3>
      <p class="col-deck">De los poemas épicos al drama, la escritura griega sentó las bases de toda la literatura occidental.</p>
      <p class="dropcap">Homero, cuya existencia histórica aún se debate, es el pilar de la literatura griega. La Ilíada narra la cólera de Aquiles durante la Guerra de Troya; la Odisea, el largo retorno de Ulises a Ítaca. Ambas obras, compuestas en el siglo VIII a.C., siguen siendo estudiadas como cumbres de la expresión humana.</p>
      <p>Hesíodo añadió otra dimensión: en la Teogonía explicó el origen del cosmos y los dioses; en Los trabajos y los días, reflexionó sobre la justicia y el esfuerzo del hombre común.</p>
      <div class="pull-quote">"El teatro griego no era entretenimiento; era medicina del alma."</div>
      <p>La Época Clásica vio nacer el teatro. Sófocles exploró el destino y la tragedia en Edipo Rey; Eurípides desafió las normas sociales en Medea; Aristófanes satirizó la política con corrosiva comedia. Miles de ciudadanos se reunían en anfiteatros al aire libre para compartir estas experiencias colectivas.</p>
      <p>La época helenística añadió una poesía más íntima e individualista, y la gran Biblioteca de Alejandría preservó el saber del mundo conocido.</p>
    </div>
  </div>

  <!-- SECTION DIVIDER -->
  <div class="section-divider">
    <h2>✦ &nbsp; Segunda Edición — Imperios y Poder &nbsp; ✦</h2>
  </div>

  <!-- MAIN HEADLINE: ROMA -->
  <div class="main-headline">
    <span class="section-tag">✦ Civilizaciones ✦</span>
    <h2>Roma Aeterna: El Imperio que<br>Inventó el Mundo Moderno</h2>
    <p class="deck">De una aldea a orillas del Tíber surgió la maquinaria política y cultural que definiría el derecho, la arquitectura y los idiomas de Occidente por dos milenios.</p>
    <p class="byline">Por la Redacción de Historia &nbsp;·&nbsp; Roma, Italia</p>
  </div>

  <!-- TWO COLUMNS: ROMA -->
  <div class="two-col">
    <div class="art">
      <span class="section-label">Fundación & República</span>
      <h3>De Rómulo al Senado: Los Siglos que Formaron una Superpotencia</h3>
      <p class="art-deck">La leyenda y la historia se entrelazan en los orígenes de la ciudad eterna.</p>
      <p class="dropcap">Según la tradición, Roma fue fundada en el 753 a.C. por Rómulo, quien, junto a su hermano Remo, fue amamantado por una loba y luego estableció la ciudad sobre las siete colinas a orillas del Tíber. Rómulo se convirtió en el primer rey y dio nombre a la ciudad. Durante la Monarquía (753–509 a.C.), la influencia etrusca fue determinante en la religión, la ingeniería y la organización urbana.</p>
      <p>En el 509 a.C., los romanos expulsaron a su último rey y crearon la República Romana. El poder se repartió entre el Senado —dominado por los patricios— y magistraturas electas. Los plebeyos libraron largas luchas para obtener representación, logrando hitos como la publicación de las Leyes de las Doce Tablas.</p>
      <p>La República fue también una era de conquista. Las Guerras Púnicas contra Cartago, con figuras como Aníbal cruzando los Alpes con elefantes, consolidaron a Roma como potencia mediterránea. El período culminó con la crisis entre César, Pompeyo y Craso, y el inevitable paso hacia el Imperio.</p>
      <div class="pull-quote" style="border-top:3px solid var(--rule);border-bottom:1px solid var(--rule);padding:12px 0;margin:16px 0;font-family:'Playfair Display',serif;font-style:italic;font-size:18px;line-height:1.4;color:var(--accent)">"Roma no se construyó en un día, pero sí se pensó como si fuera para siempre."</div>
    </div>
    <div class="art">
      <span class="section-label">Imperio & Legado</span>
      <h3>De la Pax Romana a la Caída: El Arco Completo de un Coloso</h3>
      <p class="art-deck">En su apogeo, Roma controló desde Britannia hasta Egipto. En su caída, legó el mundo que habitamos.</p>
      <p class="dropcap">En el 27 a.C., Octavio Augusto se convirtió en el primer emperador, inaugurando una era de relativa paz interior conocida como la Pax Romana. Bajo el Imperio se construyeron miles de kilómetros de calzadas, acueductos que abastecían a ciudades enteras, anfiteatros como el Coliseo y arcos triunfales que aún permanecen en pie.</p>
      <p>La sociedad romana era estratificada: patricios en la cúspide, plebeyos, clientes y esclavos en distintos peldaños. La religión politeísta, que adaptó los dioses griegos con nombres latinos —Júpiter por Zeus, Marte por Ares—, era inseparable de la vida pública y política.</p>
      <p>La literatura floreció con Virgilio (la Eneida), Cicerón (retórica y filosofía), Ovidio (Metamorfosis) y Tito Livio (historia de Roma). La filosofía estoica de Séneca influyó en emperadores y ciudadanos por igual.</p>
      <p>El Imperio se fragmentó internamente por corrupción, crisis económicas y presiones en las fronteras. En el 476 d.C., el último emperador romano de Occidente fue depuesto por el líder germánico Odoacro, cerrando formalmente una era. Pero el legado de Roma —el derecho, el latín como raíz de los idiomas romances, la arquitectura, el urbanismo— nunca desapareció. Simplemente se convirtió en el mundo moderno.</p>
      <a href="#" class="read-more">Continúa en página C6 →</a>
    </div>
  </div>

  <!-- SECTION DIVIDER -->
  <div class="section-divider">
    <h2>✦ &nbsp; Perfil — Grandes Figuras de la Historia &nbsp; ✦</h2>
  </div>

  <!-- STEVE JOBS ARTICLE -->
  <div class="main-headline">
    <span class="section-tag">✦ Necrología & Legado ✦</span>
    <h2>Steve Jobs: El Tirano Gentil<br>que Reinventó el Siglo XXI</h2>
    <p class="deck">De un garaje en Silicon Valley a la empresa más valiosa del mundo: la historia de un hombre que no aceptaba el "imposible" como respuesta.</p>
    <p class="byline">Por la Redacción de Tecnología &nbsp;·&nbsp; Cupertino, California</p>
  </div>

  <div class="columns">
    <div class="col">
      <span class="section-label">Primeros Años</span>
      <h3>El Niño Adoptado de Silicon Valley</h3>
      <p class="col-deck">Una infancia entre destornilladores y placas de circuito que prefiguraba un destino extraordinario.</p>
      <p class="dropcap">Steven Paul Jobs nació el 24 de febrero de 1955 en San Francisco, hijo biológico de un estudiante sirio y una joven estadounidense que decidieron darlo en adopción. Paul y Clara Jobs, una familia de clase media en Mountain View, lo acogieron y criaron en una zona que la historia recordaría como Silicon Valley.</p>
      <p>Su padre adoptivo, mecánico de oficio, le enseñó desde niño a desmontar y remontar aparatos electrónicos. Esa curiosidad técnica se convertiría en pasión cuando, en la secundaria, conoció a Steve Wozniak: un genio de la electrónica con quien compartiría la aventura más importante de sus vidas.</p>
      <p>En 1972 ingresó al Reed College pero abandonó a los seis meses. Sin embargo, siguió asistiendo como oyente a clases que le interesaban, entre ellas caligrafía —conocimiento que años después moldearía la tipografía del primer Macintosh.</p>
      <div class="pull-quote">"La creatividad es solo conectar puntos. Cuando conectas suficientes, cambia el mundo." — Jobs</div>
    </div>

    <div class="col col-feature">
      <span class="section-label">La Epopeya de Apple</span>
      <h3>Del Garaje al Olimpo: Cómo un Visionario Transformó Cuatro Industrias</h3>
      <p class="col-deck">La historia de Apple es inseparable de la de Jobs: sus caídas y renacimientos reflejan los de la empresa.</p>
      <p class="dropcap">En 1976, en el garaje familiar, Jobs, Wozniak y Ronald Wayne fundaron Apple Computer. El Apple I fue un experimento; el Apple II, una revolución que popularizó la computadora personal. En 1984, el Macintosh —con su interfaz gráfica y ratón— cambió para siempre la relación entre el ser humano y la máquina. Su anuncio, dirigido por Ridley Scott y emitido en el Super Bowl, se convirtió en leyenda publicitaria.</p>
      <p>Pero el éxito no duró. Conflictos con el CEO John Sculley derivaron en la salida de Jobs de la empresa que él mismo había fundado. En lugar de rendirse, fundó NeXT —cuyo sistema operativo sería clave en el futuro— y adquirió una pequeña división de animación de Lucasfilm que se convertiría en Pixar.</p>
      <p>Bajo su liderazgo, Pixar produjo en 1995 Toy Story, la primera película animada completamente por computadora. Siguieron Buscando a Nemo y Los Increíbles, hasta que Disney adquirió Pixar en 2006, convirtiendo a Jobs en el mayor accionista individual de la compañía del ratón.</p>
      <div class="pull-quote">"La innovación distingue a un líder de un seguidor."</div>
      <p>En 1997 Apple adquirió NeXT, y Jobs regresó. Lo que encontró era una empresa al borde de la quiebra. Lo que dejó, catorce años después, era la compañía más valiosa del mundo: el iMac, el iPod, iTunes, el iPhone y el iPad habían redefinido la informática, la música, la telefonía y los medios digitales.</p>
      <p>Diagnosticado con cáncer de páncreas en 2004, Jobs continuó trabajando durante años mientras su salud se deterioraba. Renunció como CEO el 24 de agosto de 2011 y falleció el 5 de octubre de ese año en Palo Alto, California, a los 56 años. El mundo entero hizo silencio.</p>
      <a href="#" class="read-more">Continúa en página D2 →</a>
    </div>

    <div class="col">
      <span class="section-label">Legado</span>
      <h3>Lo que Jobs Dejó: Más que Gadgets</h3>
      <p class="col-deck">El impacto de un visionario que se negó a separar la tecnología de la humanidad.</p>
      <p class="dropcap">El legado de Steve Jobs trasciende los productos que lanzó. Fue el primero en demostrar que el diseño y la tecnología no son disciplinas separadas, sino que la belleza de un objeto puede ser tan revolucionaria como su función. Cada detalle de los productos Apple —desde el embalaje hasta la interfaz— llevaba su sello perfeccionista.</p>
      <p>Popularizó la computadora personal, reinventó la distribución de música digital, transformó la industria del cine animado y creó el concepto moderno de smartphone. El iPhone no solo cambió los teléfonos; reorganizó economías enteras alrededor de los ecosistemas digitales.</p>
      <div class="pull-quote">"La muerte es la mejor invención de la vida. Nos recuerda que no tenemos nada que perder." — Jobs, Stanford 2005</div>
      <p>Su discurso de 2005 ante los graduados de Stanford —"Stay hungry, stay foolish"— se convirtió en uno de los textos más citados del siglo XXI. Hoy, Apple continúa siendo una de las empresas más valiosas del planeta, monumento viviente a la visión de un hombre que nunca aceptó los límites del mundo tal como era.</p>
    </div>
  </div>

  <!-- SURPRISE BUTTON -->
  <div class="surprise-wrap">
    <p class="rule-ornament">— ✦ —</p>
    <p>¿Ha disfrutado esta edición especial? Tenemos un obsequio exclusivo para nuestros lectores más fieles.</p>
    <button class="btn-surprise" onclick="window.open('https://www.youtube.com/watch?v=dQw4w9WgXcQ','_blank')">
      🎁 &nbsp; Sorpresa para el Lector &nbsp; 🎁
    </button>
    <p style="margin-top:14px;font-size:13px;font-style:italic;color:#999;">Oferta exclusiva · Solo por tiempo limitado · No se arrepentirá</p>
  </div>

</div><!-- /container -->

<footer>
  <p style="font-size:14px;font-family:'UnifrakturMaguntia',cursive;margin-bottom:6px;">The Daily Tribune</p>
  <p>© 2026 The Daily Tribune Company · Historia, Cultura y Civilización · Todos los derechos reservados</p>
  <p style="margin-top:6px;">"Impreso desde 1851 · Ahora también en su pantalla"</p>
</footer>

</body>
</html>
