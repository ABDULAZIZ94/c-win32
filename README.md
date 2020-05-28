# this repo about win32 programming

# sources
http://www.winprog.org/tutorial/start.html
https://www.transmissionzero.co.uk/computing/win32-apps-with-mingw/


# other platform (linux osx)
https://tronche.com/gui/x/xlib/

# other alternatives
MFC
win32++

# compiling

    https://gcc.gnu.org/onlinedocs/gcc-4.9.4/gnat_ugn_unw/Compiling-Resources.html

    windres -i myres.rc -o myres.o


    windres foo.rc foores.o

    gcc -o foo.exe foo.o foores.o


    gnatmake myprog -largs myres.o

# working compilation

    windres menu_one.rc -o menu_one_res.o //produce menu_one_res.o
    gcc -c menu_one.c //produce menu_one.o
    gcc menu_one.o menu_one_res.o -o menu_one.exe
