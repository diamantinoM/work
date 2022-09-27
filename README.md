#include <stdio.h>
#include <string.h>  

int main(){
  
  // definiçao de uma estrutura
  struct aluno{
    char nome[30];
    int n_matricula;
    char curso[30];
  };
  
  // declaração da estrutura
  struct aluno eu;
  
  // inicialização das variáveis da estrutura
  strcpy(eu.nome, "Diamantino");             
  eu.n_matricula = 22031;
  strcpy(eu.curso, "Programador");
  
  // imprimir os dados
  printf("Perfil do Aluno:\nNome = %s\nNumero da matricula = %i\nNome do curso = %s\n", eu.nome, eu.n_matricula, eu.curso);
  
  return 0;
}
