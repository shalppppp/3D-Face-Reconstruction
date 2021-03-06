# 3D Face Reconstruction


The goal of this project is to create a 3D face reconstruction software that could generate 3D face model from a 2D face image. Those 3D model faces can be used in further projects for animation, game development and AI projects. 

![](file1.gif)

* https://www.youtube.com/watch?v=e6nqRUt7muw - video preview

### Prerequisites

Make sure to install these libraries before running the software.


* [Dlib](http://dlib.net/) - Face detection.
* [OpenCV 3.0](https://opencv.org/opencv-3-0.html) - Implemented for image manipulation and texture creation.


## Deployment

When finished with installing libraries, proceed to the project folder and run the shell command:

```sh
g++ -std=c++11 -o 1p 1p.cpp -llapack -lblas -ldlib -lgif pkg-config opencv --cflags --libs
```
to compile the file 1p.cpp 

To run the program, type the command:

```sh
./1p [Image_file]
```

it will export the 3D face model, enjoy!
