# Tesseract

This is a proof-of-concept visualization of a 4d blocksworld game. A player in the 4d world would only be able to see a 3d slice of it at a time (much like a 2d being could only comprehend one 2d slice of the 3d reality at a time, that is, a plane). In a MineCraft-like game, this means that a literal additional dimension is added to the game, which allows for novel complex interaction among the players and between the players and the world. For example, mazes can be constructed that require  intricate understanding of 4d geometry to navigate them.

The script visualizes a grid of 4d cubes (tesseracts https://en.wikipedia.org/wiki/Tesseract). A 3d slice of the 4d reality is computed at each frame to show to the player). The 3d slice is further projected down to the 2d screen using a classical graphics engine. To see the visualization simply execute the Tesseract_tidy.ipynb notebook (you'll need jupyter installed).

The ultimate vision for the project is to rewrite it as a full-fledged app. This would require writing custom GPU shaders for efficient rendering of the 4d structures.

## References

Inspired by http://hi.gher.space/classic/page8.html and https://www.youtube.com/watch?v=9yW--eQaA2I&t=24s.

