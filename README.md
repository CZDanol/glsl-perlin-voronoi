# GLSL Compute shader noises

This repository contains a compute shader implementation of 2D + 3D Perlin noise & Voronoi diagram using thread cooperation. It is basically just a source copy-paste from my Minecraft clone project ( https://github.com/CZDanol/AnotherCraft ), so you might need some tweaking to get it running. I just put it into a separate repository so that people can find it.

I've done some measurements and the 3D Perlin is cca 3x faster than non-thread cooperation version done by Ashima ( https://github.com/ashima/webgl-noise , no measurements on the Voronoi, but it seems to be rather slow ). There is a document in this repository documenting the optimizations I have done, however it is in Czech.

Feel free to use this however you find appropriate (don't kill any puppies with it tho, that would make me mad).