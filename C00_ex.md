Examples:

1. `putchar`:

```c
#include <stdio.h>

void printCharacter(char c) {
    putchar(c);
}

int main() {
    printCharacter('A');
    return 0;
}
```
Output:
```
A
```

2. `print_alphabet`:

```c
#include <stdio.h>

void printAlphabet() {
    char c;
    for (c = 'a'; c <= 'z'; c++) {
        putchar(c);
    }
}

int main() {
    printAlphabet();
    return 0;
}
```
Output:
```
abcdefghijklmnopqrstuvwxyz
```

3. `print_reverse_alphabet`:

```c
#include <stdio.h>

void printReverseAlphabet() {
    char c;
    for (c = 'z'; c >= 'a'; c--) {
        putchar(c);
    }
}

int main() {
    printReverseAlphabet();
    return 0;
}
```
Output:
```
zyxwvutsrqponmlkjihgfedcba
```

4. `print_numbers`:

```c
#include <stdio.h>

void printNumbers() {
    int i;
    for (i = 0; i <= 9; i++) {
        putchar('0' + i);
    }
}

int main() {
    printNumbers();
    return 0;
}
```
Output:
```
0123456789
```

5. `is_negative`:

```c
#include <stdio.h>
#include <stdbool.h>

bool isNegative(int num) {
    if (num < 0) {
        return true;
    } else {
        return false;
    }
}

int main() {
    int number = -5;
    if (isNegative(number)) {
        printf("The number is negative.\n");
    } else {
        printf("The number is not negative.\n");
    }
    return 0;
}
```
Output:
```
The number is negative.
```

6. `print_comb`:

```c
#include <stdio.h>

void printComb() {
    int i, j;
    for (i = 0; i <= 9; i++) {
        for (j = 0; j <= 9; j++) {
            printf("%d%d ", i, j);
        }
    }
}

int main() {
    printComb();
    return 0;
}
```
Output:
```
00 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 ... 99
```

7. `print_comb2`:

```c
#include <stdio.h>

void printComb2() {
    int i, j;
    for (i = 0; i <= 9; i++) {
        for (j = i + 1; j <= 9; j++) {
            printf("%d%d ", i, j);
        }
    }
}

int main() {
    printComb2();
    return 0;
}
```
Output:
```
01 02 03 04 05 06 07 08 09 12 13 14 15 16 17 18 19 23 24 25 26 ... 89
```

8. `putnbr`:

```c
#include <stdio.h>

void putNumber(int num) {
    printf("%d", num);
}

int main() {
    putNumber(12345);
    return 0;
}
```
Output:
```
12345
```

9. `print_combn`:

```c
#include
