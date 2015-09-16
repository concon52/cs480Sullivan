A simple example of matrix use in OpenGL
========================================

Building This Example
---------------------

*This example requires GLM*
*On ubuntu it can be installed with this command*

>$ sudo apt-get install libglm-dev

*On a Mac you can install GLM with this command(using homebrew)*
>$ brew install glm

To build this example just 

>$ cd build
>$ make

*If you are using a Mac you will need to edit the makefile in the build directory*

The excutable will be put in bin

Additional Notes For OSX Users
------------------------------

Ensure that the latest version of the Developer Tools is installed.

This program displays a cube and has a menu which is accessible
via a right mouse click to provide a level of interactivity. The 
menu provides the user with an instruction on what the left mouse click will do, as well as a quit option. In this program the instructions for keyboard manipulation of the cubes is displayed on the screen. There is also functionality for the arrow key buttons to set the orbit or rotation of the planet, while the keyboard actions simply reverse the rotation or orbit. [EXTRA CREDIT] There is also dynamically changing text at the bottom which will display whether the rotations of the cubes are clockwise or counterclockwise.


Compile:
    navigate to build folder and make, run executable
    from bin.
