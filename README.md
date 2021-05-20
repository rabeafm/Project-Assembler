# Project-Assembler
This project aims to imitates one of every computer most common programs, which is an Assembler. This project was built as a final project for the academic course #20465 - Laboratory in Systems Programming in the open university. The Assembler (written in ANSI C90) is made for a special assembly language defined for the project. The assembler's role is to create a file of machine language from a file written in the assembly language as the first step in a program cycle towards getting the code to run on a computer. The next stages which are the linkage and loading are not part of this program.

# The project includes the following files:

1- Source files of the program (.c & .h):
 
    a.	assemble.c	- Main File
  
    b.	assemble.h	- Main Functions Declaration
  
    c.	binary.c	- Binary Translation Functions
     
    d.	data.h		- Data Structures
   
    e.	files.c		- File Handling Functions
    
    f.	passes.c	- First Pass & Second Pass Functions
    
    g.	symtab.h	- Symbol Table Structure & Declaration
    
    h.	symtab.h	- Symbol Table Functions
    
    i.	utils.h		- Utilities Macros & Declarations
    
    j.	utils.c		- Utilities Functions
    
    k.	values.h	- Assembly Language Binary Values
    
2- Runtime file for Ubuntu (Compiled and linked).
 
3- Makefile (Compiled with gcc with the flags -Wall -ansi -pedantic, with no messages or warning from the compiler).
 
4- Runtime Examples:
 
    a.	Input in Assembly, Output as a result of the using the assembler on the input files, showing use of different orders and data structures.
      
    b. 	Input in Assembly Displaying various error types (with no output files) and screenshots showing the errors.
