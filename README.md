Printf Team Project

Project Details:

0. Function will produces output according to a format.
   	Prototype: int _printf(const char *format, ...);
   	Returns: the number of characters printed (excluding the null byte used to end output to strings)
	write output to stdout, the standard output stream
	format is a character string.You need to handle the following conversion specifiers:
	c
	s
	%
1. Function will handle the following conversion specifiers:

	d
	i

2. Function will  the following custom conversion specifiers:

	b: the unsigned int argument is converted to binary

3. Function will handle the following conversion specifiers:
	u
	o
	x
	X

4. Function will Use a local buffer of 1024 chars in order to call write as little as possible.

5. Function will Handle the following custom conversion specifier:

	S : prints the string.
	Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

6. Function will Handle the following conversion specifier: p

7. Function will Handle the following flag characters for non-custom conversion specifiers:

	+
	space
	#

8. Function will handle the following length modifiers for non-custom conversion specifiers:

	l
	h
	Conversion specifiers to handle: d, i, u, o, x, X

9. Function handle  the field width for non-custom conversion specifiers.

10. Fuction will handle  the precision for non-custom conversion specifiers.

11. Function will handle  the 0 flag character for non-custom conversion specifiers.

12. Function will handle the - flag character for non-custom conversion specifiers.

13. Function will handle the following custom conversion specifier:

	r : prints the reversed string

14. Function will handle the following custom conversion specifier:

	R: prints the rot13'ed string.

15. All function will work together.
