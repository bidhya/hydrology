#hydrology


##My hydrology repository

###Tutorial for stage volume
See the [Stage - Volume Tutorial](../master/stage_volume_tutorial.py).
The working of the code is explained in the comments.  

###3D plotting
For 3D plotting of interpolated stream profile  [Profile Creator](../master/profile_creator.py).

###591 Check dam profile
#### Stage - Surface Area relationship
The stage(water height) vs water surface area relationship is calculated in this file [591 Check Dam](../master/profile_creator_591.py).
This file does following functions:
 1. Fills in between profiles.
 2. Creates x,y,z grid from profile.
 3. Creates interpolation of uniform grid.
 4. Creates a contour and 3D surface plot from the interpolated data.
 5. Calculates the contour area for given elevation levels.
 6. Plot of surface area vs stage.

