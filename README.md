# taller-practico-javascript-videogames

 > Curso de cómo hacer un jueguito para practicar Javascript y Git :)

 ## Notas:

 *  canvas: se pueden crear gráfcos 2D a través de JS. Podemos renderizar con esto.
 * Hay que darle una medida fija con pixeles, y manipularlo dinamicamente con CSS para ponerle un vw del 100% nos puede dañar la lógica y hacer que se vea pixelado.

* Paleta de colores:
.color1 { #fff4ce };
.color2 { #d0deb8 };
.color3 { #ffa492 };
.color4 { #ff7f81 };
.color5 { #ff5c71 };

### Métodos y para qué sirven

*  game.fillRect(0,0,100,100); //método
donde va a iniciar y terminar, las cordenadas
    1) Dónde empieza. Eje X
    2) Hasta dónde va a llegar. Eje Y
    3) Ancho del cuadrado.
    4) Largo del cuadrado.

 game.clearRect(0,0,100,100);
 Esto es para borrar.

 game.fillText('Holaaa', 5, 5);
 Agrega texto. Hay que especificarle la ubicación.

  game.textAlign= 'center';
  Calcula su mitad y esa mitad la centra.

  game.font = '25px Verdana';
  Tamaño y tipo de letra.

  game.fillStyle = 'purple';
  Color de la letra.
 