#include <stdio.h>


int main(){
	
int numero_suspeitos  , numero_confirmados , numero_mortes;//variaveis de controle de dados;
int total;// soma dos dados;


printf("\nPreencha com as seguintes informacoes sobre a Dengue no Brasil");
printf("\n");
printf("Casos suspeitos: \n");
scanf("%d", &numero_suspeitos);
printf("Casos confirmados: \n");
scanf("%d", &numero_confirmados);
printf("Quantidade de mortes: \n");
scanf("%d", &numero_mortes);

printf("Diante dos dados computados , segue a tabela que apresenta a situação atual da dengue no Brasil\n");

printf("Casos suspeitos: %d\n" , numero_suspeitos );
printf("Casos confirmados: %d\n" , numero_confirmados);
printf("Quantidade de Mortes: %d\n" , numero_mortes);

total= numero_mortes + numero_confirmados + numero_suspeitos;

printf("Total de dados: %d" , total );

	return  0;
}
