# Compiler-for-CUCU

How to run file-

% bison -d cucu.y
% flex cucu.l
% g++ cucu.tab.c lex.yy.c -lfl -o cucu
                                                                                                       

cucu.l

•	First I made the cucu.l file, it prints the token type along with its value in the output file, here output file is lexer.txt this file contains the output.
•	This output contains the token type of the program 
•	For compiling this file you have to give command – flex cucu.l
•	After that I make yacc file 

cucu.y


•	After that I made cucu.y file which generates the parser.txt file 
•	After adding the function calls at the right place, all we need to do is the print all the tokens in the main function of the yacc file.
•	
