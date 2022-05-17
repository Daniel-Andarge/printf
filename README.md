0x11. C - printf

Writing our own printf function, this is a project done under ALX Low Level Programming.
Resource
secrets of printf
Implementing printf and scanf in C
All About Printf

Description
The function _printf writes output to stdout. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of standard library stdarg) are converted for output.

Prototype: int _printf(const char *format, ...);


Return
Upon success, _printf returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns -1.
Format of the Argument String
The format string argument is a constant character string composed of zero or more directives: ordinary characters (apart from %) which are copied unchanged to the output stream; and conversion specifications, each of which results in fetching zero or more subsequent arguments.
Conversion specification is introduced by the character % and ends with a conversion specifier (which in whole make up the format specifier.)

	General Requirements
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line.
No more than 5 functions per file.
You are not allowed to use global variables.
The prototypes of all your functions should be included in your header file called holberton.h
All your header files should be include guarded.
Authorized functions and macros
write (man 2 write)
malloc (man 3 malloc)
free (man 3 free)
va_start (man 3 va_start)
va_end (man 3 va_end)
va_copy (man 3 va_copy)
va_arg (man 3 va_arg)

	Github
There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.
Compilation
The code can be compiled like this:
 gcc -Wall -Werror -Wextra -pedantic -std=gnu89 test/main.c *.c -o print
All test files will be in the test directory.

Authors
Daniel Andarge 
Ayenew Tilaye

