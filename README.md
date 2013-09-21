btp-project
===========

C, C++, OpenGl based routing application for fault tolerance mesh topology

Whole application is written in modular way using Qt library and Qt Creator in mac.

You can download Qt for any platform from qt-nokia.org.


There are four modules.

1) IO module => this module reads the input file of problem and save back it.

2) Gui module => this module is responsible for opengl drawing of mesh topology and fault system.

3) Core module => main module which read the problem from IO module and solves it and then send to 
 output module.
 
 4) App module => Integrated all modules into one app.
 
 HOW TO RUN/COMPILE
 
 Dependencies
 1) gcc, g++, c++ (gnu tools for c/c++)
 2) qmake (for qmake compilation)
 3) make
 4) qt library (QtCore, QtGui, QtIO, etc)
 
 
 Open .proj file in Qt-creator
 
 Or
 
 qmake from command line
 
 then make
 
 output will be in build directory according to Release or Debug config.
 
 
