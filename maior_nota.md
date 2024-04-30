Na escola **ABC do Saber**, o aluno que obtém a maior nota é premiado ao final do ano, para isso o diretor precisa que você faça um programa de computador que peça ao diretor digitar as notas dos alunos da turma XPTO que tem apenas 4 alunos e diga qual tem a maior nota.

```c
#include <stdio.h>

int main(){
    int nota1, nota2, nota3, nota4;
    int maior_nota;
    printf("Digite a primeira nota: ");
    scanf("%d", &nota1);
    printf("Digite a segunda nota: ");
    scanf("%d", &nota2);
    printf("Digite a terceira nota: ");
    scanf("%d", &nota3);
    printf("Digite a quarta nota: ");
    scanf("%d", &nota4);

    if (nota1 > nota2){
        maior_nota = nota1;
    } else {
        maior_nota = nota2;
    }
    if (nota3 > maior_nota){
        maior_nota = nota3;
    } 
    if (nota4 > maior_nota){
        maior_nota = nota4;
    }
    printf("A maior nota é: %d\n", maior_nota);

}
``` 
