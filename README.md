# Custom Printf Implementation
* This repository contains a custom implementation of the printf function in C. It offers additional features and handles specific conversion specifiers beyond the standard functionality.
* This is a collaboration between BlackOligarch (myself) & @Ballerken

## Features
* Standard Conversion Specifiers: Supports common specifiers such as %s, %c, %%, %i, %d, %b, %u, %o, %x, %X, & %S
* Additional Conversions: Includes custom conversions like %p and %r.
* Length Modifiers: Supports l and h modifiers for conversions like %d, %i, %u, %o, %x, %X.
* Error Handling: Provides basic error handling and warnings for better code robustness.

## Getting Started
### Prerequisites
* Ensure that gcc (GNU Compiler Collection) is installed on your system before using this custom printf implementation.
* An alternative can also be the Clang compiler

## Usage
* Include Header File: Add "main.h" to your C program.
* Call _printf: Use the "_printf" function in your code, passing the desired format string and arguments.

## Compilation
* Copy and paste the following command into your terminal:

##### Using GCC

*       gcc -Wall -Wextra -Werror -pedantic -std=gnu89 *.c -o printf


##### Using Clang

*       clang -Wall -Werror -Wextra -pedantic -std=gnu89 *.c


## Running
* Execute the compiled program using:

        ./printf


## Conclusion
* This README provides clear instructions on how to use and compile your printf project. Feel free to contribute or modify the code to suit your specific requirements.
