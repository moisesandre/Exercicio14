# Exercicio14

#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <math.h>
#include <string.h>
int main()
{
    system("color 0b");

    int i, tam;
    char nome[50];

    printf("Digite um  nome: ");
    gets(nome);

    tam = strlen(nome);

    for (i=1; i<=tam; i++)
    {
        printf("%s\n",nome);
    }

 return 0;
}
