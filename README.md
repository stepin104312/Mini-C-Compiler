# Mini-C-Compiler
A mini C++ compiler which detects errors like invalid variable name, invalid loops, invalid basic arithmetic expressions

Compilation Steps :
	
  $ lex c.l
	
  $ yacc c.y
	
  $ gcc y.tab.c -ll -ly 
	
  $ output [filename]
