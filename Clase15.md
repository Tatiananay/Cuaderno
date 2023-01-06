# CLASE 15: Resumen teoría.
*Date:* * 14 de diciembre del 2022*

*Author:* *Nayeli Leiva*
## Directivas del precompilador

#include Incluye el fichero, cuyo nombre se indica, para su compilaci´on
con el resto del Código
- Si el nombre del fichero va entre <...> se busca en el
directorio include del sistema (/usr/include). 

Por ejemplo
#include <stdio.h>
hace que el fichero /usr/include/stdio.h se incluya en ese
punto para ser compilado con nuestro fichero fuente
- El nombre se puede poner entre comillas (“) y el sistema lo
buscar´a en el directorio actual (tambi´en se puede poner una
ruta absoluta)
- Los ficheros se suelen denominar .h y contienen declaraciones
de tipos, variables y prototipos de funciones (son ficheros
fuente que pueden verse)
#define Define un símbolo, es decir cada ocurrencia de ese s+ímbolo es
sustituida por su definición. Por ejemplo
- El C distingue entre mayúsculas y minúsculas, aunque la
costumbre es utilizar mayúsculas para los símbolos definidos
por el preprocesador

- **Ejemplo**
  
#define MAX 1024
hace que todas las ocurrencias de la cadena MAX dentro del
código son sustituidas por 1024
* El código que se compila lleva 1024 donde iba MAX
* Si MAX iba dentro de comill as ’’...‘‘, no se sustituye
  
![xd](https://www.it.uc3m.es/~pedmume/asignaturas/2005/LAO/Lab2/tutorial4/www-etsi2.ugr.es/depar/ccia/mp2/old/apoyo/modelo/img1.gif)
**Además**
![](https://cdn.educba.com/academy/wp-content/uploads/2020/01/Escape-Sequence-is-C.png)