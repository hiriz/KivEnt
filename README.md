KivEnt
======

Warning Tutorials Out Dated! Will Fix Soon, Look at Sample Application (more complex) or https://github.com/Kovak/KivyMallDirectory (simple example)

Also Warning: Development is active right now and I expect to break everything with my next planned changes. This is going to be good though because Entities and Components will be getting a better, more optimizable interface.

KivEnt is an Entity Based Game Engine for Kivy

Requires Cymunk in order to run: 
get the master branch from here:https://github.com/tito/cymunk

You will need to compile both the cymunk module as well as the kivent_cython folders code.

I develop using [Kivy 1.8](https://github.com/kivy/kivy) (so current indevelopment branch, this is because there are some great performance enhancements
in the most recent branch)

Cymunk and Kivy must both be in your environment path in order to buld kivent as it must cimport modules from both of these modules.

Do not make install kivy, simply make it and then

export PYTHONPATH=~/path/to/kivy:$PYTHONPATH 

do the same for cymunk
(this is the path to python folder in cymunk)
export PYTHONPATH=~/path/to/cymunk/cymunk/python:$PYTHONPATH



Tested on Asus Transformer TF101, Droid 4, Droid RAZR M, Ubuntu 13.04 
