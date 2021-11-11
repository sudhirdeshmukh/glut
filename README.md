# glut

- Get the freeglut from The freeglut Project :: About (sourceforge.net)
Martin Payne's Windows binaries (MSVC and MinGW)
- Extract into C: 
- copy freeglut.dll from C:\freeglut\bin\, paste into C:\Windows\SysWOW64

cl.exe /c /EHsc /I C:\freeglut\include OGL.cpp
link.exe OGL.obj /LIBPATH:C:\freeglut\lib freeglut.lib /SUBSYSTEM:CONSOLE
