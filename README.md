# LibSDL Tech Demos
**Michael Kristofik** ([kristo605@gmail.com](mailto:kristo605@gmail.com))

This project charts my progress as I learn SDL and become familiar with C++11
techniques.  I'm sharing my work because code like this wants to be free.  It's
also my first foray into cmake without a Build Guy to do all the setup for me.

## Random Map Generator

This was inspired by Amit Patel's [blog
post](http://www-cs-students.stanford.edu/~amitp/game-programming/polygon-map-generation/)
about Voronoi Diagrams being used for random map generation.  I'm surprised I
never learned about them in school because they're quite useful.  I wanted to
see if this idea could be scaled down to a hexagonal tile map.  I think the
results were pretty good.  The program generates n random regions and assigns
terrain types using a greedy graph coloring algorithm.

![screenshot](https://raw.github.com/mkristofik/libsdl-demos/master/random_screen.jpg)

## Hello World

No learning experience is complete without a Hello World program, so here it
is.  I create a window, load an image, and print some text with various levels
of anti-aliasing enabled.

![screenshot](https://raw.github.com/mkristofik/libsdl-demos/master/hello_screen.jpg)

----

### Requirements

[SDL 1.2.15](http://www.libsdl.org/)  
[SDL\_image 1.2.12](http://www.libsdl.org/projects/SDL_image/)  
[SDL\_ttf 2.0.11](http://www.libsdl.org/projects/SDL_ttf/)  
[DejaVuSans](http://dejavu-fonts.org/wiki/Main_Page) font (drop the .ttf file
in the top-level directory)

### Special Thanks To
[Battle for Wesnoth](www.wesnoth.org) for all of the art assets.  They can
draw, and I can't.

### License

Copyright 2012 by Michael Kristofik  
The license for code and art assets is described in the file COPYING.txt.