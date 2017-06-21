__ManyRandomEarths.html__ creates 70 randomly positioned and randomly coloured spheres that cast and receive shadows, and that have a superimposed 'earth' image as a texture. &nbsp;The 'earths' remain stationary but both the camera and the point light source move automatically about the scene, so that shadows move and are visible from different points of view. 

The camera is forced to always look straight ahead (rather than at the centre of the scene), thus creating the _sense_ that the collection of spheres is translating rather than rotating. &nbsp;The camera's motion is oscillatory.

For smoother motion control with the mouse, it may help to comment-out the line 'scope.object.lookAt( scope.target );' from _OrbitControls.js_. 

NOTE: There is a delay of a few seconds before smooth rendering begins. &nbsp;(Loading all the textures causes this delay.)
