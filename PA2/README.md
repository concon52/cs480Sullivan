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
menu provides a number of of options including starting and 
stopping all movement of the cube, or just starting and stopping
one element of motion such as the rotation about its Y-Axis. There
is also inactive menu buttons used as an informational tooltip to 
let the user know the different mouse and keyboard buttons to press
to invoke different actions. In this program the space button on the 
keyboard will change the direction the cube rotates about its Y-Axis,
and the left mouse button will change the direction the cube travels 
in a circle. The start/stop all option on the menu will start 
rotation and/or spin, and if the cube is spinning and rotating it will 
stop both. 

Compile:
    navigate to build folder and make, run executable
    from bin.
