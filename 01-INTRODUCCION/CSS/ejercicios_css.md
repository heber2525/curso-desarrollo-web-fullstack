# Ejercicios CSS

1. Estilos en atributo HTML

    Aplica un color de fondo azul y un tamaño de fuente de 16px a un párrafo usando el atributo style.

2. Estilos internos

    Crea un bloque de estilos dentro del documento HTML y cambia el color de todos los encabezados h1 a verde.

3. Estilos externos
    
    Crea una hoja de estilos externa y vincúlala a tu documento HTML. Establece el color de fuente de todos los párrafos en rojo.

3. Selectores de etiqueta

    Utiliza un selector de etiqueta para cambiar la fuente de todas los párrafos a "Arial".

4. Selectores de clase

    Crea una clase llamada "destacado" que cambie el color de fondo a amarillo y la fuente a negrita. Aplícala a un párrafo y a un elemento de lista.

5. Selectores de ID
    
    Crea un selector de ID para un elemento con el ID "encabezado-principal" que cambie el tamaño de fuente a 32px y el color del texto a azul oscuro.

6. Selectores de descendientes y de hijos

    Utiliza selectores de descendientes y de hijos para aplicar el estilo a los siguientes elementos:

    - Todos los elementos li dentro de una lista ordenada (ol) deben tener una fuente en cursiva.
    -  Solo los elementos li que sean hijos directos de una lista no ordenada (ul) deben tener una viñeta de estilo cuadrado.

7. Selectores de atributo
    
    Utiliza un selector de atributo para cambiar el color de todos los enlaces que tengan un atributo href que contenga "http://" a naranja.

    Si lo necesitas aquí tienes documentación para resolver este ejercicio: https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Selectors/Attribute_selectors#selectores_de_presencia_y_valor

8. Especificidad
    
    Dado el siguiente HTML:

    ```
    <div id="container">
        <p class="text">Esto es un párrafo dentro de un div.</p>
    </div>
    <p class="text">Esto es un párrafo dentro de un div.</p>
    ```

    Crea reglas CSS utilizando diferentes niveles de especificidad para lograr lo siguiente:

    - El texto de todos los párrafos debe ser azul por defecto.
    - El texto de los párrafos con la clase "text" debe ser rojo.
    - El texto del párrafo con la clase "text" dentro del div con ID "container" debe ser verde.
