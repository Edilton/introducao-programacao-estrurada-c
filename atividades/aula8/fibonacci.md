Sequência de Fibonacci: Escreva um programa em C que imprime os primeiros n termos da sequência de Fibonacci. A sequência de Fibonacci é uma série de números onde cada número é a soma dos dois anteriores. Por exemplo, a sequência começa com 0, 1, 1, 2, 3, 5, 8, 13, ...


```c
#include <stdio.h>

int main(){
    int quantidade_termos;
    int termo_atual = 0;
    int proximo_termo = 1;
    int termo_temp;

    printf("Digite a quantidade de termos que você deseja \n");
    scanf("%d", &quantidade_termos);

    for(int i = 0; i < quantidade_termos; i++){
        printf("%d\n", termo_atual);
        termo_temp = termo_atual + proximo_termo;
        termo_atual = proximo_termo;
        proximo_termo = termo_temp;

    }

}
```