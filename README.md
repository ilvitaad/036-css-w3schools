# 036-css-w3schools
Fundamentos de CSS con W3Schools

# Introduccion a css
CSS significa Hojas de Estilo en Cascada
CSS describe cómo se deben mostrar los elementos HTML en la pantalla, en papel o en otros medios.
CSS ahorra mucho trabajo. Puede controlar el diseño de varias páginas web a la vez.
Las hojas de estilo externas se almacenan en archivos CSS

# Sintaxis css
El selector apunta al elemento HTML al que deseas aplicar estilo.

El bloque de declaración contiene una o más declaraciones separadas por punto y coma.

Cada declaración incluye el nombre de una propiedad CSS y su valor, separados por dos puntos.

Las declaraciones CSS múltiples se separan con punto y coma, y ​​los bloques de declaración se encierran entre llaves.

# Selectores Css
Los selectores CSS se utilizan para "encontrar" (o seleccionar) los elementos HTML a los que se desea aplicar estilo.

Podemos dividir los selectores CSS en cinco categorías:

Selectores simples (seleccionan elementos según su nombre, ID o clase)
Selectores combinatorios (seleccionan elementos en función de una relación específica entre ellos)
Selectores de pseudoclase (seleccionan elementos en función de un estado determinado)
Selectores de pseudoelementos (seleccionan y dan estilo a una parte de un elemento)
Selectores de atributos (seleccionan elementos en función de un atributo o valor de atributo)

# Como usar css
Existen tres formas de insertar una hoja de estilo:

CSS externo: enlace a un archivo .css externo.
CSS interno: utilice el elemento style en la sección head.
CSS en línea: utilice el atributo style en los elementos HTML

# Comentarios css
Los comentarios se utilizan para explicar el código CSS y pueden resultar útiles al editar el código fuente posteriormente.

Los comentarios también se utilizan para deshabilitar temporalmente secciones de código CSS dentro de una hoja de estilos.

¡Los navegadores ignoran los comentarios!

Un comentario CSS se coloca dentro del <style>elemento HTML y comienza con /*y termina con */:

# Estilo de borde CSS
Esta propiedad especifica qué tipo de borde se debe mostrar. border-style

Se permiten los siguientes valores:

dotted- Define un borde punteado
dashed- Define un borde punteado
solid- Define un borde sólido
double- Define un borde doble
groove- Define un borde ranurado 3D. El efecto depende del valor del color del borde.
ridge- Define un borde estriado 3D. El efecto depende del valor del color del borde.
inset- Define un borde insertado 3D. El efecto depende del valor del color del borde.
outset- Define un borde exterior 3D. El efecto depende del valor del color del borde.
none- No define frontera
hidden- Define un borde oculto

# Lados individuales
CSS tiene propiedades para especificar el relleno de cada lado de un elemento:

padding-top- establece el relleno superior de un elemento
padding-right- establece el relleno correcto de un elemento
padding-bottom- establece el relleno inferior de un elemento
padding-left- establece el relleno izquierdo de un elemento

# altura y anchura CSS
Las propiedades heighty pueden tener los siguientes valores: width

auto- Esta es la configuración predeterminada. El navegador calcula la altura y el ancho.
length- Define la altura o el ancho en px, cm, em, etc.
%- Define la altura o anchura en porcentaje del bloque contenedor.
initial- Establece la altura o el ancho a su valor predeterminado.
inherit- La altura o el ancho se heredarán de su valor padre.

# Modelo de caja
Contenido : el contenido del cuadro, donde aparecen texto e imágenes.
Relleno : crea un área alrededor del contenido. El relleno es transparente.
Borde : un borde que rodea el relleno y el contenido.
Margen : elimina un área fuera del borde. El margen es transparente.

# esquema
CSS tiene las siguientes propiedades de esquema:

outline-style- Especifica el estilo del contorno
outline-color- Especifica el color del contorno
outline-width- Especifica el ancho del contorno
outline-offset- Agrega espacio entre el contorno y el borde de un elemento.
outline- Una propiedad taquigráfica

### Esta outline-stylepropiedad el estilo del contorno y puede tener uno de los siguientes valores:

dotted- Define un contorno punteado
dashed- Define un contorno punteado
solid- Define un contorno sólido
double- Define un doble contorno
groove- Define un contorno ranurado en 3D
ridge- Define un contorno estriado en 3D
inset- Define un contorno de inserción 3D
outset- Define un contorno inicial 3D
none- No define ningún contorno
hidden- Define un contorno oculto

# Listas de estilos CSS
En HTML, existen dos tipos principales de listas:

<ul> - listas no ordenadas (los elementos de la lista están marcados con viñetas)
<ol> - listas ordenadas (los elementos de la lista están marcados con números o letras)
CSS tiene las siguientes propiedades para dar estilo a las listas HTML:

list-style-type - Especifica el tipo de marcador de elemento de lista
list-style-image - Especifica una imagen como marcador del elemento de la lista.
list-style-position - Especifica la posición de los marcadores de elementos de la lista.
list-style - Una abreviatura de propiedad para las propiedades anteriores

# diferecia entre padding y margin
margin lo de afuera, padding de la caja hacia adentro

# Bordes de tabla CSS
La propiedad CSS se utiliza para especificar el ancho, el estilo y el color de los bordes de las tablas. border

La propiedad es una forma abreviada de propiedad para: border

border-width- establece el ancho del borde
border-style- Establece el estilo del borde (obligatorio)
border-color- establece el color del borde

## Bordes de tabla colapsables CSS
La propiedad CSS border-collapsedetermina si los bordes de la tabla deben fusionarse en un solo borde o permanecer separados como en el HTML estándar.

Esta propiedad puede tener uno de los siguientes valores:

separate- Valor predeterminado. Los bordes están separados; cada celda mostrará sus propios bordes.
collapse- Los bordes se fusionan en un único borde cuando es posible.

## Ancho de tabla CSS
La propiedad CSS width se utiliza para establecer el ancho de una tabla.

El ancho se puede configurar:

en porcentaje (%)
como una longitud fija (px)
por palabra autoclave

## Altura de tabla CSS
La propiedad CSS height se utiliza para establecer la altura de una tabla.

La altura se puede ajustar:

en porcentaje (%)
como una longitud fija (px)
por palabra autoclave

## Alineación horizontal
La text-alignpropiedad CSS se utiliza para establecer la alineación horizontal del contenido en <th> o <td>.

Esta propiedad puede tener uno de los siguientes valores:

left- Alinea el texto a la izquierda
right- Alinea el texto a la derecha
center- Centra el texto

# Alineación horizontal
Existen varias formas de alinear elementos horizontalmente:

margen: automático - Centrar elementos de bloque
text-align: center - Centra el texto dentro de los elementos
Flotar o posición - Alineación izquierda/derecha
Alineación vertical
El centrado vertical se puede lograr utilizando técnicas de diseño modernas:

Flexbox - Usoalign-items: center
Cuadrícula - Usoplace-items: center
Posición + Transformación - Para elementos de dimensiones desconocidas

# Combinadores CSS
Un combinador es algo que define la relación entre dos o más selectores.

Un selector CSS puede contener más de un selector. Entre los selectores, podemos incluir un combinador para crear una selección más específica.

En CSS existen cuatro combinadores diferentes:

Combinador descendiente (espacio)
Combinador hijo (>)
Siguiente combinador hermano (+)
Combinador de hermanos subsiguientes (~)

# Pseudoclases interactivas
Las pseudoclases interactivas aplican estilos en función de la interacción del usuario :

:hover- Cuando el ratón está sobre un elemento
:focus- Cuando un elemento tiene el foco
:active- Cuando se activa un elemento
:link- Enlaces no visitados
:visited- Enlaces visitados

# Pseudoclases estructurales
Las pseudoclases estructurales seleccionan elementos en función de su posición en el árbol del documento :

:first-child- Primer hijo de un padre
:last-child- Último hijo de un padre
:nth-child(n)- El enésimo hijo de un padre
:lang()- Elementos con un idioma específico