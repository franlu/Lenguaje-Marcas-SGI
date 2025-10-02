# Ejercicios de Práctica con Enlaces en HTML

A continuación se proponen **10 ejercicios cortos** para practicar con
diferentes tipos de enlaces y propiedades de los enlaces en HTML.

------------------------------------------------------------------------

## Ejercicio 1 --- Enlace básico

Crea un enlace que dirija a la página principal de **Wikipedia**.

``` html
<a href="https://www.wikipedia.org">Ir a Wikipedia</a>
```

------------------------------------------------------------------------

## Ejercicio 2 --- Enlace con destino en nueva pestaña

Haz un enlace a **Google** que se abra en una nueva pestaña del
navegador.

``` html
<a href="https://www.google.com" target="_blank">Abrir Google en nueva pestaña</a>
```

------------------------------------------------------------------------

## Ejercicio 3 --- Enlace a una sección interna

Crea un enlace que apunte a una sección con id `contacto` dentro de la
misma página.

``` html
<a href="#contacto">Ir a Contacto</a>
```

------------------------------------------------------------------------

## Ejercicio 4 --- Enlace de correo electrónico

Haz un enlace que permita enviar un correo a `admin@ejemplo.com`.

``` html
<a href="mailto:admin@ejemplo.com">Escribir al administrador</a>
```

------------------------------------------------------------------------

## Ejercicio 5 --- Enlace de teléfono

Crea un enlace que permita llamar al número `+34123456789` desde un
móvil.

``` html
<a href="tel:+34123456789">Llamar al administrador</a>
```

------------------------------------------------------------------------

## Ejercicio 6 --- Enlace de descarga

Crea un enlace que descargue un archivo PDF llamado `manual.pdf`.

``` html
<a href="manual.pdf" download>Descargar manual</a>
```

------------------------------------------------------------------------

## Ejercicio 7 --- Enlace con título emergente

Haz un enlace a **GitHub** que muestre el texto "Repositorio de
proyectos" al pasar el ratón.

``` html
<a href="https://github.com" title="Repositorio de proyectos">Visitar GitHub</a>
```

------------------------------------------------------------------------

## Ejercicio 8 --- Enlace con imagen

Crea un enlace que, al hacer clic en una imagen (`logo.png`), lleve a la
página principal.

``` html
<a href="index.html">
  <img src="logo.png" alt="Logo principal">
</a>
```

------------------------------------------------------------------------

## Ejercicio 9 --- Enlace a archivo local

Haz un enlace que apunte a un documento HTML local llamado `about.html`.

``` html
<a href="about.html">Acerca de</a>
```

------------------------------------------------------------------------

## Ejercicio 10 --- Enlace combinado (varias propiedades)

Crea un enlace a **YouTube** que se abra en una nueva pestaña, con
título emergente y preparado para descarga (aunque no descargue
realmente).

``` html
<a href="https://www.youtube.com" target="_blank" title="Abrir YouTube" download>Ir a YouTube</a>
```

------------------------------------------------------------------------

## Sección de destino de ejemplo

``` html
<h2 id="contacto">Contacto</h2>
<p>Sección de contacto para probar enlaces internos.</p>
```