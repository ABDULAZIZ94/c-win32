# this repo about win32 programming

# sources

http://www.winprog.org/tutorial/start.html

https://www.transmissionzero.co.uk/computing/win32-apps-with-mingw/

http://www.alsprogrammingresource.com/win32_links.html

https://winapi.programmingpedia.net/

http://zetcode.com/gui/winapi/main/

http://www.smorgasbordet.com/pellesc/

#MSDN

https://docs.microsoft.com/en-us/windows/win32/learnwin32/your-first-windows-program


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

# rc file predefined symbol
[predefined symbol](https://docs.microsoft.com/en-us/cpp/windows/win32-predefined-symbols?view=vs-2019)
[rev ver](https://docs.microsoft.com/en-us/previous-versions/cc194804(v=msdn.10)?redirectedfrom=MSDN)

main links
    
    https://docs.microsoft.com/en-us/windows/win32/menurc/about-resource-files?redirectedfrom=MSDN


statements
    
    https://docs.microsoft.com/en-us/windows/win32/menurc/resource-definition-statements

preprocessors

    https://docs.microsoft.com/en-us/windows/win32/menurc/preprocessor-directives

preprocessor operator

    https://docs.microsoft.com/en-us/windows/win32/menurc/preprocessor-operators

comments

    https://docs.microsoft.com/en-us/windows/win32/menurc/comments

predefined macros

    https://docs.microsoft.com/en-us/windows/win32/menurc/predefined-macros


pragma directives

    https://docs.microsoft.com/en-us/windows/win32/menurc/pragma-directives

# style

window

    https://docs.microsoft.com/en-us/windows/win32/winmsg/window-styles

dialog boxes

    https://docs.microsoft.com/en-us/windows/win32/dlgbox/about-dialog-boxes?redirectedfrom=MSDN

# debuging

    void DebugBreak();
    __DebugBreak();
    key equivalent: var_dump, debugger
    https://docs.microsoft.com/en-us/windows/win32/debug/debugging-functions
    
 # comunication
    
    winsocs programming
    
    linux: socket programming
