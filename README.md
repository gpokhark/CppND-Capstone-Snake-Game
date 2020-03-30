# CPPND: Capstone Snake Game Example

This is a starter repo for the Capstone project in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213). The code for this repo was inspired by [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) excellent StackOverflow post and set of responses.

<img src="snake_game.gif"/>

The Capstone Project gives you a chance to integrate what you've learned throughout this program. This project will become an important part of your portfolio to share with current and future colleagues and employers.

In this project, you can build your own C++ application or extend this Snake game, following the principles you have learned throughout this Nanodegree Program. This project will demonstrate that you can independently create applications using a wide range of C++ features.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  * Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.

# Project Rubrics

Modified the existing repository to create a 2 player game.
- Control for first player - Up, Left, Down, Right arrow keys
- Control for second player - w, a, s, d keys for Up, Left, Down, Right movement.

1. The project demonstrates an understanding of C++ functions and control structures.

2. The project accepts user input and processes the input. It takes input from the keyboard for controlling the snakes.

3. The project uses Object Oriented Programming techniques.The project code is organized into classes with class attributes to hold the data, and class methods to perform tasks.

4. Classes use appropriate access specifiers for class members. All class data members are explicitly specified as public, protected, or private.

5. Class constructors utilize member initialization lists.

6. Classes abstract implementation details from their interfaces. All class member functions document their effects, either through function names, comments, or formal documentation. Member functions do not change program state in undocumented ways.

7. Classes encapsulate behavior.Appropriate data and functions are grouped into classes. Member data that is subject to an invariant is hidden from the user. State is accessed via member functions.

8. The project makes use of references in function declarations.