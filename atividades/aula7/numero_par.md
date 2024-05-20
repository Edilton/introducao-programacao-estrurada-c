Edite o programa anterior para que imprima apenas os números pares de 1 até 1700.
 Ex: Número 2, Número 4 e assim por diante.


 ```c
#include <stdio.h>

int main() {
    int i;
    for (i = 1; i <= 1700; i++) {
        if (i % 2 == 0) {
            printf("%d\n", i);
        }
    }
    return 0;
}


 ```