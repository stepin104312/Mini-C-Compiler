build: output
output: y.tab.c
	gcc -o output y.tab.c -ll 
    
y.tab.c: lex.yy.c
	yacc c.y

lex.yy.c: c.l
	lex c.l

clean:
	rm lex.yy.c c *.o	       
