# wendel
projetos_faculdade


#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

main() 

{
	int numero1=0,numero2=0;
	
	printf("Digite o primeiro numero: ");
	scanf("%i",&numero1);
	printf("Digite o segundo numero: ");
	scanf("%i",&numero2);
	
	if (numero1 > numero2)
	{
		printf("O maior numero e: %i",numero1);
	}
	
	else
	{
		printf("O maior numero e: %i",numero2);
		
	}
	
	system("pause>>null");
}
