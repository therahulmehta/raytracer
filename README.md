# Raytracer

I'm trying to **slowly** write a basic CPU based raytracer. I'm using this as an opportunity to get into the nitty gritty of C++ 11 and just learn about computer graphics. 

The scope of this project is to get positionable cameras, diffuse materials, and antialiasing working. If I can stomach this project the next one may expand to more complex raytracing and graphics topics. At the back of this I'd like to learn how to use a GPU properly but that's much further down the line. 

So far I've setup the primitives for creating the ray vectors, the next step is to draw the rays into the scene. 


# Files

main.cpp -> Currently a file to test the header files and render gradients. 
color.h -> Currently simply renders pixels to ostream out.
vec3.h -> 3D vector support functions and inline functions.