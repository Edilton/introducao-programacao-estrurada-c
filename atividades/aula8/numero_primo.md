
Número Primo: Escreva um programa em C que verifica se um número é primo. Um número primo é aquele que é divisível apenas por 1 e por ele mesmo. O programa deve solicitar ao usuário um número e informar se ele é primo ou não.


```c
#include <stdio.h>

int main(){
    int numero;

    printf("Digite um número para saber se ele faz parte do conjunto dos números primos\n");
    scanf("%d", &numero);

    if (numero <= 1){
        printf("O número %d não eh primo!", numero);
    }
    for(int i= 2; i < numero; i++ ){
        if(numero % i == 0){
            printf("O número %d não eh primo!", numero);
            return 0;
        }
    }
    printf("O número %d eh primo!", numero);
    return 0;
}
```