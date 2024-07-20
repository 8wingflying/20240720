# GITHUB: markdown

- 請幫我完成9*9乘法表的X程式設計

## C: 請幫我完成9*9乘法表的X程式設計
- [ONLINE C](https://www.programiz.com/c-programming/online-compiler/)
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
## C++: 請幫我完成9*9乘法表的C++程式設計
- [ONLINE C++](https://www.programiz.com/cpp-programming/online-compiler/)
```c++
#include <iostream>
using namespace std;

int main() {
    // 迴圈控制行數
    for(int i = 1; i <= 9; i++) {
        // 迴圈控制列數
        for(int j = 1; j <= 9; j++) {
            // 打印乘法結果，並保持對齊
            cout << i << "*" << j << "=" << i * j << "\t";
        }
        // 每列打印完後換行
        cout << endl;
    }
    return 0;
}

```
