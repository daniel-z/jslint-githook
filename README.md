A git hook to execute jslint automatically when you do a git commit.
This will run for every javascript file modified.

This was designed to be used in a developer environment.

TO INSTALL
1.- Unpack the folder 
2.- Put jsl file in your git root folder
3.- rename jslint-githook as pre-commit and move it to the .git/hooks folder in your project
4.- enjoy


NOTE: if you want to move the jsl file to a different location, just update the variable PathToJslint 

THIS PACKAGE INCLUDES
jslint-githook       - pre-commit git hook
jsl                  - version 0.3.0 - unpackaged
jsl-0.3.0-mac.tar.gz - original jsl package from http://www.javascriptlint.com/