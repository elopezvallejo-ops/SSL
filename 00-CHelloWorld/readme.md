TP O: HOLA MUNDO
----------------

EL COMPILADOR ELEGIDO

El compilador que utilizo en mi sistema Ubuntu es el GCC 14 (GNU Compiler Collection).
Se eligió esta versión debido a que es una versión moderna del compilador, con buen soporte para el estándar C23.
ademas permite compilar programas utilizando el estándar C23 mediante la opción -std=c23.

LA VERSION DEL COMPILADOR

```
$gcc-14 --version
gcc-14 (Ubuntu 14.2.0-4ubuntu2~24.04.1) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

```
LA VERSION C QUE EL COMPILADOR COMPILA

usando la terminal ejecute y compile con el estandar C23

```
gcc-14 hello.c -std=c23 -o hello
./hello > output.txt
```
use la opción -std=c23. Otra forma es utilizando el nombre
predefinido __STDC_VERSION__.




