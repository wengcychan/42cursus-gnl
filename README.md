<h1 align="center">42cursus - Get Next Line</h1>

<p align="center">
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/wengcychan/42cursus-gnl?style=plastic&color=blue&label=C%20language&logo=42"/>
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/wengcychan/42cursus-gnl?style=plastic&color=green&logo=42"/>
</p>

Get Next Line is a project designed to introduce the concept of static variables.

For more projects related to 42cursus, please visit the [hive-42cursus](https://github.com/wengcychan/hive-42cursus.git) repository.

## Introduction

The goal of this project is to implement a function that reads a line from a file descriptor and returns it.

## Usage

To compile and use the Get Next Line program, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/wengcychan/42cursus-gnl.git
	```

2. In your C projects, include the header file `get_next_line.h`:

   ```c
   #include "get_next_line.h"
   ```

3. Implement your own `main.c` file where you can call the `get_next_line` function using the following prototype:

   ```c
   char *get_next_line(int fd);
   ```

4. Compile the program with `cc`:

   ```bash
	cc -o get_next_line main.c get_next_line.c get_next_line_utils.c
	```

5. Run the program:

	```bash
	./get_next_line
	```
