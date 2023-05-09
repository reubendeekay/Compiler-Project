# GROUP 6 COMPILER CONSTRUCTION PROJECT

## Team Members

- Reuben Jefwa Balozi
- Halima Ali Wario
- Sameera Bashir Kherdin
- Sydney Nzunguli Kathina

## Project Description

The project is a compiler for a subset of the Go programming language. The compiler is written in Python and it generates assembly code for the RISC-V architecture.
The compiler is able to compile the following features of the Go programming language:

- Variable declarations
- Variable assignments
- Arithmetic expressions
- Boolean expressions
- If statements
- For loops
- Functions
- Function calls
- Function parameters
- Function return values

## Tools Used

- Python 3.8.5
- PLY (Python Lex-Yacc) 3.11
- RISC-V GNU Compiler Toolchain

## Project Structure

The compiler is divided into three main parts:

- the lexer
- the parser
- the code generator.

* The lexer is responsible for tokenizing the input source code.
* The parser is responsible for parsing the tokens and generating an abstract syntax tree.
* The code generator is responsible for generating assembly code from the abstract syntax tree.

## How to run the compiler

1. To run the lexer run the following command:

```
./run_lexer.sh

```

2. To run the parser run the following command:

```
./run_parser.sh

```

3. To run the code generator run the following command:

```
./run_ir.sh

```

4. To run the whole project run the following command:

````
./run_all.sh

    ```



````
