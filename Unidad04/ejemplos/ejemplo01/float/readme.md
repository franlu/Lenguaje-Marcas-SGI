# Float

## float01: Imagen flotante con texto

* La propiedad float: left; en la imagen hace que se coloque a la izquierda.
* El texto se ajusta automáticamente a la derecha de la imagen.
* El margin-right: 20px; agrega un pequeño espacio entre la imagen y el texto.

## float02: Dos columnas flotantes

Usamos float: left; en ambas columnas para alinearlas una al lado de la otra.
La propiedad width: 45%; asegura que cada columna ocupe el 45% del espacio, y el 10% restante se distribuye como márgenes.
overflow: hidden; en el contenedor padre (.container) es útil para que el contenedor ajusta su altura después de los elementos flotantes.

## float03: Clearfix

Las cajas .left-box y .right-box flotan a la izquierda con un float: left; para colocarse una al lado de la otra.
Para evitar que el contenedor no se ajuste al contenido flotante, se utiliza la técnica de clearfix. Esto se logra mediante el pseudo-elemento ::after que usa clear: both; para "limpiar" los elementos flotantes y asegurar que el contenedor abarque ambos elementos correctamente.

## float04: Ejemplo de Layout con Float

* Encabezado: Se establece un encabezado simple con un fondo oscuro.
* Contenido principal y barra lateral: Se usan ``float: left;` para colocar el contenido principal a la izquierda (70%) y la barra lateral a la derecha (30%).
* Pie de página: Se coloca debajo de los elementos flotantes utilizando `clear: both;` para evitar que se superponga con las secciones flotantes.
* Clearfix: Se utiliza `overflow: hidden;` o `clearfix` para asegurar que el contenedor padre abarque el contenido flotante.