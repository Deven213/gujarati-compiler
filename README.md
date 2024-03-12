# Gujarati Compiler

To compile the program, follow the following commands:

```
flex lex_file.l
yacc -d yacc_file.y
gcc lex.yy.c y.tab.c -lm
```

and to run the program

```
./a.out
```

## Happy Hacking!