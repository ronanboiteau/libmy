# libmy

{EPITECH.} first year project.

Recoding libc functions into a C static library.

## Requirements

 - [Make](https://www.gnu.org/software/make/)
 - [GCC](https://gcc.gnu.org/)

## Get started

### Compile the library

Navigate to the root of the repository from your Terminal and run `make` to build the `libmy.a` static library.

### Use libmy

 - Copy this repository inside a folder in your project directory.
 - Include the `my.h` header file in your `.c` files where you want to use libmy:
```c_cpp
#include "my.h"
```
 - If you put this repository in a folder named `lib/`, run this command to compile a `main.c` file using the library:
```
gcc main.c -L lib/ -l my -I lib/include/
```
## Author

* **Ronan Boiteau** ([GitHub](https://github.com/ronanboiteau) / [LinkedIn](https://www.linkedin.com/in/ronanboiteau/))
