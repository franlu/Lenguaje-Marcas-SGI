# Domina los selectores CSS

**Objetivo:** Identificar, escribir y aplicar correctamente los
selectores básicos de CSS: por etiqueta, id, clase, descendientes, hijos
directos, agrupados y pseudo--clases simples.

## Ejercicio 1: Selectores por etiqueta

Copia este HTML en tu editor:

``` html
<p>Este es un párrafo.</p>
<p>Este es otro párrafo.</p>
<h2>Este es un título</h2>
```

**Tarea:** - Todos los `<p>` deben ser **azules**\
- Todos los `<h2>` deben ser **rojos**



## Ejercicio 2: Selectores por clase

Añade al HTML:

``` html
<p class="importante">Este párrafo es importante.</p>
<p class="aviso">Este párrafo es un aviso.</p>
```

**Tarea:** - `.importante` debe aparecer en **negrita**\
- `.aviso` debe aparecer en **color naranja**



## Ejercicio 3: Selector por ID

Añade:

``` html
<h3 id="titulo-principal">Título principal de la página</h3>
```

**Tarea:** - Aplica al ID `titulo-principal` un **tamaño de letra de
24px**\
- Sube la especificidad modificando solo el CSS (usa etiqueta + id o
clase + id)


## Ejercicio 4: Selector descendiente

Añade:

``` html
<div class="contenedor">
    <p>Texto dentro del contenedor.</p>
</div>

<p>Texto fuera del contenedor.</p>
```

**Tarea:** - Haz que solo el `<p>` dentro de `.contenedor` aparezca en
**verde**


## Ejercicio 5: Selector hijo directo (`>`)

Añade:

``` html
<ul class="menu">
    <li>Inicio</li>
    <li>Contacto</li>
    <li>
        Servicios
        <ul>
            <li>Web</li>
            <li>Redes</li>
        </ul>
    </li>
</ul>
```

**Tarea:** - Haz que solo los `li` hijos directos de `.menu` tengan
**fondo gris claro**


## Ejercicio 6: Agrupación de selectores

**Tarea:** - Agrupa `h1`, `h2` y `h3` para que compartan:\
- color: morado\
- fuente: Arial

Ejemplo:

``` css
h1, h2, h3 {
}
```


## Ejercicio 7: Pseudo--clases simples

Añade:

``` html
<a href="#">Enlace 1</a>
<a href="#">Enlace 2</a>
```

**Tarea:** - Con `a:hover`, al pasar el ratón los enlaces deben ponerse
**rojos**\
- Con `a:active`, al hacer clic deben ponerse **verdes**


## Ejercicio 8: Selectores combinados

Añade:

``` html
<p class="aviso">Este es un aviso general.</p>
<p class="aviso destacado">Este es un aviso destacado.</p>
```

**Tarea:** - `.aviso.destacado` debe tener un **borde de 2px sólido
rojo**
