# TEMAS DE EVALUACIÓN
*Date:* *23 de diciembre del 2022*

*Author:* *Nayeli Leiva*

***Crear una barra de loaging:***
```c
# incluir < iostream >
# include < conio.h >
# incluir < ventanas.h >
# incluir < dos.h >
utilizando el espacio de  nombres  estándar ;
int  principal ()
{
    sistema ( " cls " );
        para ( int i= 1 ;i<= 50 ;i++)
            { sistema ( " cls " );
cout<< " \t                   Cargando " << 2 *i<< " % \n\t " ;
para ( int j= 1 ;j<=i;j++)
    cout<< " \xB2 " ;
si (i> 1 && i< 20 )
    cout<< " \n\n\t\t creando archivos temporales " ;
si  no (i> 20 && i< 40 )
    cout<< " \n\n\t\t Accediendo a la Memoria Principal " ;
si  no (i> 40 && i< 48 )
    cout<< " \n\n\t\t Caché de Acceso " ;
else cout<< " \n\n\t\t Completado. Presiona enter para continuar " ;
    Sueño ( 150 - i* 3 );
    }
obtener ();
devolver  0 ;
}
```

