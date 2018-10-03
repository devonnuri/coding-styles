# Indentation Style

## 1TBS

Indentation Styleは代替的にOne True Brace Style(1TBS)に沿って行く。

次のCコードを参考にすると良いようだ。

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

`4 Space`を**主に**使用しているが、言語が持った趣向にたくさん受けているのだ。

Javascriptプロジェクトを進行する場合、多くのソースを`2 Space`で進められる。
