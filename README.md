		----	PROYECTO FINAL: PRIMERA ENTREGA	 ----
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -- - - - - - - - - - - - - - - - -- - - - - - - - - - - - - - - - -
I. Descripci�n: 

	Se solicita realizar una p�gina web para la comuna de Quilicura, el tema elegido es una p�gina estilo "Tripadvisor", la cual
tendr� la funcionalidad de ser una gu�a tur�stica de la comuna de Quilicura, tanto para los vecinos de la misma como para los visitantes
 de otras comunas y/o turistas.
	Como m�nimo debe contener temas referentes a la comuna sobre: 
	- Hitos hist�ricos
	- Gastronom�a
	- Arquitectura
	- Arte callejero
	- Lugares imperdibles
	- Contacto

II. Instrucciones:

	En la primera entrega se definir� el dise�o de la p�gina en cuanto a colores, tipos de fuentes, como se recopilar� la 
informaci�n del contenido, la estructura de la p�gina y como entregables se enviar�:

	1. Sketch y mockup escritorio
	2. Sketch  y mockup m�vil
	3. Un maqueta con estructura HTML y CSS
	4. Requerimientos del sitio
	5. Gu�a de estilos
	6. Tipo de fuentes

III. Objetivos de la interfaz (UI):


	Entregar al usuario la informaci�n tur�stica de la comuna de Quilicura, en cuanto:

	1. Hitos hist�ricos: Mostra hechos que han marcado la historia y desarrollo de la comuna, mostrando imagenes e historias.
	2. Gastronom�a: Entregar al usuario informaci�n como ubicaci�n, resa�a, productos, etc., sobre "picadas" para comer, restaurantes, 
	carritos de comida (food truck), pub, entre otros. A portar a los peque�os negocios como plataforma de publicidad.
	3. Arquitectura: Mostar al usuario la evoluci�n de la arquitetura de la comuna en el tiempo, en cuanto a la construcci�n de micro 
	barrios, casonas antiguas, parques industriales, etc.
	4. Arte callejero: Informar al usuario sobre proyectos realizados en cuanto a pintado de murales y donde pueden vistarlos, entre otras actividades.
	5. Lugares imperdibles: Mostrar los lugares que pueden visitar, su ubicaci�n, informaci�n de contacto, horarios de apertura al publico, etc., 
	de parques, plazas, cines, centros comerciales, cementerio, entre otros.
	6. Actividades culturales: Informar sobre las actividades culturales que se realizaran en la comuna, como festivales, conciertos, obras de teatro, 
	exposiciones, para que as� el usuario pueda informarse para vistitar la comuna en dichas fechas, seg�n sus intereses.
	7. Transporte: Entregar informaci�n al ususario sobre los distintos medios de transportante, tanto para acceder a la comuna, como para la movilizaci�n 
	dentro de esta.
	8. Contacto: Entregar una secci�n de contacto, para consultas, comentarios y/o sugerencias, para as� poder tener un feedback con el usuario y poder
	mejorar el sitio web, seg�n las inquietudes y aportes de la comunidad.

IV. Objetivos experiencia usuario (UX):

	La p�gina ser� estilo blog, sencilla con la informaci�n necesaria para ser una buena gu�a tur�stica de la comuna para el usuario, dandole m�s enf�sis a 
im�genes y grafica que a laintroducci�n de textos extensos, para as� llamar la atenci�n y motivar al usuario a ver por sus propios ojos y vivir la 
experiencia de conocer 	presencialmente la comuna.
	En la p�gina de inicio se mostar� la �ltima informaci�n o la m�s reevantes, sobre cada una de las secciones (historia, gastronom�a, arquitectura, 
arte callejero, lugares que visitar, etc.), al hacer click sobre una de las secciones se realizar� el link, par dirigir al usuario al resto de la informaci�n
de la secci�n elegida.
	
	El usuario podr� interactuar en la p�gina mediante un men� con botones para seleccionar la seccion que quiera visitar, adem�s de hacerlo mediante im�genes tipo thumbainls
mostrar imagenes de los temas de cada secci�n.

	En el banner principal de la pagina de inicio se mostraran temas actualizados o de mayor relevancia, en el centro ir� el logo de municipalidad.
	En la barra de navegaci�n se incluira los n�meros de contacto de seguridad ciudadana y plan cuadrante y en un costado el link a redes sociales de la comuna,
mediante iconos que la representen.
	
v. Requerimientos del sitio:

1. Generales:
	- Layout: P�gina estilo blog, con la utilizaci�n de grillas de 1 a 3 columnas, responsive.
	- La estructura de las p�ginas sera de: Una barra de navegaci�n, un header, una o dos secciones y un footer.
	- La gu�a de estilo se adjunta en:

		![](images/PaletaColores.png)

	- El sketch de escritorio y m�vil es:

		![](images/sketch.jpg)
		
	- El mockup de escritorio y m�vil es:

		![](images/Mockup.pdf

	- Para la estructura HTML y CSS, se usar� Boostrap
	- Im�genes: se realizar� un reportaje fotogr�fico en terreno, para obtener im�genes actualizadas y reales.
	- Recopilaci�n de informaci�n: Para el contenido se entrevistar� a vecinos de la comuna mediante una encuesta.

 2. Espec�ficos:

	- Estructura:

		- Se usar� estructura base de boostrap.

		- Barra de navegaci�n: 
			- color fondo: #FF5729
			- Tipo y color de fuente: #8B9090
			- Contenido: numeros telefonicos de seguridad ciudadana y plan cuadrante, m�s link para pagina de inicio, mapa de la comuna y formulario de contacto
			

		- Header: 
			- Para la p�gina de inicio ir� un banner slide tipo carousel con width 100%, mostrando imagens o videos, con el logo de la municipalidad en el centro.
			- Para cada secci�n ser� grilla de 12 columnas, con container, sobre la im�genes ir� el nombre de la secci�n.
			- Tipo y color de fuente: Shrikhand-Regular #000000

		- Secciones:
			- Se usar� grillas de 2 a 3 columnas con im�genes tipo thumbainls, bajo la imagen el titulo de tema y un resumen.
			- Color fondo: blanco	

		- Footer:
			- color fondo: #595859
			- Tipo y color de fuente: Montserrat #FF5729
			- Contenido:Escritorio: Formulario de contacto y link para volver a la parte superior de la p�gina
				    M�vil: iconos redes sociales y link para volver a la parte superior de la p�gina

	- Estilos:
		- Se usar� CSS y para las clases se usar� metodolog�a BEM, aplicando estilos seg�n la gu�a de estilos entregada en la 
		secci�n de requerimientos generales.


	- Contenido:
		- Para el  contenido se utilizar� informaci�n real y lo m�s actualizda posible, para lo cual se utilizara la recopilaci�n de informaci�n de la encuesta a los
		vecinos de la comuna, la obtenida en el reportaje fotogr�fico en terrreno y de una revisi�n bibliografia en sitio web de la municipalidad.
	

	- Im�genes:
		- Seran relaes y se inlcuir�n en la carpeta images, dentro de la carpeta css (css/images).
	

	- El proyecto se encuentra en Github, en el siguiente link: 
		https://github.com/Andyta2018/Proyecto_Final_V01
