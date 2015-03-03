Anthony Moran, 03/02/2015,
My solution to this lab was to first create the vertices for the pyramid shape and both
the light and material property vectors needed for the modified Phong lighting model. Then I
added the function quad() that calculates and creates the normals of the shape. Next, I added
the colorCube() function that uses the quad() function on each surface. Then, within the init
function I used the MV.js file to calculate the necessary products for the lighting, to
calculate the properties of the perspective projection matrix, and to create the buffers for the
vertex positions and the normal positions. After that, I created a keyboard event listener and
set it to listen for each arrow key. Then, I added the render function to put together the 
model view matrix and draw the shape. Lastly, within the HTML file, I calculated the lighting
for the shape within the vertex shader; as well as the vertex positions.
