
https://replit.com/@izau/codico#main.c
#include <math.h>
#include <stdio.h>
int main() {
  int numero1, numero2;
  int soma, subtracao, multiplicacao, divisao;
  int num;
  int potencia;
  float numero;
  float raiz;

  printf("Nome: izau de azevedo sampaio \n");
  printf("Curso: Analise e desenvolvimento de sistemas \n");
  printf("Universidade: La salle \n");
  printf("Matricula: 202220408 \n");

  printf("informe um número para elevar ele a potencia: ");
  scanf("%d", &num);

  printf("informe um número para saber a raiz dele: ");
  scanf("%f", &numero);

  potencia = pow(num, 2);
  raiz = sqrt(numero);

  printf("O resultado da potenciacao é: %d\n", potencia);
  printf("O valor da raiz é: %.2f\n", raiz);

  printf(
      "**Operaçoes aritmeticas de soma,subtraçao,multiplicacao e divisao**\n");
  printf("informe o primeiro número: ");
  scanf("%d", &numero1);

  printf("informe o segundo número: ");
  scanf("%d", &numero2);

  soma = numero1 + numero2;
  subtracao = numero1 - numero2;
  multiplicacao = numero1 * numero2;
  divisao = numero1 / numero2;

  printf("numero1: %d\n", numero1);
  printf("numero2: %d\n", numero2);
  printf("soma: %d\n", soma);
  printf("subtracao: %d\n", subtracao);
  printf("Multiplicaçao: %d\n", multiplicacao);
  printf("divisao: %d\n", divisao);

  printf("*Obsevarção**\n");
  printf("Esse codigo foi adaptado do ebook");

  return 0;
}
