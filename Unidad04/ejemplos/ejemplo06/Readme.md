# Ejemplo06 

### GRID - Colocación Implicita

En este ejemplo, la cuadrícula se divide en dos columnas y dos filas con una 
anchura y altura de 100 píxeles respectivamente. La propiedad grid-auto-columns 
se utiliza para establecer el ancho de las columnas generadas automáticamente, 
en este caso, 50 píxeles. De manera similar, grid-auto-rows se utiliza para establecer
la altura de las filas generadas automáticamente. La propiedad grid-auto-flow 
se establece en row dense para que los elementos se coloquen automáticamente en 
filas y se ajusten para evitar espacios vacíos.

Los elementos con clases item1 a item3 se colocan explícitamente en la cuadrícula
con la propiedad grid-column y grid-row, mientras que los elementos con clases 
item4 a item8 se colocan automáticamente en la cuadrícula. Los elementos tienen 
un borde negro, texto centrado, tamaño de fuente de 20 píxeles y negrita para 
mayor legibilidad.