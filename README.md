# printf

The pair progrmming project is completed as part of the low-level programming and algorithm curriculum at ALX. _printf() is a formatted output conversion C program. It produces a formatted string to the standard output (the display).

The program is a replica of the C standard library function, ==printf()==

# Technologies 
-----
- C files are compiled using gcc 9.4.0 with with the flags (-Wall -Werror -Wextra -pedantic -std=gnu89).

- C files are written according to the C90 standard

- Tested on Ubuntu 20.04 LTS

# conspectus 
-----

'''
prototype

int _printf(const char *format, ...)
'''

Where format is the first argument which is referred to as the message string and is always the first argument of printf(). It can contain special control characters and/or parameter conversion control characters.

'''
format tags prototype

%[flags][width][.precision][length]specifier

'''

# Description

The _printf prototype is defined in the <main.h> header file. When you use the _printf() function, it prints the string pointed out by the format to the standard output stdout. The format can also contain some specifiers that start with a % which are replaced by values of variables(accessed via the variable-length argument facilities of stdarg) for output.

To put it simply, they work as additional arguments to the ==_printf()== function.

> **Return value**
The function returns:
- The number of characters written if successful(excluding the terminating null byte used to end output to strings)
- A negative value, if failed

# Authors
-----
 - @Ezeh Chidera Jessica
 - @Ivan Agwuye





