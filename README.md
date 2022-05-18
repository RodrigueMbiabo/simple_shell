# SIMPLE_SHELL

## Description
This project is a simple version of the linux shell made for Holberton School. This simple_shell is a command line interpreter, created using the C programming Language and it can do many functionalities that a real shell does.

## Requirements

Simple_shell is designed to run in the Ubuntu 14.04 and to be compiled using the GNU compiler collection v. gcc 4.8.4.

## Structure


## File Usage

Files|Description|Functions
--|--|--
[aux_compare.c] | function that compares strings | -int _strncmp -int _strcmp
[aux_concatenate.c] |function that concatenates | -char *_strcat(char *dest, char *src)
[aux_copy.c] | function that copy string | char *_strcpy(char *dest, char *src)
[aux_counts.c] | function that count string | int _strlen(char *a)
[aux_e.c] | function that prints error | void _error(char *CMD)
[built-in.c] | function that checks if the env exit command exists | int built_in(char **Arg_str, int ct_output, char *row)
[check_built-in.c] | function that checks if the bultins | int Run(char **Arg_str, int ct_output, char *row)
[check_built-in.c] | function that checks if the bultins | int Run(char **Arg_str, int ct_output, char *row)
[check_line.c] | function that checks line | char *rd_row(void)
[get_path.c] | function that checks if the command exists | char *get_env(void)
[is_path.c] | function that checks if the path | int comp_Arg(char **Arg_str, int ct_output)
[main.h] | function library | 
[pid.c] | function that check fork | int _fork(char **Arg_str, int ct_output)
[shell.c] | function that front-end | int main(void)
[tokenizer.c] | tokenization function | char **tokenizer(char *BUFF)


## Installation

* Clone this repository: git clone "https://github.com/dmac24/simple_shell"
* Change directories into the repository: cd simple_shell
* Compile: gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
* Run the shell in interactive mode or non-interactive mode.
* ./hsh

## Manual 

### To enter the manual 
```
man -l man_1_simple_shell
```

## Authors
```
* MBIAHA RODRIGUE [@rodriguembiabo](https://github.com/rodriguembiabo)
```
