# 0x11. C - printf #

## Description ##
This team project was done by Oluchime Promise and Beatrice Barbara Stanley, both students of ALX Software Engineering School.
This is a part of the curriculum of the ALX-Holberton School and is a required project. The project entails the creation of a function called printf and this function replicates and works exactly like the C standard library printf() function

## Prototype ##

`int _printf(const char *format, ...);`

## Usage, Implementation and Examples ##
* All files created were created and compiled on Ubuntu 20.04

* Code was compiled with `gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c` ..*       

- The "main.h" file containing the functions using the _printf() funtion are included   

* The syntax for calling is `_printf("format string", arguments...);` _where `format string` can contain conversion specfiers and flags, alongside regular characters.

### Examples ###* `_printf("Hello World\n");` prints "Hello World", followed by a new line.

* `_printf("This number is %d", 40);` prints "This number is 40."

* `_printf("My name is %s\n", John);` prints "My name is John, followed by a new line." 


# Tasks #
These are the completed tasks for this project and the problems the function aims to solve

## [0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life] ##

* Write a function that produces output according to a format.

1. Returns: the number of characters printed (excluding the null byte used to end output to strings)
2. `c` : converts input into a character
3. `s` : converts input into a string



## 1. Education is when you read the fine print. Experience is what you get if you don't ##* Handle the following conversion specifiers
1. `d` : converts input into a base 10 integer
2. `i` : converts input into an integer



## 2. Just because it's in print doesn't mean it's the gospel ##
* Create a man page for the function



## 3. With a face like mine, I do better in print ##
* Handle specific custom conversion specifiers
1. `b`: converts unsigned int to binary



## 4. What one has not experienced, one will never understand in print ##
* Handle the following conversion specifiers:
1. `u`: converts input to unsigned integer
2. `o`: converts the input into an octal number
3. `x`: converts input into hexadecimal number
4. `X`: converts the input into a hexadecimal number with capital letters



## 5. Nothing in fine print is ever good news ##
* Use a local buffer of 1024 chars in order to call `write` as little as possible.       



## 6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print ##* Handles the following conversion specifier:
1. `p`: int input is converted to a pointer address



## 7. My weakness is wearing too much leopard print ##
* `s` : prints the string
* Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)



## 8. The big print gives and the small print takes away ##* Handle the following flag characters for non-custom conversion specifiers:
1. `+` : adds a + in front of signed positive numbers and a - in front of signed negative numbers2. space : same as +, but adds a space (is overwritten by +)
3. `#` : adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0x for x or X conversions



## 9. Sarcasm is lost in print ##
* Handle the following length modifiers for non-custom conversion specifiers:
1. l : converts `d`, `i`, `u`, `o`, `x`, `X` conversions in short signed or unsigned ints2. h : converts `d`, `i`, `u`, `o`, `x`, `X` conversions in long signed or unsigned ints 



## 10. Print some money and give it to us for the rain forests ##
* Handle the field width for non-custom conversion specifiers.



## 11. The negative is the equivalent of the composer's score, and the print the performance ##
* Handle the precision for non-custom conversion specifiers.



## 12. It's depressing when you're still around and your albums are out of print ##      
* Handle the `0` flag character for non-custom conversion specifiers.



## 13. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection ##
* Handle the `-` flag character for non-custom conversion specifiers.



## 14. Print is the sharpest and the strongest weapon of our party ##
* Handle the following custom conversion specifier:
1. `r`: prints the reversed string



## 15. The flood of print has turned reading into a process of gulping rather than savoring ##
* Handle the following custom conversion specifier:
1. 'R': prints the rot13'ed string



## 16. * ##
* All the above options work together



# AUTHORS #
* ## [Oluchime Promise](https://github.com/chimeszn) ##
* ## [Barbara Stanley](https://github.com/BarbaraStanley) ##
