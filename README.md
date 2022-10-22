# SabujCha_2.0
DOCUMENTACIÓN CREACIÓN SABUJCHA

Acompáñenme en esta triste historia haha. Bueno, les presento mi proyecto Sabujcha versión 2.0 ¿Por qué 2.0? Por que en la primera versión intenté usar SASS para mi proyecto ya que antes había tenido un acercamiento y quería volver a implementarlo para no perder la práctica, sin embargo, fue en poco complicado manejar este pre-procesador y por falta de tiempo decidí estilizar mi proyecto únicamente con CSS, por ende, en mi carpeta encontraran un documento llamado estilos.css el cual es mi intento fallido de SASS (F en el chat), sin embargo, lo deje en mi repositorio como para evidenciar el trabajo que realice previamente; El trabajo de la primera versión de Sabujcha lo hice en el repositorio de mi GitHub llamado SabujCha, que pueden encontrar en este link https://github.com/Andrea-25-11/SabujCha/tree/ANDREA y donde realice mis primeros commits del HTML.

Terminando mi triste historia de cómo fallé usando SASS, realicé la creación de un nuevo repositorio llamado SabujCha 2.0 y con el HTML de base ya creado empecé a aplicar estilos en la hoja de estilos llamada styles.css.

En el head del HTML linkee mi hoja de styles.css y linkee las fuentes de google fonts exigidas para este proyecto así:



Utilicé comentarios para separar las partes del body de mi documento. En el Header utilicé una lista desordenada para el menú de navegación, luego la imagen del logo, utilice la etiqueta de select para desplegarlas diferentes opciones de pesos y finalmente incrusté una imagen de carrito de compras. Esta parte en el CSS le aplique un display flex para alinearlos uno al lado del otro junto con margin y padding necesario para separar sus elementos internos.



El main lo separé en 8 divs, diferenciándolos con la clase así div_1, div_2 y así sucesivamente. Para el footer lo separé también en dos partes mediante divs con su respectiva clase.

 Para el primer Div utilice una propiedad de background-image para poder poner texto encima, personalmente fue la parte más difícil para mí ya que los pixeles de la imagen en varias ocasiones no se ajustaban a lo que necesitaba, hice mucha búsqueda de información e implemente el background-size:cover junto con la declaración de un height y wualá funcionó después de hacerme casi llorar hahaha. Esta fue la etiqueta más nueva para mí ya que también para el div2 la apliqué y tuve muchos más problemas.



A lo largo de mi main utilicé más que todo listas desordenadas, decoraciones al texto como el underline,line-through, el italic o negrilla dependiendo de la necesidad, también apliqué los diferentes colores a las tipografías; Fue un poco confuso diferenciar las tipografías a aplicar en cada elemento, por tal razón imprimí el landing page y seleccione por colores qué fuente se debía aplicar a cada elemento así:



Algo que me pareció super cool fué que aprendí a cambiar el valor de 1rem desde la aplicación de un font-size específico a la etiqueta de HTML ya que eso me permitió acortar mucho el proceso de cambio de medidas y tamaños y letras u otros elementos, el valor general que dejé para la página fue el de 16px por cada rem y para la aplicación de media queries le cambié el valor de 10 pixeles por cara rem así:


Ya que el font-size no cambia todas las propiedades aplicadas a mí documento realicé algunos cambios en los elementos que fuera necesario, entre los cambios más frecuentes que hice fue cambiar el despliegue el display:flex aplicando el flex-direction: column para alinear un elemento bajo otro, también cambié algunos justify content hacia el centro y cambié  el despliegue de los divs a las que les apliqué el background-image.

Algunas vistas de mi página en modo escritorio:








Algunas vistas en celular:



