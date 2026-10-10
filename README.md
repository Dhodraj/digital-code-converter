# digital-code-converter

A menu-driven C program for the number-code conversions used in digital electronics: binary, decimal, hexadecimal, octal and Gray code.

Built in July 2021.

## What it converts

| From | To |
|---|---|
| Binary | decimal, Gray, hexadecimal, octal |
| Decimal | binary, Gray, hexadecimal, octal |
| Hexadecimal | binary, Gray, decimal, octal |

## Run it

```bash
gcc codeconver.c -o codeconver -lm
./codeconver
```

It includes `conio.h` and calls `getch()` to pause between screens, so it builds as is with Windows compilers such as MinGW. On Linux or macOS, remove the include and those calls first. `codeconver.exe` is a prebuilt Windows binary.
