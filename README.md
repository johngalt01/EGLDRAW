# EGLDRAW

9/28/2025

MDRAW2.COM is the drawing program i have not gotten around to completing the interface but i wanted to post it finally.

You will need a fabgl Ansi Terminal and a mouse to use.

The COMMANDS ARE:
Q/q to quit.
L/l create a line.
B/b create a box.
C/c create a Circle.
E/e Create an ellipse.

T/t Create a fill Box.
S/s Create a fill Circle.
R/r Create a Fill Ellipse.

D/d Clears the Entire work space and starts over.
] redraws the workspace does not start over. its like a screen refresh.

P/p Paintbrush mode

'Backspace' removes last element placed.

The left mouse button is used to place a start and end point for the element. used for paintbrush mode. 

right mouse button will change available color. it will also back out an element selection. so you can select a new element to place.

* limit to 500 elements * keep in mind the more elements the slower the screen draw. you want to keep scenes simple for game making.

* Poly and fill poly was not implemented due to future GEOFF terminal port. *

---
EGL is an updated image format based off IGL
----

the scope of this project is for the FABGL ANSI Terminal.
it is an image format that uses the FABGL shape primatives and colors to fast draw pixels, lines, circles, boxes to the terminal screen.

uses include visual information for games, paint and drawing, printer output, GUI creation.

the software package will include. MDRAW2 a mouse driven paint drawing program which allows up to 500 elements to be placed on the screen.
this limit is due to several reasons but can be easy ignored as you can stack EGL files by merging them and allow for more elements.

MDRAW2 is a simple drawing enviroment

EGLDRAW is a sample display program to show how EGL files are displayed and allows for manipulation of Scale, X-Y Transition, and simple reflection and rotation in 90 degree increments.

IGLTOEGL is a simple file converter to take existing IGL And make EGL format.


![DSCN6359](https://github.com/user-attachments/assets/0d3ccb68-0d82-408d-97ab-614bfca96543)
![DSCN6364](https://github.com/user-attachments/assets/9182ab41-58ed-45a8-9f0e-4445e8748475)
