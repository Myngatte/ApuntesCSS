# ApuntesCSS

Para comenzar a hacer estilos, primero creamos una carpeta "CSS" con un archivo ".css" 

Para poner a uso estos estilos debemos vincular el archivo ".css" con el archivo al cual le queremos poner los estilos con ``link``

Para poder vincularlo correctamente, en el ``src`` del ``link`` hay que poner la ubicación del archivo como si fuese una imagén

Ej: link rel="stylesheet" href="mystyle.css"

También podemos añadir o cambiar la fuente del texto, tan solo debemos ir a la pagina oficial de ``Google fonts`` y copiar el link/comandos de la fuente el cual queremos usar, y vincularlo 

#Dentro del CSS
- Selectores
A la hora de poner estilos hay que elegir "qué", en concreto,
Tenemos:
- ``*`` Como selector universal, es decir, que coje todo.
- ``xxxxx.class`` Para seleccionar una clase 
- ``Etiqueta`` Seleccionar la etiqueta, ejemplo: ``h1``
- ``#`` Para elegir objetos con ``id``, id es un identificador que le puedes poner a cualquier texto en concreto, imagenes, etc. Se pone con ``id=""``

Una vez se haya seleccionado el selector, los estilos se deben poner de esta forma:

``(Selector)`` {

    (lo que quieres hacer);

}


En los estilos que hemos aprendido estan:

### ``Padding``

Lo que seria la sangría, es decir el margen

### ``Backgrounds``

Para editar el fondo

### ``Borders``

Para añadir o editar bordes

### ``Height/Width``

Tal cual como su traducción al español, hacen referencia a la anchura y la altura
