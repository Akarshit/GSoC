# Google Summer Of Code 2016

Project Details
----
__Organization__ -The Center for Connected Learning and Computer-Based Modeling  
__Mentor__ - Robert Grider  
__Student__ - Akarshit Wal

## Project Abstract
The aim of the project was to add some features to the [NetLogo](https://github.com/NetLogo/NetLogo) Desktop Editor. The features added are -

### Features Implemented
###1. [Auto Complete](https://github.com/NetLogo/NetLogo/pull/1072)
This features adds a pop-up box to the editor as a user types a command or reporter. The user can simply choose the suggestion using the arrow keys or dismiss the pop-up. Some enhancements have also been made in the feature like

1. [Elements can be chosen with mouse click](https://github.com/NetLogo/NetLogo/pull/1080)  
2. [Integration with command center](https://github.com/NetLogo/NetLogo/pull/1081)   
3. [Algorithm improvements](https://github.com/NetLogo/NetLogo/pull/1093)

The screenshots of the feature can be found below.

![Imgur](http://i.imgur.com/Zl2LIRe.png)

###2. [Show Usage](https://github.com/NetLogo/NetLogo/pull/1079)

This adds a pop-up box to the editor which can be selected from the right click menu. The pop-up contains all the occurrence of the variable for which the `Show Usage` was invoked.
Screenshots of the pop-up are attached below.

###3. [Jump To Declaration](https://github.com/NetLogo/NetLogo/pull/1110)
This add a feature by which the user can directly jump to the place of declaration for a variable. The option can be easily selected from the right click menu.

###4. [Undo/Redo for widgets](https://github.com/NetLogo/NetLogo/pull/1088)
The users can now undo/redo the addition/removal/resizing/movement of widget. The shortcuts for the undo/redo are same as that for normal text undo. The feature also remembers the selected/unselected state of the widget and supports easy editing of the widgets.
