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

This program displays a cube moving in a circle, and
the assignment was to make the cube rotate about its y 
axis while moving in the circle. I also separated the 
shader loading from the program by creating a separate 
shader class with a shader loading function.

Compile:
	Navigate to build folder and make.
	Run executable from bin.
