# Artifact 01: C/C++ Development Environment Setup

## 1. Objective
To install, configure, and test a C development environment using Visual Studio Code and the GCC compiler.

## 2. Tools Used
- Visual Studio Code (VS Code)
- MSYS2 UCRT64
- GCC Compiler
- Windows operating system

## 3. Source Code
File name: `hello.c`

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, World!\n");
    return 0;
}
```

## 4. Compilation Command
```powershell
C:\msys64\ucrt64\bin\gcc.exe -Wall -Wextra hello.c -o hello.exe
```

## 5. Execution Command
```powershell
.\hello.exe
```

## 6. Expected Output
```text
Hello, World!
```

## 7. Second Program: Addition
File name: `add.c`

The program adds two integers, 10 and 20, and displays their sum.

Compilation:
```powershell
C:\msys64\ucrt64\bin\gcc.exe -Wall -Wextra add.c -o add.exe
```

Execution:
```powershell
.\add.exe
```

Output:
```text
Sum = 30
```

## 8. Skills Learned
- Writing and saving C programs in VS Code.
- Compiling C code using GCC.
- Running executable files through the terminal.
- Understanding compiler errors and fixing them.

## 9. Learning Outcome
Successfully configured and tested the C programming environment. Both the Hello World and addition programs compiled and executed successfully.