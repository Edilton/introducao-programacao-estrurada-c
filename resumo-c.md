
# Sintaxe básica de C

## Comentários

```c
// Este é um comentário de linha, tudo que está comentado não é exetutado pelo programa

/*
Este é um comentário de bloco
que pode se estender por várias linhas
*/
```

## Inclusão de Bibliotecas

```c
#include <stdio.h> // Biblioteca de entrada e saída padrão
#include <stdlib.h> // Biblioteca padrão do sistema
```

## Função Principal

```c
int main() {
    // Código da função principal
    return 0;
}
```

## Tipos de Dados

```c
int inteiro;
float flutuante;
char caractere;
```

## Declaração de Variáveis

```c
int idade;
float altura;
char letra;
```

## Operadores Aritméticos

```c
+, -, *, /, %
```

## Estruturas de Controle

### Condicional

```c
if (condição) {
    // código
} else if (outra_condição) {
    // outro código
} else {
    // código alternativo
}
```

---

## Entrada e Saída de Dados

### Saída (printf)

```c
int inteiro = 10;
float flutuante = 3.14;
char caractere = 'a';

printf("Inteiro: %d\n", inteiro);
printf("Flutuante: %f\n", flutuante);
printf("Caractere: %c\n", caractere);
```

### Entrada (scanf)

```c
int inteiro;
float flutuante;
char caractere;

printf("Digite um inteiro: ");
scanf("%d", &inteiro);

printf("Digite um flutuante: ");
scanf("%f", &flutuante);

printf("Digite um caractere: ");
scanf(" %c", &caractere); // Note o espaço antes de %c para consumir o caractere de nova linha

printf("Inteiro: %d\n", inteiro);
printf("Flutuante: %f\n", flutuante);
printf("Caractere: %c\n", caractere);
```

---


## Operadores Lógicos

```c
int a = 5, b = 3;

// AND lógico
if (a > 0 && b > 0) {
    printf("Ambos a e b são maiores que zero\n");
}

// OR lógico
if (a == 5 || b == 5) {
    printf("Pelo menos um dos valores é igual a cinco\n");
}

// NOT lógico
if (!(a == 0)) {
    printf("O valor de a não é zero\n");
}
```

Os operadores lógicos em C são `&&` (AND), `||` (OR) e `!` (NOT). Eles são usados para combinar condições em instruções condicionais.

