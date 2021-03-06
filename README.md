# Compiler
This is the final course project for Compiler course. We development a compiler based on BNF Grammar(https://github.com/Yuhao-Lan/Compiler/blob/master/Extended_BNF_Grammar_for_C_Minus.pdf).

# Process

We can check a program for syntax correctness by yacc and lex. With an Abstract Syntax Tree (AST), we can store the structure of the input program in a data structure (called an Intermediate Representation - IR), which allows us to perform multiple passes on the source information to improve the performance of the code. **A final pass over the AST allows us to generate target (assembly language). Our ultimate goal is to generate MIPS code and run that code on a MIPS simulator called SPIM.**

# Requirement

Please read all 10 lab requirements step by step(https://github.com/Yuhao-Lan/Compiler/tree/master/Labs).

# Test results

https://github.com/Yuhao-Lan/Compiler/blob/master/Lab%209%20Generating%20MIPS%20CODE.pdf

**Realize the READ and WRITE to a VARIABLE or a NUMBER functionality**

![alt text](https://github.com/Yuhao-Lan/Compiler/blob/master/Results/Lab%209%20Generating%20MIPS%20CODE-page-005.jpg)

**Realize the IF STATEMENT**

![alt text](https://github.com/Yuhao-Lan/Compiler/blob/master/Results/Lab%209%20Generating%20MIPS%20CODE-page-001.jpg)

![alt text](https://github.com/Yuhao-Lan/Compiler/blob/master/Results/Lab%209%20Generating%20MIPS%20CODE-page-002.jpg)

**Realize the WHILE LOOP STATEMENT**

![alt text](https://github.com/Yuhao-Lan/Compiler/blob/master/Results/Lab%209%20Generating%20MIPS%20CODE-page-003.jpg)

![alt text](https://github.com/Yuhao-Lan/Compiler/blob/master/Results/Lab%209%20Generating%20MIPS%20CODE-page-004.jpg)


