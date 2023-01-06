# CLASE 6: Introducción a C
*Date:* *18 de noviembre del 2022*

*Author:* *Nayeli Leiva*
## Introducción General
En 1972 es Dennis Ritchie(delosLaboratoriosBelldeAT&T) quien diseña finalmente C apartir del B de Thompson, aportando un diseño de tipos de datos y estructuras de datos.
Es un lenguaje que permite realizar una programación estructurada economizando las expresiones,con abundancia de operadores y tipos de datos (aunque los básicos sean pocos).

![C](https://i0.wp.com/imgs.hipertextual.com/wp-content/uploads/2019/06/hipertextual-quieres-aprender-programar-c-empieza-con-estos-cursos-online-2019651362.jpg?fit=1920%2C1086&quality=50&strip=all&ssl=1)

**Tipos de datos:**
* int
* float
* double 
* char
* boll
* ...

**Control de flujo** 
* if-else
* for(n)
* while(<> !=)
* do-while(< >  !=  ==)
* beak;
* switch
**Características de c:**

1. Programación estructurada (UNIX "ANSI C")
2. Lenguaje Natural
3. Lenguaje de máquina  *.exe "1001010010001"

## Hello world !
```c
#include <stdio.h> // llama a las librerias

//NOTAS
//1. Guardar :   ctrl s
//2. Compilar:  gcc src/main.c -o output/main.exe
//3. ejecutar:  ./output/main.exe
//4. script  :  main.c  	para    c 	 --> compilar se usa gcc 
//				main.cpp  	para	c++  --> compilar se usa g++

int main()
{
	printf("Hello pat_mic!\n");
	return (0);
} 
```
