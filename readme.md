## Introduction
The primary goal of this task is to be introduced to 3D graphics and manipulate them in practise.  
In this program, I have implemented numerous features to practise this concept.

## Primary features

### Feature 1: The main cube
As soon as the program is launched and the scene is visible, you are able to locate a stationary 2x2x2 cube centred at the origin, with unique textures on each side.

### Feature 2: Unique coordinate system axes
There are three lines drawn over the axes to help the user observe them easier. These are coloured red, green and blue, for the X, Y and Z axes respectively.

### Feature 3: Rotate the cube
You are able to rotate the cube about the X, Y and Z axes by using the preset hotkeys. In order to rotate the cube around the X axis, you need to press X.
For the Y axis, you need to press Y; and for the Z axis, you need to press Z.

### Feature 4: Different render modes
This feature allows you to render the cube in three different modes: faces, edges and vertices.  
The system is implemented in such way that at any given time, one mode is rendered. Furthermore, you can toggle the mode off and on by pressing the preassigned hotkey.  
In order to observe the cube's faces, you need to press F. For the edges, you need to press E. And lastly, to observe the cube's vertices, you need to press V.  
By pressing the hotkey of the mode is currently rendered, the program renders another mode. The preset behaviour is as follows:  
* Faces are being rendered: F -> edges rendering mode activated
* Edges are being rendered: E -> vertices rendering mode activated
* Vertices are being rendered: V -> faces rendering mode activated
You may also rotate the cube in either of the rendering modes.

### Feature 5: Translate the camera
The camera can be controlled and moved around the scene in all directions via the default hotkeys:
* Y axis
	* Up: Arrow up
	* Down: Arrow down
* X axis
	* Right: Arrow right
	* Left: Arrow left
* Z axis
	* Forward: W
	* Backward: S

### Feature 6: Orbit the camera
The program enables you to orbit the camera around the cube, allowing you to observe the cube from any direction and position you wish.  
You may orbit the cube in four directions, by pressing the following hotkeys:
* Up: Numpad 8
* Down: Numpad 5
* Right: Numpad 6
* Left: Numpad 4

### Feature 7: Stanford Bunny
In addition to the cube, there exists a bunny in this program that is contained within the cube. You may render the bunny in the three rendering modes mentioned for the cube using the same hotkeys.  
The rendering mode toggle system applies to the bunny too.  
Moreover, you may rotate the bunny about the X, Y and Z axes using the same hotkeys as explained in Feature 3.

### Feature 8: Disco
By pressing L, you can activate disco mode! By doing so, you spawn in a smaller bunny, a large disco ball and two smaller disco balls!  
The large disco ball will emit lights of different colours constantly, giving the scene an immersive disco atmosphere.
The two bunnies immediately start circling around the cube.  
Additionally, the bigger bunny and the cube start rotating at very fast speeds, with the two smaller disco balls being on the right and left sides of the cube.
There is also another hidden feature, where you can press M to slow down the rotation speed & change the lights to white.  
Lastly, you may deactivate this feature by pressing L again.