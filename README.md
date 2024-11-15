# 0373-Apuntes-IzanIzquierdo
### Apuntes de lenguaje de marcas

# GIT
Para crear un nuevo repositorio nos situamos en nuestro perfil en el apartado `Repositories` y clicamos en `New`.  
![Estilos](img/NEW.png)

En el apartado de la creación podremos importar un repositorio con el codigo de otro clicando en `Import a repository` o crear uno de 0.  
Para crearlo agregaremos un nombre de repositorio, definiremos quien puede ver nuestro repositorio `Public o Private` y añadiremos un archivo readme clicando en la casilla `Add a README file` en caso de necesitarlo. Ahora simplemente le damos a `Create repository` y ya tendriamos el repositorio.
![GIT](img/Creacion.png)

Una vez tengamos el repositorio acabado, lo subiremos a traves de Github pages.  
Para hacer esto tendremos que dirigirnos a la configuración `Settings`, luego al apartado `Pages` y seleccionar la rama que queramos subir, en este caso sera `main`.
La seleccionamos, guardamos clicando en `Save` y esperamos unos minutos.
![GIT](img/CrearPages.png)

En un par de minutos ya tendremos nustra pagina web subida.
![GIT](img/LinkPages.png)

Por último, si queremos trabajar con el repositorio en local, tendremos que dirigirnos a `Code` y copiar el HTTPS que luego pegaremos en local.
![GIT](img/CopiarURL.png)


Para clonar un repositorio de Github en local copiaremos el codigo del repositorio y lo pegaremos en el terminal:  
![GIT](img/Clone.png)

Para subir los archivos a Github, tendremos que poner los siguientes comandos:

- Inicializaremos el repositorio de `Git`
![GIT](img/INIT.png)

- Selecciona la rama a la que queremos subir
![GIT](img/BRANCH.png)

- Selecciona lo que queremos subir, en este caso ponemos `.` para seleccionar todo  
![GIT](img/ADD.png)

- Enviamos las actualizaciones que hemos hecho del repositorio `commit` y le damos un nombre a la version `-m`  
![GIT](img/COMMIT.png)

- Subimos el repositorio a Github  
![GIT](img/PUSH.png)


# MARKDOWN

## Estilos de letra:
Para cambiar los estilos en Markdown usaremos asteriscos `*` y guiones bajos `_` 
Estos estilos se pueden combinar  

![Estilos](img/EstilosMark.png)

*Cursiva*

**Negrita**

***Combinado***

## Encabezados:
Para crear encabezados en Markdown usamos las almohadillas `#`, añadiendo 1 por cada nivel hasta un maximo de 6.  
Puedes cerrar los encabezados añadiendo el mismo numero de almohadillas al final.  
Los encabezados tienen un estilo asociado por defecto.

 # #Encabezado 1
 ## ##Encabezado 2
 ### ###Encabezado 3
 #### ####Encabezado 4
 ##### #####Encabezado 5
 ###### ######Encabezado 6

## Parrafos y Saltos de linea:
Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces intro)

Markdown no soporta dobles líneas en blanco, así que si intentas generarlas estas se convertirán en una sola al procesarse.  
Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora antes de pulsar una vez intro.


## Imagenes

### Imagen en linea  
Las imagenes en linea estan compuestas por una exclamación `!` para definir que estas haciendo una imagen, un texto alternativo `[]` y la dirección `()`:
`![TextoAlternativo](RutaImg.png)`

### Imagen de referencia  
Las imagenes de referenciaa estan compuestas por una exclamación `!` para definir que estas haciendo una imagen, un texto alternativo `[]` y la referencia `[]`.
Y donde queramos añadir la imagen pondremos el nombre de la referencia `[]` la dirección `:https//` y el texto alternativo `""`:
`![TextoAlternativo][NombreReferencia]
[NombreReferencia]:Link"TextoAlternativo"
`

## Enlaces
Los enlaces estan compuestos por el texto que contendra el link `[]`, el link `()`.  
`[Link](https://ejemplo.com/ "Título opcional del enlace")`  
[Link](https://google.com/)


## Listas:

### Listas ordenadas:
1. Para crear una lista ordenada usamos `numero.` Ej.: 1.
    1. Las listas se pueden anidar o combinar añadiendo 4 espacios antes del siguiente
5. El numero de la lista no es necesario que sea consecutivo ya que el numero cambia segun en la posición en la que se encuentre

### Listas desordenadas:
- Para crear una lista desordenada podemos usar: guion `-`, suma `+` o asterisco `*`
+ El simbolo usado para crear la lista no importa ya que todos se veran igual al procesarse
    * Estas listas tambien se pueden anidar o combinar


## Tablas
-Para crear las filas usaremos las barras verticles `|` entre una y otra
-Para crear un encabezado, debajo de este añadiremos una columna con las mismas filas separadas con `|` y en vez de texto, pondremos 2 o mas guiones `--`. En esta separación, podremos definir la alineación de las columnas con `:`
-Para añadir mas columnas simplemente seguiremos con la misma estructura (no hace falta que las columnas esten alineads verticalmente)

Ej:  
```
|Columna1|Columna2|Columna3|
|:--|--|--:|
|Texto1|Texto2|Texto3|
```
|Columna1|Columna2|Columna3|
|:--|--|--:|
|Texto1|Texto2|Texto3|


## Codigo
El codigo se tiene que introducir dentro de accentos graves '` `` `'.

`codigo`

Para crear un bloque que contenga codigo, este se ha de incluir entre tres accentos graves '` ``` `'.

```
codigo
```


# HTML
