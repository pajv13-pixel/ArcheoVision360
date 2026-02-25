<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>ArchaeoVision 360</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-image: url("https://upload.wikimedia.org/wikipedia/commons/4/4e/Tikal_Temple_I.jpg");
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    color: white;
}

.overlay {
    background: rgba(0,40,0,0.80);
    min-height: 100vh;
}

/* MENÚ */
nav {
    background-color: rgba(0,0,0,0.85);
    padding: 15px;
    text-align: center;
}

nav a {
    color: #90ee90;
    margin: 0 20px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: yellow;
}

/* CONTENIDO */
.container {
    text-align: center;
    padding: 40px;
    animation: fadeIn 2s ease-in;
}

.section {
    background-color: rgba(0,0,0,0.65);
    margin: 25px auto;
    padding: 25px;
    border-radius: 15px;
    max-width: 900px;
    text-align: justify;
}

h1 {
    font-size: 50px;
}

h2 {
    text-align: center;
    color: #90ee90;
}

.links {
    background-color: rgba(0,0,0,0.6);
    display: inline-block;
    padding: 25px;
    border-radius: 15px;
}

.links a {
    display: block;
    color: #90ee90;
    margin: 12px 0;
    font-size: 18px;
    text-decoration: none;
}

.links a:hover {
    color: yellow;
}

/* símbolos */
.maya-left, .maya-right {
    position: fixed;
    top: 50%;
    font-size: 60px;
    opacity: 0.3;
}

.maya-left { left: 10px; }
.maya-right { right: 10px; }

@keyframes fadeIn {
    from {opacity:0;}
    to {opacity:1;}
}
</style>
</head>

<body>

<div class="overlay">

<nav>
<a href="#">Inicio</a>
<a href="#">Videos</a>
<a href="#">Proyecto</a>
</nav>

<div class="container">

<h1>ArchaeoVision 360</h1>
<h2>Links de videos 360 de arqueología en Youtube</h2>

<div class="links">
<a href="https://youtu.be/VNsgC2Jsza8?si=ELsS0TbsNyTTAggB" target="_blank">Video 360 - Arqueología 1</a>
<a href="https://youtu.be/VA2elnKhO88?si=JXo5gju9AeT0j54z" target="_blank">Video 360 - Arqueología 2</a>
<a href="https://youtu.be/v3bDMldpaLs?si=uDpK_j-enr9X5r3_" target="_blank">Video 360 - Arqueología 3</a>
<a href="https://youtu.be/fQ3s3I6ihHE?si=HYlnTOn1VzlR9AH1" target="_blank">Video 360 - Arqueología 4</a>
</div>

<!-- PLANTEAMIENTO -->
<div class="section">
<h2>Planteamiento del problema</h2>
<p>
Muchos sitios arqueológicos de Guatemala son difíciles de visitar debido a la distancia,
los costos y las limitaciones de acceso, por lo que no todas las personas —
especialmente estudiantes y comunidades escolares— tienen la oportunidad de conocerlos
y aprender de su historia. Esto limita el acceso al patrimonio cultural y la experiencia educativa directa.
</p>

<p>
Por ello, se necesita una alternativa accesible que permita que cualquier persona pueda vivir
y explorar virtualmente estos lugares. A través de videos en 3D y lentes elaborados con papel
y cartón, los estudiantes y el público en general podrán experimentar los sitios arqueológicos
de manera inmersiva, promoviendo el aprendizaje y contribuyendo a la preservación física de las ruinas.
</p>
</div>

<!-- IMPORTANCIA -->
<div class="section">
<h2>¿Por qué es importante resolverlo?</h2>
<p>
Acercar los sitios arqueológicos a todas las personas fortalece la identidad cultural
y el aprendizaje histórico desde edades tempranas. Además, permite preservar físicamente
las ruinas al ofrecer una forma alternativa de explorarlas sin causar desgaste por visitas masivas.
</p>
</div>

<!-- OBJETIVO GENERAL -->
<div class="section">
<h2>Objetivo general</h2>
<p>
Crear una experiencia inmersiva en 3D que permita a cualquier persona explorar sitios
arqueológicos de Guatemala usando lentes hechos con papel y cartón,
promoviendo aprendizaje y preservación.
</p>
</div>

<!-- OBJETIVOS -->
<div class="section">
<h2>Objetivos específicos</h2>
<ul>
<li>Diseñar videos arqueológicos en formato 3D accesible.</li>
<li>Construir lentes caseros de bajo costo.</li>
<li>Permitir que estudiantes vivan una visita virtual al sitio.</li>
<li>Promover el cuidado del patrimonio cultural.</li>
<li>Facilitar acceso educativo inclusivo.</li>
</ul>
</div>

</div>

<div class="maya-left">𓂀</div>
<div class="maya-right">𓆣</div>

<audio autoplay loop>
<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

</div>

</body>
</html>
