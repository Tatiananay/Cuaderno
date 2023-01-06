#CLASE 22: ARCHIVOS
*Date:* *03 de enero del 2023*

*Author:* *Nayeli Leiva*
```c
//author: Nayeli Leiva
//Fecha: 03 de enero del 2023 
# incluir < iostream >
# include < fstream >  // flujo de información
utilizando el espacio de  nombres  estándar ;
void  leerArchivo (string archivo)
{
    int pagina = 1 ;
    cadena s;
    ifstream f (archivo);

    si (!f. está_abierto ())
        cerr<< " error al abrir el archivo. " <<endl;
    más
        hacer
        {
            obtener línea (f,s);
            cout<<s<<endl;
            si (pag++% 5 == 0 )
            obtener char ();
        } while (!f. eof ());
    F. cerrar ();    
}
int  principal (){
    leerArchivo ( " archivos \\ texto.txt " );
    devolver  0 ;
}
```