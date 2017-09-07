# TicTacToeQt
TicTacToeQt is a simple game written in C++ using the Qt framework (unsurprisingly). It takes advantages of features such as QPainter, Signals/Slots, and QLayouts. Combined with the high performance of C++, Qt is an ideal choice for designing desktop games. It even supports OpenGL (which I have not taken advantage of, but perhaps will in the future).

It currently comes (as default) two-player mode. X always goes first. I will be implementing a one-player mode with a fairly rational AI to play against in the very near future! (It's already been sort of done in the non-qt version, but I have to migrate the code over to the Qt version.)

### Build instructions
You are free to try to build this on your own using qmake and make, but personally I have had difficulty doing so. As of this moment (Sep. 6, 2017) the application was created using:
* Qt 5.9.1 (GCC 5.3.1 20160406 (Red Hat 5.3.1-6), 64 bit)
* g++ (Ubuntu 5.4.0-6ubuntu1~16.04.4) 5.4.0 20160609

Probably the easiest way to build TicTacToeQt would be to install Qt Creator with Qt ver. >= 5.9.1, and build the application using Qt Creator directly.

### Feedback
Please post an issue for any feedback or comments! Alternatively, feel free to email me at brianhylee99@gmail.com.
