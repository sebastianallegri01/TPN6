#include <bits/stdc++.h>
using namespace std;
string CalcularDDD(int codigo);
int main (){
	int codigo;
	
	cout<<"Ingrese los numeros del destino que quiere llamar: "<<endl;
	cin>>codigo;
	
	cout<<CalcularDDD(codigo)<<endl;
	
	return 0;
}

string CalcularDDD(int codigo){
	string msg;
	
	switch (codigo){
		case 61:
			msg="Usted esta llamando a Brasilia";
			break;
		case 71:
			msg="Usted esta llamando a Salvador";
			break;
		case 11:
			msg="Usted esta llamando a Sao Pablo";
			break;
		case 21:
			msg="Usted esta llamando a Rio de Janeiro";
			break;
		case 32:
			msg="Usted esta llamando a Juiz de fora";
			break;
		case 19:
			msg="Usted esta llamando a Campinas";
			break;
		case 27:
			msg="Usted esta llamando a Vitoria";
			break;
		case 31:
			msg="Usted esta llamando a Belo Horizonte";
			break;
		default:
			msg="USTED A INGRESADO UN NUMERO INCORRECTO";
			break;	
		
		}
	
	return  msg;
}
