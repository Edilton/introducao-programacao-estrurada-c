Crie um programa que pede ao usuário para inserir um caractere e verificar se é uma vogal, uma consoante ou outro tipo de caractere.


```c

#include <stdio.h>

int main() {
    char caractere;

    // Solicita ao usuário para inserir um caractere
    printf("Digite um caractere: ");
    scanf(" %c", &caractere);

    switch (caractere) {
        case 'a':
        case 'e':
        case 'i':
        case 'o':
        case 'u':
            printf("'%c' e uma vogal.\n", caractere);
            break;
        default:
            printf("'%c' e uma consoante.\n", caractere);
            break;
    }
    

    return 0;
}
```