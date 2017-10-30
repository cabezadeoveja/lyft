## LYFT

#### ITEM ARCHIVO HTML.
El archivo html contiene dos etiquetas principales: Head y Body; dentro de estas etiquetas hay otras sub-etiquetas las cuales le van dando la estructura a nuestra página.

EAD: 
Titulo: Lyft, nombre que saldrá en la pestaña al momento de abrir nuestra página.
Enlazamos nuestro archivo CSS para que al momento de atribuirles estilos a las etiquetas se vean reflejados en el navegador.
Enlazamos la tipografia Montserrat con sus diferentes pesos visuales (400,700,800,900).
Enlazamos Font awesome, para colocar los iconos.

BODY:
La etiqueta body se sub-dividio en 6 partes, para que al momento de realizar un cambio o leer el codigo se nos sea más entendible.

1- DIV ID "FONDO": Fondo (background) con una imagen gif la cual va desde el HEADER hasta el termino de SECTION ID="PART1".

1.1- HEADER (o encabezado): En esta sección va el menu principal de la página. Contiene un logo en el lado derecho, el cual insertamos través de la etiqueta: img src="". y 4 secciones al lado izquiero de forma horizontal (Drive, Explore, Help y Log in)

1.2- SECTION ID="PART1": En esta sección va un formulario el cual se hizo a travez de la etiqueta: input; esta sección esta ubicado al lado derecho de la pagina, y contiene un boton y enlaces.

1.3- DIV ID ="GRADIENTE": se creo un nuevo fondo grandiente para lograr una transición armonica entre el final del fondo gif y el color de fondo de la sección siguiente.

2- SECTION ID="PART2": Contiene 3 sub-secciones, donde cada una de ellas tiene un Titulo h3 y un parrafo. Estás sub-secciones estan ubicadas al lado izquierdo de la pantalla. Mientras que en el lado derecho hay una imagen, la cual insertamos través de la etiqueta: img src=""

3- SECTION ID="PART3": Contiene dos contenedores: contenedor 1 (donde tenemos una caja con información) y contenedor 2 (donde insertamos un video por medio de la etiqueta iframe src="")

4- SECTION ID="PART4":  Contiene dos contenedores: contenedor 1 (donde tenemos una caja con información) y contenedor 2 (donde insertamos un video por medio de la etiqueta iframe src="")

5- SECTION ID="PART5":  Contiene dos contenedores: contenedor 1 (donde tenemos una caja con información) y contenedor 2 (donde insertamos un video por medio de la etiqueta iframe src="")

6- FOOTER: Contiene 2 sub-secciones: 1.footer-principal, el cual es un menu en forma vertical con 4 contenedores diferentes (m-inferior1/2/3 y 4) de forma horizontal, donde los tres primeros contenedores son textos que nos llevan a nuevos enlaces, mientras que el ultimo son 3 imagenes con enlaces). 2.Redes sociales, bajo del footer-principal se encuentran los enlaces de las redes sociales, donde se insertaron los iconos correspondientes a travez de la etiqueta: i class="". También va un texto de copyright y 2 enlaces.


Otras etiquetas a conciderar:

1- ANCHOR: se utilizó la etiqueta anchor: a href="#" para cada uno de los enlaces de nuestra página (en esta ocación los enlaces se encuentran inactivos)

2- BOTONES: Se hicieron a travez de div los cuales se le dieron atributos en CSS.

3- VIDEOS: Para conseguir el URL de un video, se deben seguir los siguentes pasos: abrir el video, luego dar click en compartir, presionar el boton insertar, copiar la dirección y pegarla en nuestro archivo html.


#### ITEM ARCHIVO CSS.
Hoja de estilo, donde controlamos los resultados finales de la página (colores, tamaños, posiciones).

1- background fondo: background-image: url()

2- background transparente: background: linear-gradient(transparent, #76278F (morado))

3- background: linear-gradient (#76278F (morado), #2B1E66 (azul));

4- background footer: #333447;

5- font-family: 'Montserrat', sans-serif;

6- color (para las fonts): #ffffff; (blanco) #FF00BF; (fuccia) #352384; (morado azulino) #bfc7d9; (plomo-celeste) #2B1E66; (morado) #f3f3f5; (plomo) 

7- h2 tiene una font-size: 32px;

8- h3 tiene una font-size: 28px;

9- h5 tiene una font-size: 14px;

10- Utilizamos box-sizing: border-box; para que cuando utilizemos padding y/o border el elemento no incremente su ancho.

11- :HOVER (a:hover { color:): Para que cuando nos situemos con el puntero sobre algún elemento, (en este caso enlaces e iconos) cambien de color. 

12- Ocupamos float para posiciona elementos de forma flotante, ya sea a la derecha o a la izquierda.