# Penzil

![Preview of Penzil user interface](preview.png?raw=true "Preview of Penzil user interface")

Penzil is a web application for sketching in 3d, powered by three.js and Vue. It is intended to be a light version of Blender's Grease pencil for the web. Penzil is designed for tablet with a pen, but it should work on desktop as well.

The project is currently on pause and offered as-is. 

## Basic instructions

- You can draw/erase with left mouse button, finger or pen on top of the "3d canvas", the white plane in the 3d scene.
- You can adjust the position of the "3d canvas" with the arrow-heads or the arcs at the center.
- You can move and rotate the camera using the touchpad, two fingers or by pressing the alt key and dragging with the left mouse button. Panning is done with three fingers or by pressing the Spacebar and dragging with the left mouse button.
- You can swap your primary tool between pencil and eraser from the selector at the top.

## Saving, loading and exporting

- Penzil is a fully local application. No servers are involved. Because of the size of the files (and, partially, scope) saving and loading is currently done manually. You can save a .json file with your drawing and restore it with Load. Big files will take a long time to load as the geometries are not optimized yet.
- Penzil exports in a format friendly to Blender's grease pencil but an importer is necessary. The importer doesn't exist yet but I have a Python script that can be run from Blender. If you want to import into Blender, join the Penzil Discord server. You can find the link in the app.

## Acknowledgements

This is the fork project of [Penzil](https://github.com/jacopocolo/Penzil) by [Jacopo Colò](https://github.com/jacopocolo). The original project is no longer maintained and the dependencies are outdated. This fork is a continuation of the project with updated dependencies and some new features (maybe in the future).