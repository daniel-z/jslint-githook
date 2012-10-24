# JSLint-GitHook
http://daniel-z.github.com/jslint-githook/
=============

A git hook to execute jslint automatically when you do a git commit.
This will run for every javascript file modified.
This was designed to be used in a developer environment.


## TO USE IT

1. Put jsl file in your git root folder
2. Rename jslint-githook as pre-commit and move it to the .git/hooks folder in your project

#### NOTE: if you want to move the jsl file to a different location, just update the variable PathToJslint inside jslint-githook file 


## THIS REPO INCLUDES

* jslint-githook       - pre-commit git hook
* jsl                  - jsl library version 0.3.0 - unpackaged
* jsl-0.3.0-mac.tar.gz - just a backup of the original jsl library package from http://www.javascriptlint.com/

This is the first version and may not be too flexible, but I hope this works for you.