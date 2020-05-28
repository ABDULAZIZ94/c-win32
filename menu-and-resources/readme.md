# try using -wall in compiler
windres menu.rc -o menu.o
gcc -c window.c
gcc -o window.exe window.o menu.res