# 0x08. C - Recursion

## Resources

**Read or watch:**

* [0x08. Recursion, introduction](https://alx-intranet.hbtn.io/rltoken/dzZB83Hm3lO7dScjhebAxw)
* [What on Earth is Recursion?](https://alx-intranet.hbtn.io/rltoken/xYjKl3024oN58Bi_621_vQ)
* [C - Recursion](https://alx-intranet.hbtn.io/rltoken/u4ojc5CZpf4qiuQvmXCiOA)
* [C Programming Tutorial 85, Recursion pt.1](https://alx-intranet.hbtn.io/rltoken/Wv-wffgpXelN9ZTrbmiOyA)
* [C Programming Tutorial 86, Recursion pt.2](https://alx-intranet.hbtn.io/rltoken/7GVdI-KT-M1vOIzwEjSahQ)

## Learning Objectives

* At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General

* What is recursion
* How to implement recursion
* In what situations you should implement recursion
* In what situations you shouldn’t implement recursion

### Copyright - Plagiarism

* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General

* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
* All your files should end with a new line
* A README.md file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
* You are not allowed to use global variables
* No more than 5 functions per file
* You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
* You are allowed to use _putchar
* You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
* In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
* The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
* Don’t forget to push your header file
* You are not allowed to use any kind of loops
* You are not allowed to use static variables

## Tasks

### 0. She locked away a secret, deep inside herself, something she once knew to be true... but chose to forget

Write a function that prints a string, followed by a new line.

* Prototype: void _puts_recursion(char *s);

FYI: The standard library provides a similar function: puts. Run man puts to learn more.

	julien@ubuntu:~/0x08. Recursion$ cat 0-main.c
	#include "main.h"
	
	/**
	 * main - check the code
	 *
	 * Return: Always 0.
	 */
	int main(void)
	{
	    _puts_recursion("Puts with recursion");
	    return (0);
	}
	julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 0-main.c 0-puts_recursion.c -o 0-puts_recursion
	julien@ubuntu:~/0x08. Recursion$ ./0-puts_recursion 
	Puts with recursion
	julien@ubuntu:~/0x08. Recursion$ 

Repo:

* GitHub repository: [alx-low_level_programming](https://github.com/MubarekSD/alx-low_level_programming)
* Directory: [0x08-recursion](https://github.com/MubarekSD/alx-low_level_programming/tree/main/0x08-recursion)
* File: [0-puts_recursion.c](https://github.com/MubarekSD/alx-low_level_programming/blob/main/0x08-recursion/0-puts_recursion.c)
