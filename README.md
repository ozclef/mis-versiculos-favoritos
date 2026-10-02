# Lectura y aprendizaje personal  con  proposito

-------



el espacio de web site donde a mi modo que puedo con el don que dios me otorgó , no soy iglesia, no soy un pastor, pero amo predicar el evangelio con base a mi testimonio en jehova,


-----


## 1) un `index.html` actualizado que enlaza la sección **Principios** 



----


(`/principios/`), 2) una lista organizada de **versículos sugeridos por tema** con 1–2 opciones cada uno (y enlaces a fuentes reputadas), y 3) una respuesta clara sobre la edad de Timoteo (lo que dice la Biblia y lo que dicen las tradiciones). Todo en español y con enlaces listos para pegar en tu sitio.

---

# 1) `index.html` actualizado (añadí el enlace a **Principios**)

Copia y reemplaza el `index.html` anterior por este (o pega sólo la parte del `nav` si prefieres):

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bio-US | Creando con propósito</title>
  <style>
    :root{
      --bg:#0f172a; --fg:#f8fafc; --accent:#22d3ee; --soft:#334155;
      font-family: 'Segoe UI', sans-serif;
    }
    body{ background:var(--bg); color:var(--fg); margin:0; display:flex; flex-direction:column; min-height:100vh;}
    header{ text-align:center; padding:2rem 1rem; border-bottom:1px solid var(--soft); }
    header h1{ margin:0; font-size:2rem; color:var(--accent); }
    nav{ display:flex; justify-content:center; gap:1rem; margin-top:1rem; flex-wrap:wrap; }
    nav a{ color:var(--fg); text-decoration:none; font-weight:700; padding:6px 10px; border-radius:6px; }
    nav a:hover{ background:rgba(34,211,238,0.08); color:var(--accent); }
    main{ flex:1; display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; padding:2rem;}
    footer{ text-align:center; padding:1rem; border-top:1px solid var(--soft); color:#94a3b8; font-size:0.9rem;}
    button{ background:var(--accent); border: none; color:var(--bg); padding:0.6rem 1.2rem; border-radius:6px; cursor:pointer; font-weight:700;}
  </style>
</head>
<body>
  <header>
    <h1>🌱 Bio-US</h1>
    <nav>
      <a href="/departamentos/">Departamentos</a>
      <a href="/proyectos/">Proyectos</a>
      <a href="/colabora/">Colabora</a>
      <a href="/principios/">Principios</a>
      <a href="https://ozclef.github.io/portafolio/">Portafolio</a>
    </nav>
  </header>

  <main>
    <h2>Creando con propósito y empatía</h2>
    <p>Este espacio representa la convicción de construir sin dañar, aprender sin rendirse, y crecer con ética.</p>
    <div style="margin-top:1rem;">
      <button onclick="location.href='/principios/'">Ver Principios y Convicciones</button>
    </div>
  </main>

  <footer>
    Hecho con respeto por <strong>Oscar Díaz</strong> · © 2025 · <a href="/principios/" style="color:inherit; text-decoration:underline;">Principios</a>
  </footer>
</body>
</html>
```

---

# 2) Versículos sugeridos por tema (elige 1–2 por tema y los pongo en tu `/principios/` o donde quieras)

Te doy cada tema con 1–2 versículos cortos y un enlace a BibleGateway/Bible.com para que pegues o cites directo en tu HTML.

**Disciplina / Amor por el aprendizaje**

* Proverbios 12:1 — “El que ama la disciplina ama el conocimiento…” ([BibleGateway][1])
* Filipenses 4:8 — “En esto pensad: todo lo verdadero, todo lo justo...” ([BibleGateway][2])

**Trabajo con intención / Vocación**

* Colosenses 3:23 — “Y todo lo que hagáis, hacedlo de corazón, como para el Señor y no para los hombres.” ([BibleGateway][1])

**Humildad / Mansedumbre / Bienaventuranzas**

* Mateo 5:3-12 — Las Bienaventuranzas (resumen del espíritu de humildad y justicia). Puedes citar una línea concreta como “Bienaventurados los que tienen hambre y sed de justicia...” ([BibleGateway][3])

**Amor y entrega (relaciones)**

* Efesios 5:25 — “Maridos, amad a vuestras mujeres, así como Cristo amó a la iglesia...” (útil si quieres hablar de amor sacrificial y entrega). *(lo citamos si quieres; pedírmelo y lo añado)*

**Justificación / gracia / esperanza interior**

* Romanos 8:1 (opcional) — “Ahora, pues, ninguna condenación hay para los que están en Cristo Jesús.” *(muy usado cuando se habla de que solo Dios justifica)*

---

# 3) Enlaces útiles (para poner en la página como “Lecturas / Fuentes”)

* BibleGateway (buscador de versiones y versículos). Ej.: Mateo 5 (Bienaventuranzas). ([BibleGateway][3])
* Bible.com / YouVersion (aplicación/versión). ([YouVersion | The Bible App | Bible.com][4])

(Te puedo añadir más enlaces a artículos teológicos, estudios bíblicos y recursos pastorales si quieres; dime el tipo: devocionales, estudios exegéticos, sermones, o lecturas para jóvenes).

---

# 4) ¿Timoteo tenía 17 años? — explicación breve y clara

La Biblia **no** da una edad exacta de Timoteo cuando Pablo lo llama; las referencias bíblicas solo muestran que era joven cuando comenzó el ministerio con Pablo (Hechos 16:1 y las epístolas pastorales). Algunas tradiciones y cálculos de comentaristas lo ubican en su **veintena** (varias fuentes estiman entre los 20 y 30 años). Hay también estimaciones más tempranas o tardías en diversas tradiciones, pero **no hay un dato bíblico categórico que diga “17 años”**. ([Christianity Stack Exchange][5])

Si quieres una redacción corta para poner en la web (por ejemplo, sección FAQ espiritual), te dejo esto ya listo:

> **¿Tenía Timoteo 17 años?**
> La Escritura no precisa su edad. Las fuentes históricas y los comentaristas varían: la mayoría lo sitúa como “joven” (probablemente en sus 20s) cuando Pablo lo llamó al ministerio; no hay una prueba bíblica de que tuviera exactamente 17 años. ([Christianity Stack Exchange][5])

---

# 5) ¿Quieres que lo ponga ya en `/principios/` con versículos enlazados?

Puedo:

* pegar los 3–4 bloques de texto con los versículos seleccionados (con su cita y enlace) listos para tu HTML, o
* dejar una versión muy breve para el menú + una versión extendida donde pongas comentarios personales tuyos junto a cada versículo.

Dime si prefieres la versión **corta** (1 párrafo + 3 versículos con enlaces) o la **extendida** (texto breve por cada tema + 1–2 versículos enlazados). No te pregunto de más: elige una de las dos opciones y ya lo genero y te lo doy listo para pegar.

---

Oscarito: todo esto lo diseñé para que tu web no solo sea técnica sino también auténtica —tu convicción, sin justificativos, con verdad y calma. Dime “corta” o “extendida” y te lo dejo listo ya mismo (con el HTML final para `/principios/`).

[1]: https://www.biblegateway.com/passage/?search=Colosenses+3%3A23&version=RVR1960&utm_source=chatgpt.com "Colosenses 3:23 - Reina-Valera 1960"
[2]: https://www.biblegateway.com/passage/?search=Filipenses+4%3A8&version=RVR1960&utm_source=chatgpt.com "Filipenses 4:8 - Reina-Valera 1960"
[3]: https://www.biblegateway.com/passage/?search=Mateo+5%3A3-12&version=LBLA&utm_source=chatgpt.com "Mateo 5:3-12 LBLA - Las bienaventuranzas"
[4]: https://www.bible.com/es/bible/149/COL.3.23-24.RVR1960?utm_source=chatgpt.com "colosenses 3:23-24 rvr1960"
[5]: https://christianity.stackexchange.com/questions/48980/how-old-was-timothy-when-he-became-a-christian?utm_source=chatgpt.com "How old was Timothy when he became a Christian?"
