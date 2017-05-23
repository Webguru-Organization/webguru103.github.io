ThreeFab	
=============

ThreeFab is a tool that allows designers and developers to quickly fabricate and manipulate a three.js scene.  This is currently an alpha build as a proof of concept. You will need a WebGL capable browser.

For those not familiar with [Three.js][1] 

[1]: https://github.com/mrdoob/three.js

[TRY IT OUT][2]
[2]: http://blackjk3.github.com/threefab/

Controls
=============

Keyboard controls
-------------
* S - Zoom in and out on scene (Zoom also works with mouse wheel)
* D - Pan around scene
* X - Delete selected object
* SPACE - Start stop animation preview

Viewport
-------------
To move the camera click and drag anywhere in the viewport.  

Targeting objects
-------------
Double click a mesh object to target.  The viewport controls will then rotate according to the registration point of the targeted object.  Clicking the "center" button in the "Controls" panel will re-target the viewport controls to the center of the scene.

Positioning objects
-------------
To position an object you can use the manipulator tool or use the individual position attributes in the transforms panel.

Transforms
-------------
The transforms are setup in blocks of three coordinates (x,y,z).  The first block is for position, second is for rotation, third is for scale.  Note: Rotation is currently in radians. 

Outliner
-------------
The outliner contains all the children that can be manuipulated in the scene. To change the selected object you can either click on that object in the viewport or use the drop down provided in the outliner.

Textures
-------------
To add a texture first select a model and drag and drop the image on to the viewport.

Exporter
-------------
To generate and export the current three.js code click the generate button in the top right.  Note: You will need to update the paths for any textured materials and JSON models.  Threefab will put a placeholer url that will need to be modified.

Animation
-------------
To preview an animation the model must have morph targets set up.  The animation timeline will then allow you to play, pause, and scrub through the keyframes.  To test use the animated models that come with three.js.  (Ex. horse.js, parrot.js, flamingo.js, stork.js)

Screenshots
=============
![Screenshot](http://blackjk3.github.com/threefab/assets/screenie0.jpg)
![Screenshot 2](http://blackjk3.github.com/threefab/assets/screenie1.jpg)