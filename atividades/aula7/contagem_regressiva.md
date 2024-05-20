Faça uma contagem regressiva de 10 a 1.

```c
#include <stdio.h>
#include <unistd.h> // Para sistemas Unix-like (Linux, macOS)

int main() {
    int i;

    for (i = 10; i >= 1; i--) {
        printf("%d\n", i);
        sleep(1); //Pausa 1s
    }

    printf("FIM!\n");

    return 0;
}
```