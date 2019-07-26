# nurbsSurface
HTML Application to draw and modify a NURBS Surface in 3D

NURBS Surface = Non Uniform Rational B-Spline Surface

Requirements:
   1. Should enable the user to modify the x, y, z and h coordinates (homogeneous coordinates) 
       of 49 control points constituting a NURBS Surface (7 x 7 grid of control points).
       The range for coordinates of the control points should be [-1,1]. The user should 
       be able to modify these through sliders.
   2. Should display the NURBS Surface on the screen, and this surface should 
      change dynamically as the user modifies any of the values using sliders. 
      Perspective View. 
   3. Should display the bounding box of dimension 2 units, centred at the origin.
   4. Should enable the user to modify the camera angle (degrees), from which 
      viewing is done.
   5. Should enable the user to modify the u, w values of a chosen point, and should 
      display a moving point on the curve as the user modifies these values 
      using the sliders.
   6. Should display the knot vectors used for either of u or w.
   7. All user input should be via sliders.
   8. Should use WebGL, in the form of three.js. 

Note: Rather than write the NURBS code myself and reinvent the wheel, I have taken 
relevant extracts from the examples provided by three.js. These are all contained 
in the file nurbsHelper.js. This has the NurbsCurve and NurbsSurface definitions.
We just pass the inputs and get these classes to generate points on the curve and 
surface.

Tested on Chrome, Firefox, on Windows.
Uses WebGL as available in three.js

Please report issues to amarnaths.codeproject@gmail.com

Open the file <i>index.html</i> in your browser.

Screenshot
![Screenshot of NurbsSurface](https://github.com/amarnaths0005/nurbsSurface/blob/master/nurbsSurface.png)
