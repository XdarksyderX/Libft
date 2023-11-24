# Libft

## Overview
Libft is a custom C library, part of the 42 school curriculum, which includes re-implementations of several standard C library functions along with some additional utilities. This project is an essential step for students to grasp the basics of C programming and low-level operation.

## Features
- Re-implemented standard C library functions.
- Additional string manipulation, memory allocation, and data processing functions.
- Bonus functions for linked list operations.

## Compilation and Usage
### Requirements
- GCC compiler
- GNU make

### Compiling the Library
Run the following command in the root of the project directory to compile the library:

```
make all
```

This will compile the `libft.a` library file using the `gcc` compiler with the flags `-Wall -Werror -Wextra`.

### Compiling with Bonus Functions
To compile the library with bonus functions, particularly for linked list operations, use:

```
make bonus
```

### Cleaning Up
After compilation, you can clean up the object files by running:

```
make clean
```

To remove the object files and the compiled library, use:

```
make fclean
```

### Recompiling
To recompile the library, you can use the following command:

```
make re
```

For recompiling with bonus functions:

```
make rebonus
```

## File Structure
- `ft_*.c` - Core library function files.
- `ft_*.o` - Object files generated during compilation.
- `libft.h` - Header file containing function prototypes and necessary includes.