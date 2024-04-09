#include <stdio.h>

int main(){
char nomeProduto[50];
char Quantidade[50];
float Precodevenda;
int opcao;
int continuar;
 
 do{
 
 // Menu de opções
        printf("\n========== MENU ==========\n");
        printf("1. Cadastrar produto\n");
        printf("==========================\n");
      

 // cadastro do produto 
     printf("Informe o nome do produto:");
     scanf("%s",nomeProduto);
     printf("Informe a quantidade em estoque: ");
     scanf("%s", Quantidade);
     printf("Informe o preco do produto: ");
     scanf("%f", &Precodevenda);
     

 // dados do produto em estoque
     printf("-----------------------------------\n");
     printf("Dados do produto cadastrado:\n ");
     printf("-----------------------------------\n");
     printf("%s\n",nomeProduto);
     printf ("R$%.2f\n", Precodevenda);
     printf("Quantidade: %s\n", Quantidade);
     printf("Digite 1 para continuar ou 2 para sair");
     scanf("%d",&continuar );
     break;

 
    }while(1==continuar);
 
     printf("Informe o nome do produto:");
     scanf("%s",nomeProduto);
     printf("Informe a quantidade em estoque: ");
     scanf("%s", Quantidade);
     printf("Informe o preco do produto: ");
     scanf("%f", &Precodevenda);
     
     
 

    return 0;
    
}
