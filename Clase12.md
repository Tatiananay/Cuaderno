# CLASE 12: ARRAYS
*Date:* *09 de diciembre del 2022*
*Author:* *Nayeli Leiva*
## Introducción a ARRAYs
---

* La declaración en C de un array es
  
>tipo nombre array[dimension]
* La siguiente declaración declara un array de 10 enteros
  
>int a [10];
* Los elementos se acceden como a[0], a[1] . . . a[9]
* Los elementos de un array se almacenan consecutivamente en
memoria
* El nombre del array es la dirección del primer elemento del
array

Consideremos ahora lo siguiente

    int *pa;
    pa=&a[0];

* los elementos del array a[0], a[1]...a[9] están
almacenados en las direcciones de memoria
pa,pa+1,...pa+9 por lo que pueden ser accedidos como
    
        *pa, *(pa+1),. . . *(pa+9)
* Dado que el nombre del array es la dirección del primer
elemento del array, podríamos haber hecho pa=a en lugar de
pa=&a[0];

* C también admite el acceso a los elementos del array de esta
manera

        pa[0], pa[1] pa[9]
