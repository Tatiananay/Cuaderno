# CLASE 10: Bucles
*Date:* *06 de diciembre del 2022*

*Author:* *Nayeli Leiva*
### ***Codificación del ejemplo de algoritmia.***
```c
#include <stdio.h>

/**
 * @author  : Nayeli Leiva
 * @date    : 6.dic.2022
 * @details : Determinar el área de un rectángulo 
 */
int main()
{   //declarar e inicializar las variables
    int logitud =0, ancho=0, areaRect =0;
    
    printf("\n << Calula el area de un rectangulo >> \n ");
    printf("Ingrese la Logitud: ");
    scanf("%i", &logitud);

    printf("Ingrese la ancho: ");
    scanf("%i", &ancho);

    areaRect = logitud * ancho;

    printf("EL el area del rectangulo es: %i \n",areaRect);
    printf("EL el area del rectangulo de ancho %i y longitud %i es %i \n",ancho, logitud, areaRect);

    return 0;
}
```
## La proposición for–while–do_While
>## Bucle cuadrado con for:
```c
#include <stdio.h>
 
int main()
{
 
    int num, a, b;
 
    printf("Numero de signos para el cuadrado:");
    scanf("%d",&num);
 
    for(b=1; b <= num; b++)
    {
        for(a=1; a<= num; a++)
        {
            if(b==1 || b== num)
            {
                if (a%2==0)
                printf("+ ");
                else
                printf("- ");
                
            }else if(a==1 || a== num){
                if (b%2==0)
                    printf("+ ");
                else
                    printf("- ");
            }else{
 
                printf("  ");
            }
        }
        printf("\n");
    }
}
```

>## Bucle escalera con for;
---

```c
int main(void)
{
    int nivel=5;
    
    for (int i = 0; i < nivel*2; i++)
    {
        if (i%2==0)
        {
            printf("__\n");
        }
        else
        {
            for (int f = 0; f <= i; f++)
                printf(" ");
            printf("|");        
        }
    }
     printf("\n\n");
    return 0;
}
```