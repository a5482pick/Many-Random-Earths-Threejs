__ManyRandomEarths.html__ creates 70 randomly positioned and randomly coloured spheres that cast and receive shadows, and that have a superimposed 'earth' image composed of three textures. &nbsp;The 'earths' remain stationary but both the camera and the point light source move automatically about the scene, so that shadows move and are visible from different points of view. 

The camera is forced to always look straight ahead (rather than at the centre of the scene), thus creating the _sense_ that the collection of spheres is translating rather than rotating. &nbsp;The camera's motion is oscillatory.

Additionally provided is code that makes the 'earth' that is pointed to by the cursor glow green, and also code that logs the cursor's screen coordinates each time a new one of these cursor intersections occurs.

NOTES: For smoother motion control with the mouse, it may help to comment-out the line 'scope.object.lookAt( scope.target );' from _OrbitControls.js_. 

