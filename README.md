# MeuProjeto

#include <stdio.h>
#include <string.h>
#include <windows.h>
#include <locale.h>
#include <conio.h>

void gotoxy(int x, int y)
{
  COORD coord;
  coord.X = x;
  coord.Y = y;
  SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}
void telalogin(void){
	printf("===========================================================================================\n");
  printf("=                                     SISTEMA OS                                          =\n");
  printf("===========================================================================================\n");
	printf("=                                   TELA DE LOGIN                                         =\n"); 
	printf("===========================================================================================\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                          Id:                                                            =\n");
	printf("=                          Senha:                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");	
	printf("=                                                                                         =\n");
	printf("===========================================================================================\n");
}
void telamenu(void){
	printf("===========================================================================================\n");
  printf("=                                     SISTEMA OS                                          =\n");
  printf("===========================================================================================\n");
	printf("=                                   TELA DE INÍCIO                                        =\n"); 
	printf("===========================================================================================\n");
	printf("=--------------------------------------- MENU --------------------------------------------=\n");
	printf("=                                                                                         =\n");
	printf("=                                  1 - Cadastrar cliente                                  =\n");
	printf("=                                  2 - Pedido                                             =\n");
	printf("=                                  3 - Gerenciar cadastros                                =\n");
	printf("=                                  4 - Gerenciar pedidos                                  =\n");
	printf("=                                  5 - Sair do sistema                                    =\n");	
	printf("=                                                                                         =\n");
	printf("===========================================================================================\n");	
}
void telacadastro(void){
	printf("===========================================================================================\n");
	printf("=                            TELA DE CADASTRO DO CLIENTE                                  =\n");
	printf("===========================================================================================\n");		
	printf("=   Nome completo*:                                                                       =\n");
	printf("=   CPF/CNPJ*:                                                                            =\n");
	printf("=   Data de nascimento*:                                                                  =\n");
	printf("=   Sexo*:                                                                                =\n");
	printf("=   E-mail*:                                                                              =\n");
	printf("=   Telefone*:                                                                            =\n");
	printf("=   Telefone p/ recado:                                                                   =\n");
	printf("===========================================================================================\n");
}
void telapedido(void){
	printf("===========================================================================================\n");
	printf("=                                  TELA DO PEDIDO                                         =\n");
	printf("===========================================================================================\n");
	printf("=  Nome:                                                                                  =\n");
	printf("=  CPF ou CNPJ:                                                                           =\n");
	printf("=  Distancia da viagem (KM):                                                              =\n");
	printf("=  Materiais a serem transportados:                                                       =\n");
	printf("=  Tamanho:              Peso:                                                            =\n");
	printf("=                                                                                         =\n");
	printf("=  VALOR FINAL:                                                                           =\n");
	printf("===========================================================================================\n");
}
void telaOS(void){
	printf("===========================================================================================\n");
  printf("=                                  SI TRANSPORTADORA                                      =\n");
  printf("===========================================================================================\n");
	printf("=     ORDEM DE SERVIÇO           NF:                          | Nº                        =\n"); 
	printf("===========================================================================================\n");
	printf("=     NOME DO CONTRATANTE:                                                                =\n"); 
	printf("===========================================================================================\n");
	printf("=                                                                                         =\n");
	printf("=     PLACA:                     TIPO DO VEÍCULO:                                         =\n");
	printf("=     NOME DO MOTORISTA:                                                                  =\n");
	printf("=                                                                                         =\n"); 
	printf("===========================================================================================\n");
	printf("=   MATERIAIS A SEREM TRASNPORTADOS                                    | QUANT.           =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n");
	printf("=                                                                      |                  =\n"); 
	printf("===========================================================================================\n");
	printf("=                         |                                                               =\n");
	printf("=                         |                                                               =\n");
	printf("= ____/____/____          |  ___________________________________________________________  =\n");
	printf("=      DATA               |                     ASSINATURA DO GERENTE                     =\n");
	printf("=                         |                                                               =\n");
	printf("===========================================================================================\n");
	
}
void telaGerenciarCadastro(void){
	system("cls");
	printf("===========================================================================================\n");
	printf("=                          TELA DE GERENCIAMENTE DE CADASTROS                             =\n");
	printf("===========================================================================================\n");		
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                  1 - Alterar cadastros                                  =\n");
	printf("=                                  2 - Inativar cadastros                                 =\n");
	printf("=                                  0 - Voltar para o menu                                 =\n");	
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("===========================================================================================\n\n");
}
void telaGerenciarPedido(void){
	system("cls");
	printf("===========================================================================================\n");
	printf("=                          TELA DE GERENCIAMENTE DE PEDIDOS                               =\n");
	printf("===========================================================================================\n");		
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                  1 - Alterar pedidos                                    =\n");
	printf("=                                  2 - Cancelar pedidos                                   =\n");
	printf("=                                  0 - Voltar para o menu                                 =\n");	
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("=                                                                                         =\n");
	printf("===========================================================================================\n\n");
}
void telaDigitoInvalido(void){
	system("cls");
	printf ("\n\n\n                  =============================================");
	printf ("\n                  =                                           =");
	printf ("\n                  =               DIGITO INVALIDO             =");
	printf ("\n                  =                                           =");
	printf ("\n                  =============================================\n\n\n");
	printf("\n\nPressione qualquer tecla para voltar ao menu inicial");
	getch();
}

main(){
	setlocale(LC_ALL,"Portuguese"); 
	system("color 0a");
	fflush(stdin);
	
	int invalid, i,i2, loop; 
    char id[9],senha[9], op1,opcao, charnome[25], telefone2[15],telefone[15], cnpj[18], dataNasc[15], sexo[10], email[30];
	float distV, materiais, tamanho, peso, valorF;
	
	invalid=distV=materiais=tamanho=peso=valorF=0;
	loop, invalid = 1;
	op1=' ';
	
	while(invalid<4){
		telalogin();
		gotoxy(31,10);
		fflush(stdin);
		scanf ("%s", &id);
		
		gotoxy(34,11);
		fflush(stdin);
		//scanf ("%s", &re);
		for (i2=0;i2<9;i2++) {
        	senha[i2] = getch();
       		printf("*");
       		if(senha[i2]==13){
       			i2=10;
			}
    	}
    	
		if ((strcmp(senha,"sistemaos"))&&(strcmp(id,"sistema")==0)){
			opcao = ' ';														//
			invalid = 10;                                                       // LOGIN NO SISTEMA		
		}																		//
		else{
			system("cls");
			invalid++;
			opcao='5';
		}
		if(invalid==4){
			printf("\n\nVoce informou um codigo invalido 3 vezes... Desconectando");
		}
	}
		
	while (opcao!='5'){
	    system("cls");
		opcao  = '0'; 
		telamenu();
		printf("   Pressione o numero da opcao desejada: ");
	    fflush(stdin);
		opcao = getch();
		//scanf("%c",&opcao);	
		if (opcao == '1'){ 
			system("cls");
			telacadastro();
			fflush(stdin);
			gotoxy(20,3);
			gets(charnome);
			
			fflush(stdin);
			gotoxy(15,4);
			gets(cnpj);
			
			fflush(stdin);
			gotoxy(25,5);
			gets(dataNasc);
			
			fflush(stdin);
			gotoxy(11,6);
			gets(sexo);
			
			fflush(stdin);
			gotoxy(13,7);
			gets(email);
			
			fflush(stdin);
			gotoxy(15,8);
			gets(telefone);
			
			fflush(stdin);
			gotoxy(24,9);
			gets(telefone2);
		
	
			printf("\n\nPressione qualquer tecla para voltar ao menu inicial");
			fflush(stdin);
			getch();	
		}
		else if (opcao == '2'){
			system("cls");	
			telapedido();
				gotoxy(8,3);    
				puts(charnome);  // Imprimi o nome e cpf na tela pedido
				gotoxy(15,4);
				puts(cnpj);
			
			gotoxy(28,5);
			scanf("%f",&distV);
		
			gotoxy(35,6);
			scanf("%f",&materiais);
		
			gotoxy(11,7);
			scanf("%f",&tamanho);
		
			gotoxy(30,7);
			scanf("%f",&peso);
