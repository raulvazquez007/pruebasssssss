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

· Cada elemento HTML está delimitado por etiquetas, como &lt;body&gt;, &lt;head&gt;, &lt;p&gt;, &lt;h1&gt;, etc.

Las siglas de HTML corresponden con **“HyperText Markup Language”**, que tiene el siguiente significado:

· **HyperText**, cuyo significado es hipertexto, que no es más que un texto que enlaza con otros contenidos, que pueden ser otro texto u otro archivo. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es más que páginas y recursos interconectados.

· **Markup**, que significa marca o etiqueta, ya que todas las páginas web están construidas en base a etiquetas, desde las primeras versiones hasta las últimas etiquetas de HTML5. Un ejemplo de una etiqueta HTML es la que identifica un párrafo, que se compone de la etiqueta, el contenido de la etiqueta y el cierre del párrafo: <p>HOLA</p>. (&lt;p&gt;Texto&lt;/p&gt;) 

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

&lt;p class="editor-note">Mi gato es muy gruñón&gt;/p

· class es el **nombre del atributo**

· editor-note es el **valor del atributo**

*Los atributos siempre se incluyen en la etiqueta de apertura de un elemento y deben tener:*

· Un espacio entre el nombre del elemento y el atributo (o entre atributos, si hay varios).

· El **nombre del atributo**, seguido de un signo igual (=).

· Comillas de apertura y cierre que encierran el **valor del atributo**.

Puedes también colocar elementos dentro de otros elementos. Esto se llama **anidamiento**.

Algunos elementos no poseen contenido y son llamados **elementos vacíos**.
Por ejemplo:

&lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;
Este elemento posee atributos, pero no tiene etiqueta de cierre (&lt;/img&gt;) ni contenido encerrado.

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

### Estructura básica de un fichero HTML (2)

&lt;!DOCTYPE html&gt;

&lt;html&gt;

 &lt;head&gt;

  &lt;meta charset="utf-8"&gt;

  &lt;meta name="description" content="Esta es una página web de ejemplo que demuestra el uso de metadatos, estilos CSS y otras características básicas de HTML."&gt;

  &lt;meta name="keywords" content="HTML, CSS, ejemplo, metadatos, favicon"&gt;

 &lt;title&gt;Mi página de prueba&lt;/title&gt;

  &lt;link rel="icon" href="favicon.png"&gt;

  &lt;link rel="stylesheet" href="styles.css"&gt;

  &lt;script src="script.js"&gt;&lt;/script&gt;

  &lt;style&gt;

   body {

    font-family: Arial, sans-serif;

    background-color: #f4f4f9;

   }

  &lt;/style&gt;

 &lt;/head&gt;

 &lt;body&gt;

  &lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;

 &lt;/body&gt;

&lt;/html&gt;

1. ESTRUCTURA BÁSICA DE UN FICHERO HTML

    Un documento HTML define la estructura básica de una página web. 
Contiene dos secciones principales:

    &lt;head&gt;: incluye metadatos, información adicional y enlaces a archivos externos 
      (como CSS o scripts).
    - &lt;body&gt;: contiene todo el contenido visible de la página (texto, imágenes, enlaces, etc.).

## Ejemplo básico:
´´´html
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Mi página web</title>
        </head>
        <body>
            <h1>Título principal</h1>
            <p>Este es un párrafo.</p>
        </body>
    </html>
´´´
Dentro del <head> pueden incluirse etiquetas importantes como:
´´´html
    <meta name="viewport" content="width=device-width"> 
        → Permite que el sitio sea adaptable a diferentes dispositivos.
    
    <meta name="description" content="Descripción del sitio"> 
        → Utilizada por los motores de búsqueda.
    
    <meta name="robots" content="index, follow"> 
        → Indica a los buscadores si deben indexar la página.
´´´

2. ELEMENTOS DE BLOQUE Y DE LÍNEA

´´´html
    Los elementos HTML dentro del <body> se dividen en dos tipos:

    · Elementos de bloque:
        - Ocupan todo el ancho disponible y comienzan en una nueva línea.
        - Ejemplos:
            <h1> a <h6>, <p>, <div>, <blockquote>, <pre>, <ul>, <table>.
        - Se usan para estructurar secciones grandes del contenido.

    · Elementos de línea:
        - Solo ocupan el espacio necesario y no crean una nueva línea.
        - Ejemplos:
            <em>, <strong>, <span>, <a>, <img>, <code>, <q>.
        - Se usan para resaltar o enlazar partes del texto.
´´´

3. NORMAS BÁSICAS DE LAS ETIQUETAS HTML

´´´html
    · Las etiquetas vienen en pares:
        <p>Texto</p>

    · Algunas etiquetas son vacías (no tienen cierre):
        <img>, <br>, <input>

    · Deben anidarse correctamente:
        <b><i>Texto</i></b> es correcto.
        <b><i>Texto</b></i> es incorrecto.

    · Los atributos se colocan en la etiqueta de apertura:
        <img src="imagen.jpg" alt="Descripción">

    · Recomendación:
        Escribir siempre las etiquetas y atributos en minúsculas.
´´´

4. COMENTARIOS
´´´html

    Los comentarios permiten añadir anotaciones que no se muestran en el navegador.

    Sintaxis:
        <!-- comentario -->

    Ejemplo de uso:

        <!DOCTYPE html>
        <html>
            <head>
                <title>Título</title>
            </head>
            <body>
                <!-- Cabecera -->
                <!-- Menú de navegación -->
                <!-- Contenido principal -->
                <!-- Pie de página -->
            </body>
        </html>

´´´

5. LEGIBILIDAD Y ORGANIZACIÓN DEL CÓDIGO
´´´html

    Es fundamental que el código sea claro y legible para otros desarrolladores.

    · Recomendaciones:
        - Usar comentarios claros.
        - Mantener sangrías correctas.
        - Organizar los archivos por carpetas (css, images, js).
        - Evitar líneas demasiado largas.

    · Motivo:
        Facilita la colaboración y el mantenimiento del proyecto.

´´´
6. ETIQUETAS BÁSICAS DE HTML
´´´html

    · Encabezados:
        <h1> a <h6> → Títulos y subtítulos (bloque).

    · Párrafos:
        <p> → Agrupa frases relacionadas (bloque).

    · Saltos de línea:
        <br> → Inserta un salto de línea.

    · Separadores:
        <hr> → Crea una línea horizontal divisoria.

    · Énfasis:
        <em> → Texto en cursiva.
        <strong> → Texto en negrita.

    · Span:
        <span> → Contenedor en línea para aplicar estilos dentro de un texto.
´´´

7. RUTAS EN HTML
´´´html

    · Ruta absoluta:
        Especifica la dirección completa del archivo en la web.
        Ejemplo:
            <img src="https://www.example.com/imagen.jpg" alt="Ejemplo">

    · Ruta relativa:
        Especifica la ubicación del archivo respecto al documento actual.
        Ejemplo:
            <img src="images/logo.png" alt="Logo del sitio">

´´´
8. ENLACES (<a>)
´´´html

    · Permiten navegar entre documentos mediante el atributo href.
        Ejemplo:
            <a href="https://www.ejemplo.com">Ir al sitio</a>

    · Enlaces externos:
        Conectan con páginas fuera del sitio.

    · Enlaces locales:
        Conectan con documentos del mismo sitio (usando rutas relativas).

    · Atributos comunes:
        - href: destino del enlace.
        - title: texto informativo al pasar el cursor.

´´´

9. FORMULARIOS
´´´html

    · Sirven para interactuar con el usuario y enviar información al servidor.

    · Tipos de controles:
        - <input type="text"> → campo de texto.
        - <input type="password"> → contraseña.
        - <input type="radio"> → botón de opción.
        - <input type="checkbox"> → casilla de verificación.
        - <button> → botón de envío.
        - <select> → lista desplegable.
        - <textarea> → área de texto.
        - <input type="file"> → subida de archivos.

    · Cada control debe tener un atributo name para identificar el dato enviado.
´´´

10. ETIQUETA <form>
´´´html

    · Se utiliza para crear formularios.

    · Atributos principales:
        - action: URL a la que se enviarán los datos.
        - method: método de envío (GET o POST).
        - enctype: cómo se codifican los datos.
        - target: dónde se mostrará la respuesta (_self o _blank).

    · Ejemplo completo:

        <form action="process.php" method="post" enctype="multipart/form-data">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name">

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email">

            <label for="file">Subir archivo:</label>
            <input type="file" id="file" name="file">

            <button type="submit">Enviar</button>
        </form>

´´´

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

## Git 

1. Primer paso antes de nada tendremos que crear un repositorio en el GitHub y una vez creado copiaremos el codigo.
2. Despues iremos a la car
