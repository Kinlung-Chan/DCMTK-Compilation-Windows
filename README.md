# DCMTK-Compilation-Windows
DCMTK compilation under windows with visual studio 2017

How to compile dcmtk with visual studio under Windows?

1. Download the dcmtk source code and support libraries on the OFFIS website.
2. Download CMake 3.10.0.
3. Build solution of the source code.
4. Replace scu.h and scu.cc to add SendNCREATERequest and Send NSETRequest support to dcmtk.
5. Build all projects in visual studio.
6. Install dcmtk header files, library files to the installation folder.
