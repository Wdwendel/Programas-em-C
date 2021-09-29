# Programas-em-C
atividades em linguagem c

programa em c  se o eleitor e obrigado ou não a votar
usando o comando de laço.

#include<stdio.h>

int main(){
	float idade;
	printf("informe sua idade: \n");
	scanf("%f",&idade);
	
		if(idade<=16){
			printf("voto nao obrigatorio\n");
		}
		else if (idade>=18, idade<=65){
			printf("voto obrigatorio");
		}
		else if (idade>=65){
			printf("eleitor facultativo");
		}
		else{
			printf("idade incorreta");
		}
}
