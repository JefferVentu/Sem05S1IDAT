## FLEXIBOX

1. **`display: flex;`**: Esta propiedad se aplica al contenedor padre para activar el modelo de diseño flexbox en sus elementos secundarios (hijos). Cuando se aplica a un contenedor, los elementos secundarios dentro de ese contenedor se comportan como elementos flexibles.

2. **`justify-content: center;`**: Esta propiedad se aplica al contenedor padre y se utiliza para alinear los elementos secundarios horizontalmente. En este caso, `center` centra los elementos secundarios a lo largo del eje principal del contenedor.

3. `align-items: center;`: Esta propiedad se aplica al contenedor padre y se utiliza para alinear los elementos secundarios verticalmente. En este caso, `center` alinea los elementos secundarios en el centro a lo largo del eje transversal del contenedor.

4. `justify-content: space-around;`: Esta propiedad se aplica al contenedor padre y se utiliza para distribuir uniformemente los elementos secundarios con un espacio igual alrededor de ellos a lo largo del eje principal del contenedor.

5. `order: 1;` : Esta propiedad se aplica a los elementos secundarios y se utiliza para cambiar el orden de visualización de los elementos flexibles dentro del contenedor. En este caso, `1` establece el orden del elemento en segundo lugar.

6. `align-self: flex-end;`: Esta propiedad se aplica a elementos secundarios individuales dentro del contenedor y anula la alineación predeterminada definida por `align-items` en el contenedor padre. En este caso, `flex-end` alinea el elemento secundario en la parte inferior del contenedor.

7. `flex-wrap: wrap;`: Esta propiedad se aplica al contenedor padre y se utiliza para permitir que los elementos secundarios se envuelvan en múltiples líneas si no caben en una sola línea dentro del contenedor.