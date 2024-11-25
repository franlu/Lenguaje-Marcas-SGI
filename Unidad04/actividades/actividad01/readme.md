# Actividad 01: Propiedad `position` en CSS

**Objetivo:** Aprender a utilizar la propiedad `position` en CSS para controlar el posicionamiento de elementos en una página web.

## Instrucciones

0. Crea una carpeta de trabajo `actividad00`.
1. Crea un archivo `index.html` básico donde realizarás los ejercicios.
2. Crea un archivo `estilos00.css` para aplicar los estilos a los ejercicios.

## Ejercicios

### 1. Menú fijo en la parte superior

- Crea un encabezado (`<header>`) que permanezca fijo en la parte superior de la pantalla mientras haces scroll.
- Usa `position: fixed;`.

### 2. Caja centrada en la pantalla

- Crea un `<div>` con fondo de color que esté perfectamente centrado, tanto horizontal como verticalmente.
- Usa `position: absolute;` o `position: fixed;` combinando con `top`, `left`, `transform`, etc.

### 3. Imagen con una etiqueta superpuesta

- Coloca una imagen y usa un `<span>` para mostrar una etiqueta superpuesta en la esquina superior derecha de la imagen.
- Usa `position: relative;` en el contenedor e `absolute` en el `<span>`.

### 4. Botón pegado al borde inferior

- Añade un botón que se mantenga fijo en la esquina inferior derecha de la pantalla.
- Usa `position: fixed;` con `bottom` y `right`.

### 5. Cajas con efecto "stack"

- Crea 3 cajas apiladas unas sobre otras con diferentes valores de `z-index`.
- Experimenta con `position: relative;` y observa cómo el orden cambia con `z-index`.

### 6. Tooltip al pasar el ratón

- Diseña un botón que al pasar el ratón muestre un texto (tooltip) flotante justo arriba de él.
- Usa `position: relative;` para el botón y `absolute` para el tooltip.

### 7. Fondo que se queda fijo

- Coloca un fondo de color que permanezca fijo mientras haces scroll.
- Usa `position: fixed;` con un contenedor.

### 8. Banner que desaparece al hacer scroll

- Crea un banner en la parte superior que use `position: sticky;` y desaparezca cuando el usuario pase de cierto punto al hacer scroll.

### 9. Imagen como fondo de un texto

- Usa `position: absolute;` para colocar una imagen detrás de un texto sin que el texto sea afectado.
- Asegúrate de que el texto sea legible.

### 10. Menú flotante

- Crea un menú lateral que se mantenga fijo al desplazarte, pero que esté posicionado en el borde izquierdo.
- Usa `position: fixed;` y define `top` y `left` para posicionarlo.
