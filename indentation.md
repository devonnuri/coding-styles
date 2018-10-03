# 인덴트 스타일

## 1TBS

인덴트 스타일은 대체적으로 One True Brace Style(1TBS)를 따른다.

다음 C코드를 참고하면 될 것 같다.

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

`4 Space`를 **선호**하며, 대체로 언어가 가지고 있는 취향에 많이 타는 편이다.

자바스크립트 프로젝트를 진행할 경우 대부분의 소스를 `2 Space`로 진행한다.
