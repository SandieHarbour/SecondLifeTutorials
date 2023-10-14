# Using the Grid

When we build, sometimes we want to position things accurately.  Second Life has a feature that helps us do that.  It is called Snap To Grid.




## How It Works:
- Rez a cube and move it using the red, green and blue arrows (aka axis-arrows)
- As you move it a pair of rulers will appear.
- Moving  your mouse over those rulers will cause the cube to snap to the grid lines on the ruler.

![](images/Rulers%20on%20Prim.png)







### Moving the cube with the "Positioning Handles"
Another way to move the prim is to use the Positioning Handles.
When you drag on those, the grid shows up like a piece of graph paper.
![](images/Corner%20Handle%20Grid.png)




## A look at the build window
### Snap Checkbox
There is a checkbox under the edit tab of the Build window labeled Snap.
Please make sure that is checked.
Click the arrow to the right the snap checkbox to open the grid options.
Lets take a look at the parameters.
![](images/Build%20Window%20&%20Grid%20Options.png)
### Grid Options
#### Units (meters)
The first one in Units (meters)
This indicates the size of the grid unit in meters.
It's probably set to 0.500
Set it to 1 and move your cube.
See how the lines on the rulers are set to even numbers?
Now set it to .1 and move your cube.
Now the grid markings on your ruler are much finer.
Set it back to .5

#### Extents (meters)
Extents sets the size of the visible white grid when dragging the colored positioning handles instead of an axis arrow, centered on the object you're editing.

Most likely it is set to 12 (default)
Set it to 1 and use the positioning handles to move your cube.
See how much smaller the grid is surrounding your cube?
Set it back to 12 and move it again.  Notice how much larger the grid is.

#### Decimal Precision
Not much has been written about this parameter.
For this class, we will leave it at its default of 5.

#### Snap to sub-units 
Divides the grid into smaller sub-units for greater precision. The number of sub-units depends on how closely your camera is zoomed in and goes up to 16 divisions between main Grid Units. Edited objects snap to these sub-unit lines the same way they do to a normal grid line.

#### View cross-sections 
Displays a visible plane in the center of the object you are editing, oriented orthogonally to the axis the object is moving on. This plane extends into adjacent objects to aid precision alignment.

We will ignore this parameter in this class
    
#### Opacity 
Sets how opaque the grid appears.

You may close the window labeled Grid Options.

# Grid Mode: 
The last setting we will look at is Grid Mode.  It is a little below the Snap Checkbox.
![](images/Grid%20Mode.png)


There are 3 options: (World, Local and Reference)

#### World Mode: 
The rulers are relative to absolute region coordinates.
So far this is the setting we have been using.   The numbers you see are the distances from the bottom southwest corner of the sim you are in.
![](images/World%20Mode.png)


#### Local Mode: 
The rulers are relative to the cube's coordinates.
Set the grid mode to local and use the axis-arrows to move it.
Notice that the center of the cube is 0x




#### Reference Mode: 
Rulers are relative to be prim being edited.
