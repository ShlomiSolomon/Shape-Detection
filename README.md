# Shape-Detection
Computer Vision project, program that receives an image and identifies specific objects and shapes in the picture , coloring them and add the shape name too , (color each shape in a specific color and add in front of the shape her name).

In this project I used in method that called Counting Contours.

Contours are defined as the line joining all the points along the boundary of an image that are having the same intensity. Contours come handy in shape analysis, finding the size of the object of interest, and object detection.

OpenCV has findContour() function that helps in extracting the contours from the image. It works best on binary images, so we should first apply thresholding techniques, Sobel edges, etc.



![](https://i.makeagif.com/media/8-25-2019/JnOLUp.gif)
