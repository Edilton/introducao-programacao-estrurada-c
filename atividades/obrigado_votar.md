
São obrigados a votar pessoas com mais de 18 anos e menos de 70, faça um programa que leia a idade do usuário e informe se ele é obrigado a votar.
```c
#include <stdio.h>

int main() {
    int idade;
    printf("Digite sua idade: ");
    scanf("%d", &idade);

    if (idade >= 18 && idade < 70) {
        printf("Você é obrigado a votar.\n");
    } else {
        printf("Você não é obrigado a votar.\n");
    }

    return 0;
}
```