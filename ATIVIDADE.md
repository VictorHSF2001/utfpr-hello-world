# Atividade do minicurso de GitHub - UTFPR <h1>

## Utilizando h2 como exemplo de linguagem Markdown. <h2>

  * Comprar um Hot Dog;
  * Ligar o PC;
  * Assistir Série.
  
Exemplo de código em C:

```C
#include <stdio.h>
#include <stdlib.h>

int main() {
    int x[10], i = 0;

    for(i=0;i<10;i++) {
        scanf("%d", &x[i]);
        if (x[i] <= 0) {
            x[i] = 1;
        }

    }
    for(i=0;i<10;i++){
        printf("X[%d] = %d\n", i, x[i]);
    }
    return 0;
}
```
