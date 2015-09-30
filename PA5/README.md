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

This program displays a model which is loaded from the command line argument. This file must be in the .obj filetype format and would be specified by using the command ./Matrix File.obj. This program will display the loaded object and it will be rotating slowly in the center of the window. There are directions for controlling the rotation of the object on screen and there is a menu option for it as well. This model was loaded using assimp.


Compile:
    navigate to build folder and make, run executable
    from bin.
