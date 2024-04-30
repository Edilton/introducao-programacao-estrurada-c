Um restaurante precisa de um programa para o seu restaurante tem 4 opções de pratos:
- 1-Açaí e Peixe
- 2-Açaí e Carne
- 3-Açaí e Frango
- 4- Açaí e Charque

Faça o programa, que leia o pedido do usuário e imprima na tela a opção escolhida.  

--- 
Resposta:
```c #include <stdio.h>

int main() {
    int escolha;

    printf("Menu:\n");
    printf("1. Açaí e Peixe\n");
    printf("2. Açaí e Carne\n");
    printf("3. Açaí e Frango\n");
    printf("4. Açaí e Charque\n");
    printf("Escolha uma opção: ");
    scanf("%d", &escolha);

    switch (escolha) {
        case 1:
            printf("Você escolheu Açaí e Peixe.\n");
            break;
        case 2:
            printf("Você escolheu Açaí e Carne.\n");
            break;
        case 3:
            printf("Você escolheu Açaí e Frango.\n");
            break;
        case 4:
            printf("Você escolheu Açaí e Charque.\n");
            break;
        default:
            printf("Opção inválida.\n");
    }

    return 0;
}
```
