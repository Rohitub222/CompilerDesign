# CompilerDesign
A C compiler to accept nested while-loop and if-else condition using lex and yacc

Execute this by using the following commands:-

lex tokens.l
yacc icg.y
gcc lex.yy.c y.tab.c -ll -ly -w
./a.out input.c
