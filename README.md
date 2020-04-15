#include<iostream>
#include<conio.h>
using namespace std;

double suma(double x, double y){//Declarada directamente
	double res;//Declaracion de variable local
	res = x+y;//suma de manera local
	return res;//regresa el resultado de la suma, con la variable "res"
}

	int main(){
	double x,y,res;
	
	cout<<"ingresa el Numero 1: ";
	cin>>x;
	cout<<"ingresa el Numero 2: ";	
	cin>>y;	
		
		res = suma(x,y);//funcion sumar
		cout<<"El resultado es: "<<res;
		
		getch();
		return 0;	
	}//fin del main
