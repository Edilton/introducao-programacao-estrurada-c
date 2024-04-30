
Para comprar meia entrada no cinema a pessoa tem que ter acima de 60 anos ou ser estudante. Vamos escrever um programa que verifica se o usuário tem direito ao desconto com base na idade e se ele é um estudante.

```c
#include <stdio.h>

int main() {
    int idade;
    char ehEstudante;

    // Entrada de dados
    printf("Qual a sua idade? ");
    scanf("%d", &idade);
    printf("Você é estudante? (S/N) ");
    scanf(" %c", &ehEstudante);

    // Verifica se a pessoa tem direito à meia entrada
    if (idade >= 60 || ehEstudante == 'S' || ehEstudante == 's') {
        printf("Você tem direito à meia entrada.\n");
    } else {
        printf("Você não tem direito à meia entrada.\n");
    }

    return 0;
}
```
