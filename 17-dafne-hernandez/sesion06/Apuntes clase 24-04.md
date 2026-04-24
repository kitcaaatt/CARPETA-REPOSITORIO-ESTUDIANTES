4 pilares del pnesamiento computacional  

1. descomposicion:
consiste en tomar un problema grande y complejo y romperlo en partes mas peqieñas y manejables

2. reconocimiento de patrones
es observar tendencias o regularidades dentro de un prpblema. si algo se repite o sigue una logica constante, podemos automatizarlo.
- en diseño; notas que para representar a 100 personas, no necesitas dibujar 100 veces, notas que todas son un circulo con una posicion x distinta.

3. abstraccion:
es filtrar la informacion innecesaria y quedarse solo con las caracteristicas que definen el problema. es crear una representacion simbolica de la realidad,

- en diseño: para representar la presion social no necesitas dibujar <a toda la sociedad, quizas un circulo que se achica cuando el mouse se acerca es suficiente.  
- en el codigo; se trasduce en el uso de variables...

4. algoritmos:
es el diseño de una serie de reglas ordenadas para resolver el problema, es el plan de accion que debe seguir el sistema.

- en el diseño: es el flujo de la ezxp. si el usuario hace esto, pasa aquello, si no, pasa esto otro.
- en el codigo: se traduce en el diagrama de flujo y en las condicionales (if/else), es el mapa logico que conecta todas las partes anteriores,


Tipos de interaccion:  

- interaccion discreta (eventos)
Es cuando ocurre un evento especifico, y el sistema responde con una accion unica (aparecen circulos), es un interruptor de encendido/apagado o accion/reaccion
. en el codigo: se suele usar dentro de la funcion "mousePressed"



Funciones propias: 
modularidad - reusabilidad  

function "nombreDeLaFuncion"() {  
}  

ejemplo: 
function draw() {  
background  
dibujarFiguras();  
}  

function DibujaeFiguras() {  
stroke  
strokeweight  
fill  
ellipse  
}  


