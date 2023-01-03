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

## Tar archive

`tar` needs no special options.

```
$ tar -cf "Hello World archive" "Hello World" "Hello World source code"

$ tar -xvf "Hello World archive"
x Hello World
x Hello World source code
```
