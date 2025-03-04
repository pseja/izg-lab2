# Generating basic objects in a raster

Author: Lukáš Pšeja

xlogin: xpsejal00

## Assignment
1. Solving Problems with the DDA Algorithm (2 points)
  - Complete the code in the `rasterizeLine()` function.
  - The correct solution will draw line segments in all quadrants.
3. Circle Symmetry (1 point)
  - Complete the code in the `put8PixelsOfCircle()` function.
  - The correct solution will draw the entire circle.

## Setup
To compile this application, you'll need GCC 7.0.0+ and CMake 3.12.0+.
With Ubuntu, you'll also need to install [libsdl2](https://packages.ubuntu.com/en/source/focal/libsdl2).

```sh
git clone git@github.com:pseja/izg-lab2.git
cd izg-lab2
git submodule update --init --recursive
mkdir build
cd build/
cmake ..
make
./izg_lab_02
```

## Usage
| **Key/Button**           | **Action**                          |
|--------------------------|-------------------------------------|
| Left mouse click down    | Sets the beginning point of line.   |
| Left mouse click up      | Sets the ending point of line.      |
| Right mouse click down   | Sets the center point of circle.    |
| Right mouse click up     | Sets the radius of circle.          |
| Middle mouse hold & drag | Rotate the current polygonal model. |
| L                        | Load testing image.                 |
| S                        | Save current raster into image.     |
| D                        | Draw lines from the lines.txt file. |
| T                        | Draw line testing pattern.          |
| B                        | Draw polygonal cube.                |
| N                        | Draw polygonal cuboctahedron.       |
| M                        | Draw polygonal model.               |
| C                        | Clear the raster.                   |
| ESC                      | Quit application.                   |
