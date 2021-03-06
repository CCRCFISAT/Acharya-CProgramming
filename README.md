# Acharya-CProgramming
This repo contains contributions to project Acharya, an Open Smart Education Initiative. Submissions in the domain of C programming  are welcome.  You are contributions will be made available in the Acharya E-Learning platform.



# How to make Contributions

You can submit Jupyter notebooks that illustrates the working of python programs. Please check the topics to be covered. However, you do not have to restrict the submissions to the list of topics to be covered. Make sure to include figures and videos in your notebook.

For those who are confused as to how jupyter notebooks are possible for c and c++, please refer to jupyter-xeus/xeus-cling, which is a jupyter kernel for c/c++.

If you have miniconda installed, do the following:
```
conda create cling
conda activate cling
```

After this, you'd be with a totally new env just for C/C++ notebooks called cling. To install the required kernel, in this new env:
```
conda install xeus-cling -c conda-forge
```

Now you have a jupyter notebook kernel that can handle c/c++ code.

https://github.com/jupyter-xeus/xeus-cling



# Topics to be covered

 Program Basics
Basic structure of C program: Character set, Tokens, Identifiers in C, Variables and Data Types , Constants, Console IO Operations, printf and scanf

Operators and Expressions: Expressions and Arithmetic Operators, Relational and Logical Operators,Conditional operator, size of operator, Assignment operators and Bitwise Operators. Operators Precedence

Control Flow Statements: If Statement, Switch Statement, Unconditional Branching using goto statement, While Loop, Do While Loop, For Loop, Break and Continue statements.(Simple programs covering control flow)

 Arrays and strings
Arrays Declaration and Initialization, 1-Dimensional Array, 2-Dimensional Array String processing: In built String handling functions (strlen, strcpy, strcat and strcmp, puts, gets) Linear search program, bubble sort program, simple programs covering arrays and strings

 Working with functions
Introduction to modular programming, writing functions, formal parameters, actual parameters Pass by Value, Recursion, Arrays as Function Parameters structure, union, Storage Classes, Scope and life time of variables, simple programs using functions

Pointers and Files
Basics of Pointer: declaring pointers, accessing data though pointers, NULL pointer,array access using pointers, pass by reference effect File Operations: open, close, read, write, append Sequential access and random access to files: In built file handlingfunctions (rewind() ,fseek(), ftell(),feof(), fread(), fwrite()), simple programs covering pointers and files. 
