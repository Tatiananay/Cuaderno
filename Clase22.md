# CLASE 22:WORKSHOP - PET SHOP.
*Date:* *04 de enero del 2023*

*Author:* *Nayeli Leiva*

## Objetivo: Crear un menú de una tienda de mascotas.
### ***Primera parte:***
```c++
//Author: Nayeli Leiva
//Date: 04-01-2023
#include<iostream>
#include<stdlib.h>
#include<../lib/utility.h>
#include<../lib/color.h>  //se utlizaron librerias propias.
using namespace std;
void menu(){
    system("clear")
    cout<<"COLOR_RED   "texto RED!;
    cout<<"------PET-SHOP-------"<<endl;
    cout<<"1. Agregar mascota"<<endl;
    cout<<"2. Lista de mascotas"<<endl;
    cout<<"3. Vender mascota"<<endl;
    cout<<"0. Salir"<<endl;
    do{
        opc=getNumber("Ingresa tu opc: ");
    }while (opc>3);
    return opc;
}

void agregarPet(){cout<<"agregaPet...!"}
void ListaPet(){cout<<"listaPet...!"}
void venderPet(){cout<<"venderPet...!"}
int main(){
    switch(menu()){
        case 1:

    }
    return 0;
}

void agregarPet(){
    string s;
    ifstream f (tatiananay);
    if(!f.is_open())
        cerr<<"error de abrir el archivo de mascotas"<<endl;
    else
        do
        {
            getline(f,s)
            cout<<s<<endl;
        } while (!f,eof());
    f.close();
        
}
void leerarchivo()

```
## ***Fin del primer bimestre***