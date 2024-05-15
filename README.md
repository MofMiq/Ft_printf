# Ft_printf
> This repository contains a "Ft_printf" project that is part of the École 42 curriculum.

This project consists of coding a library that contains a simplified version of the real printf function. It's an extremely useful function that does a series of base conversions (decimal and hexadecimal) and makes the output much easier - especially when compared to its predecessor in 42 - the system call write. The function can be used in future projects.

One of the key to make this project are variadic arguments, which is possible to achieve by using the header <stdarg.h> and parameters like va_arg for the list arguments in order of occurrence, or va_start and va_end to start and end the use of the argument list.

We must be able to do those conversions:
• **%c** print a single character. \

• **%s** print a string of characters. \

• **%p** The void * pointer argument is printed in hexadecimal. \

• **%d** print a decimal (base 10) number. \

• **%i** print an integer in base 10. \

• **%u** print an unsigned decimal (base 10) number. \

• **%x** print a number in hexadecimal (base 16). \

• **%%** print a percent sign. \
