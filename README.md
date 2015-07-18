// Algoritmos-1
// IS120 -  Tareas

#include "stdafx.h"
#include "conio.h"
#include <iostream>
using namespace std;

void main()
{int sal_bruto, sal_neto;
 cout<<"Ingresar salario bruto: ";
 cin>>sal_bruto;
 if(sal_bruto>2960)
    sal_neto = sal_bruto*(1-0.12-0.13);
 else
    sal_neto = sal_bruto*(1-0.12);
 cout<<endl<<"Salario neto es: "<<sal_neto;
 getch();
}


