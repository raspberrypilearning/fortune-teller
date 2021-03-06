## Tomando una decisión

Hagamos que tu micro:bit tome una decisión al azar eligiendo un número (`0` para 'No' y `1` para 'Sí').

+ Agrega un nuevo evento `al presionar el botón A` a tu código.

![captura de pantalla](images/fortune-on-a-pressed.png)

+ Vamos a crear una nueva variable para almacenar la respuesta. Haz clic en 'Variables' y luego en 'Crear una variable'.

![captura de pantalla](images/fortune-variables.png)

+ Nombra la nueva variable como `respuesta`.

![captura de pantalla](images/fortune-answer.png)

+ Arrastra un bloque `establecer` de las Variables a tu bloque `al presionarse el botón A` y selecciona la variable `respuesta`.

![captura de pantalla](images/fortune-set.png)

Como puedes ver, el `para` en el bloque significa que puedes establecer la respuesta al monitor.

+ Haz clic en 'Matemática' y arrastra un bloque `escoger al azar` después de `para`:

![captura de pantalla](images/fortune-random.png)

+ Dile al bloque aleatorio que elija un número entre 0 y 1. Así es como debe verse tu código:

![captura de pantalla](images/fortune-random-1.png)

+ A continuación, quieres mostrar la palabra `No` en el micro:bit solo `si` la `respuesta` es 0.

Para hacer esto, arrastra un bloque `si` a la parte baja de tu evento `al presionar el botón A`:

![captura de pantalla](images/fortune-if.png)

+ Luego arrastra un bloque `=` como condición en el `si`:

![captura de pantalla](images/fortune-equals.png)

+ Arrastra tu variable `respuesta` al lado izquierdo del bloque `si`.

![captura de pantalla](images/fortune-if-finished.png)

+ Cualquier código dentro del bloque `si` se ejecutará si la `respuesta` es 0. Como 0 es `No`, vamos a añadir un bloque `mostrar cadena`.

![captura de pantalla](images/fortune-no.png)

+ Prueba tu código. 
    + A veces la `respuesta` será 0, y el micro:bit debe decir 'No'.
    + A veces la `respuesta` será 1, y ¡no pasará nada!