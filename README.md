** DGP2026 Digital Geometry Processing **

Assignment 0

0) First of all, configure your development environment.

1) download the **data-A0.zip** file from the course site, and
unzip it in your computer. Don't unzip it within this directory, named
DGP2026-A0, because otherwise git will try to save the large data
files in your git repository, and it may fail due to size limits. It
is rather difficult to fix this problem once you get there.

2) In this directory, DGP2026-A0, in addition to this README file, you
should find the following subdirectories:

  **assets, forms, qt, and src**

The assets, forms, and qt subdirectories contain files which you
should not modify for the moment. We will come back to these
subdirectories later.

You will use Qt Creator to build the interactive application
DGP2026-A0

The **src** subdirectory contains the following subdirectories:

  **io, util, wrl,** and **gui**

The qt top subdirectory mentioned above contains the following files

DGP2026-A0.pro
DGP2026-A0.pri

used by qmake. Don't modify this files unless you add new files to the
hierarchy.

Qmake will create a new subdirectory named 'build' and another hidden
subdirectory named '.qtcreator'. These subdirectories can be deleted with
all their contents to start the Qt build process over. You should also
find the interactive executable in the build subdirectory.

3) Before compiling the application for the first time, edit the file
   src/gui/GuiStrings.hpp

In my version, this files contains the definition of the following strings

#define STUDENT_NAME "Gabriel Taubin"

Replace my name by your name in the last string and save the file.

4) Run Qt Creator to create projects files for the
application, and make sure that it compiles without errors.

5) Verify that you can load and display the *.wrl files contained in
the data-A1 directory using the FILE->Load menu button.

6) Using the FILE-Save menu button, save the files with different
*.wrl names, and verify that you can reload the files that you have
created using the FILE->Load button.

7) You don't have to submit anything for Assignment 0. 
