# Actividad de Recuperación: Propiedad `float` en CSS

**Objetivo:** Comprender y aplicar la propiedad `float` en CSS para la disposición de elementos en una página web, trabajando con imágenes, columnas flotantes y técnicas de clearfix.

---

## Parte 1: Imagen flotante con texto (float01) — 25%

**Instrucciones:**
1. Crea un archivo HTML y CSS para implementar una imagen flotante con texto. (5 puntos)
2. Usa una imagen de tu elección, añádela a la página y colócala a la izquierda utilizando `float: left;`. (5 puntos)
3. A la derecha de la imagen, coloca un párrafo con texto. Asegúrate de que el texto se ajuste automáticamente alrededor de la imagen. (5 puntos)
4. Añade un `margin-right: 20px;` a la imagen para que haya un pequeño espacio entre la imagen y el texto. (5 puntos)

**Requisitos:**
- El texto debe ajustarse correctamente al lado derecho de la imagen. (5 puntos)
- La imagen debe estar flotando a la izquierda, con un margen de separación entre la imagen y el texto. (5 puntos)

**Puntuación total para Parte 1: 30 puntos**

---

## Parte 2: Dos columnas flotantes (float02) — 25%

**Instrucciones:**
1. Crea un contenedor con dos columnas. Ambas columnas deben flotar a la izquierda utilizando `float: left;`. (5 puntos)
2. Asigna un `width: 45%;` a cada columna para que ambas ocupen el 45% del ancho, dejando un 10% para los márgenes. (5 puntos)
3. Añade algo de contenido dentro de cada columna (pueden ser párrafos de texto o listas). (5 puntos)
4. Utiliza `overflow: hidden;` en el contenedor padre para que este ajuste su altura según el contenido flotante. (5 puntos)

**Requisitos:**
- Dos columnas deben flotar una al lado de la otra. (5 puntos)
- El contenedor debe ajustarse correctamente a la altura de las columnas flotantes. (5 puntos)

**Puntuación total para Parte 2: 30 puntos**

---

## Parte 3: Clearfix (float03) — 25%

**Instrucciones:**
1. Crea un contenedor que contenga dos cajas flotantes con `float: left;`. (5 puntos)
2. Implementa la técnica de clearfix utilizando el pseudo-elemento `::after` con `clear: both;` para asegurar que el contenedor ajuste su altura después de los elementos flotantes. (5 puntos)
3. Asegúrate de que las cajas flotantes se ubiquen una al lado de la otra. (5 puntos)

**Requisitos:**
- El contenedor debe abarcar ambas cajas flotantes sin problemas de superposición. (5 puntos)
- Debes implementar clearfix correctamente. (5 puntos)

**Puntuación total para Parte 3: 25 puntos**

---

## Parte 4: Ejemplo de Layout con Float (float04) — 25%

**Instrucciones:**
1. Crea un layout básico con un encabezado, contenido principal, barra lateral y pie de página. (5 puntos)
2. El encabezado debe tener un fondo oscuro. (5 puntos)
3. El contenido principal debe ocupar el 70% del ancho, y la barra lateral debe ocupar el 30%. (5 puntos)
4. Usa `float: left;` para colocar el contenido principal a la izquierda y la barra lateral a la derecha. (5 puntos)
5. El pie de página debe colocarse debajo de los elementos flotantes utilizando `clear: both;` para evitar que se superponga. (5 puntos)
6. Aplica clearfix en el contenedor para evitar problemas de ajuste. (5 puntos)

**Requisitos:**
- Debe haber un encabezado con fondo oscuro, contenido principal (70%) y barra lateral (30%). (5 puntos)
- El pie de página debe estar debajo de las secciones flotantes sin superponerse. (5 puntos)
- El contenedor debe ajustarse correctamente con clearfix. (5 puntos)

**Puntuación total para Parte 4: 45 puntos**


---


## Entrega:
- El código completo debe ser entregado en un solo archivo comprimido que incluya, para cada parte una carpeta, que incluya todos los archivos HTML y CSS necesarios. 
