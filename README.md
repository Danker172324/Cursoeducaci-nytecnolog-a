<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Website Layout</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 1;
  background-image: url("Fondo_Hueso.jpg"); 
}

/* Style the header */
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Left and right column */
.column.side_1 {
  padding: 1px 10px;
  background-position:  left top;
  background-repeat: no-repeat, repeat;
 text-align: Center;
  width: 47% ;
margin: 10;
}

/* Middle column */
.column.middle {
margin: 1;
  background-position:  left top;
  background-repeat: no-repeat, repeat;
  padding: 150px 10px;
  width: 50%;
  text-align: left;
}
.column.middle_2 {
margin: 1;
  background-position:  left top;
  background-repeat: no-repeat, repeat;
  padding: 150px 10px;
  width: 100%;
  text-align: left;
border: 1px solid lightblue;
}

/* Create three unequal columns that floats next to each other */
.column {

  border: 1px solid black;
  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 5px;
  margin-left: 5px;
  background-color: lightblue;

  float: left;
  padding: 1px 2px;
text-align: left;
}


}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;

}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 500px) {
  .column.side, .column.middle {
    width: 300%;
  }
}

/* Style the footer */
.footer {
  background-color: orange;
  padding: 100px;
  text-align: center;
}
.hero-image {
padding: 100px;
  background-image: url("Kandisky.png");
  background-color: #cccccc;
  
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-image-1 {
padding: 100px;
  background-image: url("Centro.png");
  background-color: #cccccc;
  
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

div.relative {
  position: relative;
  margin: 3;
  left: 30px;
  width: 280px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Centro.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 400px;
} 

div.absolute {
  position: absolute;
  top: 70px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 1px opacity: 0.33;
}

div.absolute_1 {
  position: absolute;
  top: 70px;
  right: 406px;
  width: 100px;
  height: 100px;
  border: 1px opacity: 0.33;
}

div.absolute_18 {
  position: absolute;
  top: 330px;
  right: 1px;
  width: 100px;
  height: 100px;
  border: 1px opacity: 0.33;
}

div.absolute_2 {
  position: absolute;
  top: 240px;
  right: 570px;
  width: 650px;
  height: 260px;
  border: 1px solid #73AD21;
}
div.relative_2 {
  position: relative;
  margin: 3;
  left: 30px;
  width: 80px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Rupestre.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 300px;
} 

div.relative_1 {
  position: relative;
  margin: 3;
  left: 30px;
  width: 80px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Rupestre.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 300px;
} 
div.relative_3 {
  position: relative;
  margin: 3;
  left: 30px;
  width: 80px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Rupestre.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 300px;
}
div.relative_4 {
  position: relative;
  margin: 3;
  left: 30px;
  width: 80px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Rupestre.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 300px;
}
div.relative_5 {
  position: relative;
  margin: 3;
  left: 30px;
  width: 80px;
  height: 10px;
  border: 1px solid lightblue;

background-image: url(Rupestre.png);
  background-position: 50% 50%;
  background-repeat: no-repeat, repeat;
  padding: 250px 250px;
  width: 50%;
  background-size: 300px;
}
div.absolute_3 {
  position: absolute;
  top: 225px;
  right: 1px;
  width: 450px;
  height: 260px;
  border: 1px solid lightblue;
}
div.absolute_4 {
  position: absolute;
  top: 160px;
  right: 1px;
  width: 400px;
  height: 260px;
  border: 1px solid lightblue;
}
div.absolute_7 {
  position: absolute;
  top: 80px;
  right: 1px;
  width: 450px;
  height: 100px;
  border: 1px solid lightblue;
}
div.absolute_9 {
  position: absolute;
  top: 80px;
  right: 1px;
  width: 450px;
  height: 100px;
  border: 1px solid lightblue;
}
div.absolute_10 {
  position: absolute;
  top: 225px;
  right: 1px;
  width: 450px;
  height: 260px;
  border: 1px solid lightblue;
}
div.absolute_11 {
  position: absolute;
  top: 80px;
  right: 1px;
  width: 450px;
  height: 100px;
  border: 1px solid lightblue;
}
div.absolute_12 {
  position: absolute;
  top: 280px;
  right: 1px;
  width: 450px;
  height: 260px;
  border: 1px solid lightblue;
}
div.absolute_13 {
  position: absolute;
  top: 80px;
  right: 1px;
  width: 450px;
  height: 100px;
  border: 1px solid lightblue;
}
div.absolute_14 {
  position: absolute;
  top: 235px;
  right: 1px;
  width: 450px;
  height: 260px;
  border: 1px solid lightblue;
}
div.absolute_15 {
  position: absolute;
  top: 535px;
  right: 1px;
  width: 450px;
  height: 260px;
  border: 1px opacity: 0.33;
}
div.absolute_16 {
  position: absolute;
  top: 135px;
  right: 700px;
  width: 450px;
  height: 260px;
  border: 1px opacity: 0.33;
}
div.absolute_17 {
  position: absolute;
  top: 400px;
  right: 700px;
  width: 450px;
  height: 260px;
  border: 1px opacity: 0.33;
}
div.absolute_8 {
  position: absolute;
  top: 20px;
  right: 1px;
  width: 450px;
  height: 100px;
  border: 1px solid lightblue;
}

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

</style>
</head>
<body>
 
<div class="header">
  <div class="hero-image">
  <div class="hero-text">
    <h1 style="font-size:50px">¡Hola!, soy Darwin</h1>
    <h3>Y seré tu guía en este sitio</h3>
    <button>Contactame</button>
  </div>
</div>
</div>

<div class="topnav">
  <a href="https://phet.colorado.edu/en/simulation/color-vision"target="_blank">Simulador uno</a>
  <a href="https://phet.colorado.edu/en/simulation/bending-light" target="_blank">Simulador dos</a>
  <a href="https://phet.colorado.edu/en/simulation/wave-interference" target="_blank">Simulador tres</a>
</div>

<div class="row">
<div class="column middle_1">
    <h2>¡Bienvenidos!</h2>
    <p>El estudio de la ciencia es de por si complicado , requiere vasta cultura e interés, además de conciencia de su valor, más en este mundo moderno. La complejidad de los temas depende en gran parte del área especifica en la que se vaya a profundizar.</p>
    <p>Este espacio, para continuar con la tradición de publicar y divulgar los descubrimientos y definiciones sobre diversos tópicos de la luz, que creemos de valiosa utilidad para la familia, para el educador, para el estudiante, para el profesional. Presentamos ahora un compilado de los temaeios de Ciencia Visual. </p>
	<p>Para los siempre curiosos y amantes del arte y la ciencia va a ser un grato regalo a nivel cultural. </p>
<h2>La Generación de la Luz</h2>
    <p>En un momento remoto de la antigüedad, los seres humanos aprendieron a controlar el fuego. al principio tenían que encontrrlo y conservarlo. Apilaban ramas y mantenian el fuego vivo tanto tiempo como podían. Si la llamas se apagaban, partían a la busqueda de un nuevo fuego. Más tarde aprendierón a encender uno por ellos mismos. Golpeaban dos piedras hasta que saltaban chispas o frotaban dos trozos de madera hasta que generarar suficiente calor para, en uno u otro caso, iniciar una hoguera con yesca seca. Una vez que dominaron esta técnica pudieron obtener calor y luz siempre que lo precisaron.</p>
</div>
  </div>

<div class="row">
<div class="column middle">
    <h2>Sustracción de Colores</h2>
    <p>Todos los objetos visibles emiten luz, pero lo hacen de dos maneras distintas. Algunos objetos son fuentes luminosas, es decir, emiten luz. Por ejemplo, una linterna genera luz utilizando energía eléctrica para calentar un filamento. Si se alumbra una pared con esa linterna, ésta reflejará la luz pero no será fuente luminosa por sí misma. El color de los objetos que no emitén luz por sí mismos se obtienen por sustracción. Reciben luz blanca y absorben algunos colores al tiempo que reflejan o transmiten otros. Las hojas se ven verdes porque son capaces de absorver todos los colores excepto uno: el verde, que es el que reflejan y, por lo tanto, es el que puede persibir el ojo. Hace siglos que se conoce que algunas sustancias son especialmente buenas para sustraer colores. Esas sustancias se emplean en la fabricación de pigmentos, colorantes, pinturas y tintas, y hacen que nuestro mundo sea un lugar más colorido no sólo añadiendole colores sino también restándoselos.</p>
    </div>

<div class="column side_1">
    <h2>Colores Remanentes</h2>
    <div class="relative">;
  <div class="absolute">El triangulo absorbe el rojo de la luz blanca pero deja el verde y el azul. El cerebro los suma y se obtiene el Cian.</div>
 <div class="absolute_1">El cuadrado absorbe el verde de la luz blanca pero deja el azul y el rojo. El cerebro los suma y se obtiene el magenta.</div>
<div class="absolute_18">El círculo absorbe el azul de la luz blanca pero deja el verde y el rojo. El cerebro los suma y se obtiene el amarillo.</div>

</div>


  </div>

<div class="row">
<div class="column middle">
    <center><h2>Los Colorantes De Los Alimentos</h2></center>
   <div class="relative_2">;
  <div class="absolute_4"><img src="Captuz.jpg" alt="Captuz" style="width:80%"></div>
<div class="absolute_8">En la actualidad se emplea un gran número de sustancias artificiales para intensificar el color natural de los alimentos. En la antigüedad estos colorantes se extraían de plantas y animales. De la cochinilla, un pequeño insecto que se alimenta de un cierto tipo de captuz, se obtiene un tipo de color escarlata brillante. Era necesario capturar laboriosamente los insectos a mano y machacarlos para extraer el pigmento. </div>
 </div>
</div>

<div class="column side_1">
    <h2>Pinturas Rupestres</h2>
    <div class="relative_1">;
  <div class="absolute_3"><img src="Toro.jpg" alt="Toro" style="width:70%"></div>
<div class="absolute_7">Las pinturas rupestres constituyen los vestigios más antiguos del arte humano. Se crearon utilizando pigmentos naturales como el rojo ocre y el carbbón. La luz solar va borrando los pigmentos con el paso del tiempo, pero como las pinturas rupestres se encuentran en el interior de cuevas han podido mantenerse durante siglos. Se supone que las pintaron bajo la luz amarilla de las antorchas.</div>
 <div class="absolute_15"><img src="Difracción.gif" alt="Difracción" style="width:90%"></div>
</div>


  </div>

<div class="row">
<div class="column middle">
    <center><h2>Luz Difusa</h2></center>
    <div class="relative_3">;
  <div class="absolute_9">Cuando una luz blanca pasa a través de una jarra que contiene agua con unas gotas de leche, la luz azul se difunde por la acción de las minúsculas partículas en el agua. La luz roja no se difunde si no que atraviesa perfectamente el agua. Este fenómeno recibe el nombre de (efecto Rayleigh). El liquido brilla y adquiere un tono azulado. El humo puede llegar a tener un tono grisáceo por el efecto Rayleigh que actúa sobre las minúsculas particulas de ceniza.</div>
 <div class="absolute_10"><img src="Luz.jpg" alt="Luz" style="width:90%"></div>
  </div>
  </div>
<div class="column side_1">
    <center><h2>Cambios De Color De La Luz Del Sol</h2></center>
    <div class="relative_4">;
  <div class="absolute_11">El color de la luz del sol sufre cambios de color a medida que atraviesa la admosfera porque el aire absorbe algunos colores y deja pasar otros. Este fenómeno es especialmente evidente durante las puestas de sol. Al principio el sol parece amarillo. A medida que se va acercando a la linea del horizonte, los rayos se vuelven mas tangenciales y han de recorrer una mayor porción de aire, por lo que el color se convierte en naranja o rojo. Esto se debe a que la luz absorbe mas y mas la luz azul del sol y deja pasar mas las ondas más largas de la luz roja.</div>
 <div class="absolute_12"><img src="Tarde.jpg" alt="Tarde" style="width:70%"></div>
  </div>
<div class="column middle_2">
    <center><h2>Pigmentos Artificiales</h2></center>
    <div class="relative_5">;
  
 <div class="absolute_13">En 1856, un joven químico inglés llamado William Perkin hizo un gran descubrimiento que fue el orifgen de una gran industria. Trataba de preparar quinina a base de alquitrán del carbón cuando tras uno de los expermentos obtuvo accidentalmente una sustancia de color malva intenso. Perkin comprendió que dicha sustancia tenía un gran potencial como pigmento por lo que puso en marcha una empressa dedicada a su producción industrial y ganó una fortuna. En la actualidad, la mayoría de los pigmentos son artificiales.</div>
<div class="absolute_14"><img src="Pigmento.jpg" alt="Pigmento" style="width:50%"></div>
<div class="absolute_16"><img src="Disco.gif" alt="Disco" style="width:80%"></div>
<div class="absolute_17"><p><h2>Referencias</h2></p><p>https://www.w3schools.com/css/default.asp</p><p>https://i.makeagif.com/media/9-05-2015/vV9hg4.gif</p><p>Eyewitness Science. Light. Copyright (c) 1992 Dorling Kindersley Limited.</p><p>https://co.pinterest.com/arqclarin/galer%C3%ADa-de-fotos/</p></div>
  </div>
  </div>
  </div>
</body>
</html>
