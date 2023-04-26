## Description

A simulation of the **Unix Shell**. It uses the POSIX API to implement the  functionalities of the first Ken Thompson's Shell.

Written in C programming language, it gives the user a prompt *Hell_Shell>> *, after it accepts, it executes the command in a separate process called child process.

## Requirements:

* Operating System: Ubuntu 14.04 LTS

* Compiler: GCC 4.8.4

* This software shows a prompt and waits for the user to type a command. When the user presses the *ENTER* key, a command line always ends with a new line.
* Each time a command is run, the prompt is shown once more.
* Hell shell will terminate and return a status of 0 when the user enters the exit key.
* Hell Shell terminates and returns the inputted status when the user types exit *[status], where *status* is a value between 0 and 255. 
* The application might be stopped by pressing the keys Ctrl+D (end of file).
* The command lines are handled by the shell using arguments and paths. When the user presses Ctrl+C, the program does not end.
* When the user types *env*, the application prints the current environment.

## Getting Started

To run this shell, clone this repository in your local machine using your terminal.

git clone https://github.com/Christine-design-web/simple_shell
```

- SSH:

```
git clone git@github.com:/Christine-design-web/simple_shell.git
```

## Compiling, Debugging and Running

- All programs functions will be compiled with `gcc 4.8.4` using the flags `-Wall` `-Werror` `-Wextra` and `-pedantic`

- **Compiling ** your functions use: `

```
gcc -Wall -Wextra -Werror -pedantic -Wno-format -g *.c -o Hell_Shell
```
-  **debugging** the shell, use valgrind:
```
valgrind --leak-check=full ./Hell_Shell
```
- Or  **run** :
```
./Hell_Shell
```

### Authors:

- *Christine*  - [@Christine-design-web](https://github.com/Christine-design-web)
- *Njoroge S* - [@Samuel-Njoroge](https://github.com/Samuel-Njoroge)
