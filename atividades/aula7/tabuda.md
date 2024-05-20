
Faça um programa que calcule a tabuada de multiplicação de número que o usuário digitar.

```c
#include <stdio.h>

int main() {
    int numero, i;

    printf("Digite um numero para ver sua tabuada de multiplicacao: ");
    scanf("%d", &numero);

    printf("Tabuada de multiplicacao para %d:\n", numero);
    for (i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", numero, i, numero * i);
    }

    return 0;
}

```