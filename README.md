# AE1b Mi documentación (apuntes) [REVISIÓN 1] Raul Vazquez

## Etiquetas basica MarkDown
### **Encabezados:** 
Llevan ya asociado un estilo por defecto cada un y sirven para iniciar secciones de docuemtos.

Ej: Si pones solo una # seria un H1 es decir el encabezado mas grande, si ponemos ## seria el segundo mas grandre y asi hasta llegar a seies hastags.
# Hola
## hola
### hola
#### hola

### **Estilos de letra**

· **Negritas:** 
Se puede poner el tenxto en negrita utilizando 2 barra bajas delante y dos detras de la palabra o poniedo dos asteriscos delante y y dos detras "__ algo __ o ** algo **" sin seperacion!!

Ej:
Esto esta en __negrita__ 
Esto esta en **negrita** tambien

· _Cursiva_: Se puede poner el tenxto en cursiva utilizando 1 barra baja delante y 1 detras de la palabra o poniedo 1 asteriscos delante y 1 detras "_ algo _ o * algo *" sin seperacion!!

Ej:
Esto esta en _cursiva_
Esto esta en *cursiva*

### Enlaces

Para poner un enlace tenemos que utilizar esta estructura [] (), Dentro de los corchetes escribiremos el nombre del sitio y dentro de los parentesis pondremos el enlace y si quermeos escribir un texto adicional pondremos entre comillas el texto "Aqui dentro el texto".

Ej: 
[Periodico oficial del Pais](https://elpais.com/ "Texto adicional")

### Imagenes

Para poner una imagen usaremos la estructura ! []   (). Primero escribiremos ! junto a los corchetes es decir asi ! [] dentro del corchete escribirmeos alt tex, despues dentro de los parentesis pondremos la ruta donde esta la imagen  y si quermeos escribir un texto adicional pondremos entre comillas el texto "Aqui dentro el texto".

Ej:![alt tex](./Imagenn1.jpg "Imagen bandera")

### Tablas

Para hacer tablas utilizaremos el elemento | que son para los encabezados de las columnas.

| *Jugador* | Equipo | Nombre |
|:---------|:-------------:|:--------------|
| 32 | Lakers | Magic Johnson |
| 33 | Celtics| Boston Celtics |
| 23 | Bulls | Michael Jordan |

Los dos puntos se usasn para alinear las columnas (izquierda/centro/derecha).

Se han de poner al menos tres guiones para separar cada encabezado. 

### Notas al pie de pagina:

Para poner un texto con pie de pagina utilizaremos los corchetes [] y dentro de los corchetes ^1.

Ej: Texto con enlace a nota de pie de pagina [^1]

## HTML

### Introduccion a HTML

· **HTML** (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web. Lenguaje más importante de Internet dado que sin HTML no se vería nada en el navegador.

· **HTML** define la estructura y el contenido (es decir, si hay una imagen, una lista de elementos, un enlace, un párrafo, un titular, etc...) de las páginas web mediante etiquetas, es muy adaptable, tiene una estructura lógica y es muy fácil de entender e interpretar. DESCRIBE EL CONTENIDO.

· No se dedica a ver cómo se interactúa con el contenido (Javascript, PHP, etc...), ni se preocupa por la presentación o estilizado del contenido, es decir, de cómo se ve el contenido (para eso tenemos CSS).

· Los elementos HTML son los bloques de construcción de las páginas HTML.

· Cada elemento HTML está delimitado por etiquetas, como < body >, < head>, < p>, < h1>, etc.(Sin espacios)

Las siglas de HTML corresponden con **“HyperText Markup Language”**, que tiene el siguiente significado:

· **HyperText**, cuyo significado es hipertexto, que no es más que un texto que enlaza con otros contenidos, que pueden ser otro texto u otro archivo. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es más que páginas y recursos interconectados.

· **Markup**, que significa marca o etiqueta, ya que todas las páginas web están construidas en base a etiquetas, desde las primeras versiones hasta las últimas etiquetas de HTML5. Un ejemplo de una etiqueta HTML es la que identifica un párrafo, que se compone de la etiqueta, el contenido de la etiqueta y el cierre del párrafo: <p>HOLA</p>. (< p>Texto< /p> Esto sin espacios )

· **Language**, cuyo significado es lenguaje, porque HTML es un lenguaje, es decir, tiene sus normas, tiene su estructura y una serie de convenciones que nos sirven para definir tanto la estructura como el contenido de una web. Algo importante a tener en cuenta y con lo que no hay que confundirse, es que porque HTML sea un lenguaje no quiere decir que sea un lenguaje de programación.

#### Introduccion a HTML (elementos)

Es decir, que HTML no es un lenguaje de programación; es un lenguaje de marcado que define la estructura de su contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera.

Esto implica que la información a mostrar ha de ir “etiquetada” para formar elementos que el navegador web sepa interpretar de qué tipo de información se trata y cómo tal sepa cómo representarlos.

##### Las partes principales del elemento son:
· **La etiqueta de apertura:** consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares (< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento —en este caso, dónde es el comienzo del párrafo—.

· **La etiqueta de cierre:** es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento —en este caso dónde termina el párrafo—.

· **El contenido:** este es el contenido del elemento, que en este caso es sólo texto.

· **El elemento:** la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento.

#### Introduccion a HTML (atributos)

Los elementos pueden también tener atributos.

Los atributos contienen información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento.
En el siguiente ejemplo:

<p class="editor-note">Mi gato es muy gruñón</p>

· class es el **nombre del atributo**

· editor-note es el **valor del atributo**

*Los atributos siempre se incluyen en la etiqueta de apertura de un elemento y deben tener:*

· Un espacio entre el nombre del elemento y el atributo (o entre atributos, si hay varios).

· El **nombre del atributo**, seguido de un signo igual (=).

· Comillas de apertura y cierre que encierran el **valor del atributo**.

Puedes también colocar elementos dentro de otros elementos. Esto se llama **anidamiento**.

Algunos elementos no poseen contenido y son llamados **elementos vacíos**.
Por ejemplo:

<img src="images/firefox-icon.png" alt="Mi imagen de prueba">
Este elemento posee atributos, pero no tiene etiqueta de cierre (</img>) ni contenido encerrado.

### Estructura básica de un fichero HTML

· Una página **HTML** básica incluye una declaración **DOCTYPE**, un elemento html, y dentro de este, un head y un body.

· El **head** contiene metadatos y enlaces a hojas de estilo y scripts, mientras que el **body** contiene el contenido principal de la página web.

&lt;!DOCTYPE html&gt;

&lt;html&gt;

&lt;head&gt;

&lt;meta charset="utf-8"&gt;

&lt;title&gt;Mi página de prueba&lt;/title&gt;

&lt;link rel="icon" href="favicon.png"&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;

&lt;/body&gt;

&lt;/html&gt;


· **&lt;!DOCTYPE html&gt;** indica el tipo de documento.

· **&lt;html&gt;&lt;/html&gt;** el elemento &lt;html&gt;. Este elemento encierra todo el contenido de la página entera y, a veces, se le conoce como el elemento raíz (root element).

· **&lt;head&gt; &lt;/head&gt;** el elemento <head>. Este elemento actúa como un contenedor de todo aquello que quieres incluir en la página HTML que no es contenido visible por los visitantes de la página.


__*ABRIR ETIQUTA 1*__
    ABRIR ETIQUETA 2 
        contenido
    CERRAR ETIQUETA 2
CERRAR ETIQUETA 1

__Para hacer una lista ordenada utilizaremos 1. 2. 3. y para una lista desordenada utilizaremos el * el + o -__

* Elemento desordenado 1
* Elemento desordenado 2
* Elemento desrodenado 3

1. Elemento 1
2. Elemento 2
3. Elemento 3

__Para hacer una lista anexada pondremos 1. y debajo el * y le daremos al tabulador para el sangrado__
1. Elemento 1
    * Elemento desordenado 1,2
    * Elemento desordenado 1,2
2. Elemento 2
    * Elemento desordenado 2,1
    * Elemento desordenado 2,2
3. Elemento 3

**Para hacer un parrafo clicamos dos veces al intro**

hola que tal: Esto es un parrafo 


Yo bien y gracias por el parrafo

Otra forma de hacer un parrafo urilizaremos las (```html <p>Las p para eescribir el parrafo</p> y ``` para cerrars)

```html
<p>Esto es un parrafo</p>
```
