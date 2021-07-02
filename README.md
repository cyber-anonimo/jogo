#include<iostream>
#include<cstdlib>
#include<ctime>
#define correto 100
#define chanche 10
using namespace std;

int main(){
	
	int numero[chanche];
	int resposta = 0;
	int tentativa = 0;
	srand(time(NULL));
	
	for(int i = 0; i < chanche; i++){
		resposta = rand() % correto;
	
	cout << "Digite um numero: ";
	  cin >> resposta;
	
	  if(tentativa < resposta){
		cout << "Errado, mais.";	
	}else if(tentativa > resposta){
		cout << "Errado, menos.";	
	}else if(tentativa = resposta){
		cout << "meus parabens, voce acertou";
	}else if(numero > chanche){
		cout << "Que pena, voce nao conseguiu." << "O numero certo era" << rand;
	}
   }
	
   
system("pause");
return 0;	
}
