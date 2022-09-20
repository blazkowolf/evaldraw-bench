# Grid Raycasting

My attempt at a pseudo-3D world using raycasting.

__Full disclosure:__ I followed the awesome raycasting documentation and code from [Lodev](https://lodev.org/cgtutor/raycasting.html)

## Why?

This project was a proof of concept. I am a huge fan of games such as Wolfenstein 3D and Blake Stone, and I have always found their raycasting graphics fascinating. I wanted to try it for myself.

Unfortunately, this iteration does not allow for texture mapping. I went for a simpler implementation and made all the walls solid colors.

## About Raycasting

Raycasting is an approximation of a 3D world by assigning depth to a top-down 2D map, and draw it to the screen from a first-person perspective.

There are many notable implementations of raycasting allowing for more diverse and realistic environments when implemented with Sectors, as opposed to a 2D array.
