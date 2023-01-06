## CLASE 5: Git + Markdown
---- 
*Date:* *16 de noviembre del 2022*

*Author:* *Nayeli Leiva*
## Sintaxis de escritura y formato básicos
### Encabezados
---
Para crear un encabezado, agrega entre uno y seis símbolos # antes del encabezado del texto. El número de # que use determinará el tamaño del encabezado.

        # The largest heading
        ## The second largest heading
        ###### The smallest heading
### Estilos de texto
---
|estilo     |Sintaxis       |
|-----------|-------------- | 
|Bold       |** ** o __ __  |
|Cursiva    |* *  o _ _     |
|Tachado    |~~ ~~          |
|Subscript  | <sub .> </sub .>|       
|Superscript| <sup.> </sup.> |
### Entrecomillado de texto
---
Puede entrecomillar texto con >.


        Text that is not a quote

        > Text that is a quote
**Example:**

Text that is not a quote

> Text that is a quote
### Vínculos
---
Puede crear un vínculo en línea escribiendo su texto entre corchetes [ ] y escribiendo la URL entre paréntesis ( ). También puedes usar el método abreviado de teclado Comando+K para crear un vínculo. Cuando tienes texto seleccionado, puedes pegar una dirección URL del Portapapeles para crear un vínculo automáticamente a partir de la selección.

También puedes crear un hipervínculo de Markdown resaltando el texto y usando el método abreviado de teclado Comando+V. Si quieres reemplazar el texto por el vínculo, usa el método abreviado de teclado Comando+Mayús+V.

    This site was built using [GitHub Pages](https://pages.github.com/).
### Imágenes
---

Puede mostrar una imagen agregando ! y ajustar el texto alternativo en [ ]. Escriba el vínculo de la imagen entre paréntesis ().

    ![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
### Listas de tareas
---

Para crear una lista de tareas, debe añadir como prefijo un guion y espacio, seguido de [ ] a los elementos de la lista. Para marcar una tarea como completada, use [x].

        - [x] #739
        - [ ] https://github.com/octo-org/octo-repo/issues/740
        - [ ] Add delight to the experience when all tasks are complete :tada:

