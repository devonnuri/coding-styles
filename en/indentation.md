# Indentation Style
## 1TBS

I mostly follow `One True Brace Style(1TBS)`.

Here is an example code about my indentation style.

```c
#include <stdio.h>

void sayHello(char* name) {
    printf("Hello! %s", name);
}

int main() {
    char*[] names = ['James', 'John', 'Mary', 'Patrica', 'Robert', 'Jeniffer']
    for (int i = 0; i < 10; i++) {
        if (i % 2 == 0) {
            sayHello(names[i]);
        }
    }
}
```

## Tab or Space

I prefer to use `4 Space`, but I mostly follow to preferences that each language has.

And, when I write an javascript project, I use `2 Space` in most code.
