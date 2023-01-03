# Extensionless

## C programming language

```
$ cat > "Hello World source code"
#include <stdio.h>
int main(void) {
  printf("Hello World\n");
  return 0;
}

$ gcc -o "Hello World" -x c "Hello World source code"

$ ./"Hello World"
Hello World
```
