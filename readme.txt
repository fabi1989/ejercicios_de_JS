================================================================================
EJERCICIOS JS 2
================================================================================
Haz cada ejercicio en un archivo nuevo, y nómbralo ejercicio 22.html, ejercicio 23.html, etc.
En cada ejercicio, para abreviar, puedes pegar este código:

<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Document</title>
	<style>
	
	</style>
</head>
<body>

	
	<script>
					
	</script>
</body>
</html>
	
Si te atascas con un ejercicio, déjalo reposar un poco y prueba con el siguiente
Si te atascas con todos, prueba a ver seguidas Un día de furia, La naranja mecánica y Asesinos natos. Luego vuelves.
================================================================================

22- Comenzamos por un poco de generación de contenido HTML dinámico
	HTML:
		<div id="destacado"></div>
	JS: 
		Haz que en ese div aparezca un h1 y un párrafo con un enlace, con los textos que quieras.


23- Vamos a complicarlo un poco más, metiendo dentro de ese contenido el valor de unas variables
	HTML:
		<div id="noticia"></div>
	JS: 
		var titulo = "Última hora: Javascript está mal";
		var fecha = "2020-07-10";
		var texto = "Investigadores de Harvard han llegado a la conclusión de que Javascript no me gusta nada, y que prefiero las croquetas de jamón.";
		
		Haz que en el div aparezca un h1, un span y un párrafo. En el h1 tienes que poner el valor de la variable titulo, en el span el de la variable fecha, y en el párrafo el de la variable texto.


24- HTML:
		<nav>
			<a href="index.html">Inicio</a>
			<a href="empresa.html">Nosotros</a>
			<a href="servicios.html">Servicios</a>
		</nav>
	JS: 
		Código JS para AÑADIR a ese nav un nuevo enlace al final: el de contacto.


25- HTML:
		<nav>
			<a href="empresa.html">Nosotros</a>
			<a href="servicios.html">Servicios</a>
			<a href="contacto.html">Contacto</a>
		</nav>
	JS: 
		Código JS para AÑADIR a ese nav un nuevo enlace AL PRINCIPIO: el de la página de inicio (jejeje)
		
	
26- HTML:
		<div class="saludo">esperaba que vinierais</div>
	JS: 
		Añade la palabra "No" al principio de la frase del div, y la palabra "sobrios" al final. Las dos palabras deben ir en ROJO. Piensa, piensa.
		

27-	HTML:
		Importe base:<br>
		<input id="base" type="number" value="238"><br>
		Importe total: <span id="total"></span> €
	JS: 
		Código para que en el span #total aparezca el importe del input con el IVA (21% a día de hoy)
		

28-	HTML:
		Importe base:<br>
		<input id="base" type="number" value="238"><br>
		Descuento (10%): <span id="descuento"></span> €
		IVA (21%): <span id="iva"></span> €
		Importe total: <span id="total"></span> €
	JS: 
		Complicamos un poco más el ejercicio anterior.
		
		
29- Venga, empezamos con los EVENTOS
	HTML:
		<button id="btnPrueba">Prueba</button>
	JS: 
		Haz que al pulsar el botón #btnPrueba aparezca un mensaje en la consola (el que quieras)
		
		
30- Esto es lo mismo que el anterior, pero la forma de llamar al evento es distinta
	HTML:
		<button id="btnPrueba" onclick="avisa()">Prueba</button>
	JS: 
		Tienes que crear la función avisa para que salga el mensaje que quieras en la consola. Compara este ejercicio con el anterior, y fíjate en las diferencias entre una y otra forma de activar el evento.
		
		
31- Este no es dificil, pero tendrás que pensar. O sea, que puede que sea difícil.
	HTML:
		<header id="cabecera"></header>
	JS: 
		Escribe código JS para que en el header ése aparezca un BOTÓN que al pulsarlo muestre un mensaje en un alert (el que quieras)
		
		
32- HTML:
		<header id="cabecera">
			<div id="aviso">
				<a href="ofertas">Descubre nuestras ofertas</a><br>
				<button onclick="verMas()">Descartar</button>
			</div>
		</header>
	JS: 
		Escribe la función verMas. Al llamarla clicando el botón, borrará todo lo que hay en la cabecera. Es muy fácil, tranquilo.
		
		
33- CSS: 
		body {height: 100vh; margin: 0; padding-left: 275px;}
		.caja {display: inline-block; width: 250px; min-height: 50px; border: 1px solid #666;}
		.tablon {position: fixed; top: 0; left: 0; width: 250px; height: 100%; background: #CCC;}
	HTML:
		<aside class="tablon"></aside>
		<button onclick="unoMas()">Añadir uno más</button>
	JS: 
		Código para que cada vez que se pulse el botón se añada en el aside.tablon un div con la clase caja, y un texto, el que quieras.
		¿Podrías hacer que en lugar de un texto fijo apareciera la fecha actual?
		
		
34- CSS: 
		body {height: 100vh; margin: 0; padding-left: 275px;}
		.caja {display: inline-block; width: 250px; min-height: 50px; border: 1px solid #666;}
		.tablon {position: fixed; top: 0; left: 0; width: 250px; height: 100%; background: #CCC;}
	HTML:
		<aside class="tablon"></aside>
		<input type="text" id="mensaje">
		<button onclick="unoMas()">Añadir uno más</button>
	JS: 
		Esta es una variación del ejercicio anterior. Al pulsar el botón añadirás al tablón un div con la clase caja, como antes, pero en esta ocasión el texto será el que hayas escrito dentro del input#mensaje
		

35- No hagas este ejercicio sin haber terminado el anterior. Partiendo de ese punto, haz que cuando pulsemos el botón, además de añadirse al tablón lo que hemos escrito, se VACÍE el campo de texto.
		

36- Partiendo del ejercicio anterior, añade un botón al HTML más para que, al pulsarlo, se VACÍE el .tablon (es decir, que se borre todo su contenido).