0: script that runs a C file through the preprocessor and save the result into another file: gcc $CFILE -E -o c
1: cript that compiles a C file but does not link: gcc -c $CFILE
2: script that generates the assembly code of a C code and save it in an output file: gcc -S $CFILE
3: script that compiles a C file and creates an executable named cisfun: gcc $CFILE -o cisfun
