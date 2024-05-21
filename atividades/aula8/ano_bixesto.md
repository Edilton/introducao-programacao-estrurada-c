
Faça um programa que verifique se um ano inserido pelo usuário é bissexto:

    1. Um ano é bissexto se atender a uma das seguintes condições:

    1. O ano é divisível por 4, mas não é divisível por 100.

    2. O ano é divisível por 400.



```c
#include <stdio.h>

int main(){
    int ano;
    int eh_divisivel_por_4;
    int eh_divisivel_por_100;
    int eh_divisivel_por_400;

    printf("Digite o ano: ");
    scanf("%d", &ano);

    eh_divisivel_por_4 = ano % 4 == 0;
    eh_divisivel_por_100 = ano % 100 == 0;
    eh_divisivel_por_400 = ano % 400 == 0;

    if(eh_divisivel_por_4 && !eh_divisivel_por_100){
        printf("%d eh bixesto",ano);
    } else if(eh_divisivel_por_400){
        printf("%d eh bixesto",ano);
    }
    else {
       printf("%d Não eh bixesto", ano);
    }

    return 0;
}
```