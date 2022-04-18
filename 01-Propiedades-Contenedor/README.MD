# 01 - Propiedades del contenedor grid

- display: grid
- grid-template
- grid-auto
- gaps

### display grid
Para comenzar a utilizar grid, en el contenedor padre se coloca **`display: grid`**

### grid-template-colums
Indica cuantas columnas va a tener y de que ancho va a ser cada columna.

### grid-template-rows
Indica cuantas filas va a tener y de que altura va a ser cada fila.

### grid-auto
Otra forma de crear filas y columnas, es utilizando grid auto. Esta propiedad define el tamaño de cualquier fila o columna que se crea.

- grid auto row
- grid auto column
- grid auto flow

### grid-auto row
Esta propiedad define un ancho de fila automatico

### grid-auto column
Esta propiedad define un ancho de columna automatico

### grid-auto flow

- row
- column
- dense


Esta propiedad modifica cómo se está llenando nuestro grid.

**grid-auto-flow: row**
Por defecto está el row, ya que cuando los elementos no caben en lo que hemos definido, lo que hace es crear filas nuevas.

**grid-auto-flow: dense** 
Si hay un espacio vacío en el grid, lo que va a hacer es poner los elementos allí, en vez de seguir poniéndolos en filas y columnas.

**grid-auto-flow: column**
Crea nuevas columnas, en vez de nuevas filas.

### gap

**row-gap**
Para definir espacios entre filas y/o columnas
row-gap: crea un espacio solo entre filas (no se crea un espacio entre una fila y el borde de su contenedor).

**column-gap**
se crea un espacio solo entre sus columnas.

**gap**
Es una combinación entre row-gap y column-gap (crea un espacio entre filas y entre columnas con el mismo tamaño)