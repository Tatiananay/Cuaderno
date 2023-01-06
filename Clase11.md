## CLASE 11: FUNCIONES Y PROCEDIMIENTOS.
---
*Date:* *07 de diciembre del 2022*

*Author:* *Nayeli Leiva*

## Funciones:

* Un programa e C es una colección de funciones.
* Una de esas funciones se llama main y es la primera en
ejecutarse
* Las funciones pueden residir en uno o varios ficheros fuente
* Cada función tiene la forma
  
        tipo de dato nombre funcion (declaraciones argumentos)
        {
        declaraciones y sentencias
        }
* Se puede omitir el tipo de dato que devuelve la función (en
ese caso se asume que es int
Sistemas Operativos El Lenguaje de programación C 92 / 218
* Una función puede no tener argumentos o no tener
declaraciones o sentencias

        funcion_simple()
        {
        }
* Cuando una función no lleva parámetros o no devuelve ningún
valor se usa el término void
void funcion_nada(void)
```c
#include <stdio.h>

#include <stdio.h>


// función : Tipo de Dato (no void) -> int, float, loble long, short,  ......  [return]
int Suma()
{
    int n1, n2, rta;
    n1 = 10;
    n2 = 23;
    rta = n1 + n2;
    return rta;
}

// función + parametros
int SumaPara(int n1, int n2)
{
    int rta;
    rta = n1 + n2;
    return rta;
}
// función que suma numeros enteros
int SumaParaShort(int n1, int n2)
{
    // forma corta de sumar sin variables
    return n1 + n2;
}

void main( )
{
    int rta = 0;
    rta = Suma();
    printf("\n La suma es: %d", rta);

    printf("\n ----------------- \n");

    rta = SumaPara(42,52);
    printf("\n La suma es: %d", rta);
   
    printf("\n ----------------- \n");
    printf("\n La suma es: %d", SumaParaShort(42,52) );
}
``` 