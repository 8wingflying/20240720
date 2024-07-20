# GITHUB: markdown

## C
```c
#include <stdio.h>

int main() {
    // 迴圈控制行數
    for(int i = 1; i <= 9; i++) {
        // 迴圈控制列數
        for(int j = 1; j <= 9; j++) {
            // 打印乘法結果，並保持對齊
            printf("%d*%d=%2d ", i, j, i * j);
        }
        // 每列打印完後換行
        printf("\n");
    }
    return 0;
}


```
