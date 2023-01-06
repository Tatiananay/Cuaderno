# CLASE7: Operadores
 *Date:* *21 de noviembre del 2022*

*Author:* *Nayeli Leiva*
## Ejemplos de tipos de operdores.
---
![operadores](https://fisiprogramacion.files.wordpress.com/2014/07/tabla_operadores1.png)

## Primer ejemplo:
---
```c
#include <stdio.h>
//@author: Nayeli Leiva
//Date: 21.11.2022
int main()
{
    int num1,num2,resultado,a=3,b=8; //Declarar variables

    printf("ingrese el primer valor\n");
    scanf("%i",&num1);
    printf("ingrese el segundo valor\n");
    scanf("%i",&num2);
    resultado = a*(num1 + num2);
    printf("el resultado de la suma es:%i\n",resultado);
    return (0);

```
## Segundo  ejemplo

---
```c
#include <stdio.h>
int main(void)
{
    int a, b;
    printf("Introduce dos enteros separados por un espacio: \n");
    scanf("%i %i", &a, &b);

    if (a > b)
        printf("El mayor es %i", a);
    
    if (b > a)
            printf("El mayor es %i", b);
    if (b == a)
            printf("son iguales");

    // if (a>b)
    //     printf("El mayor es %i", a);
    // else
    //     if (b > a)
    //         printf("El mayor es %i", b);
    //     else
    //         printf("son iguales");
    printf("\n");
}
```
