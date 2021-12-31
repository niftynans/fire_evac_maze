# fire_evac_maze
This project aims to provide the best path for evacuation of multiple agents on a given floor plan for multiple fire origination points through a maze solver algorithm which uses the Dijkstra Algorithm. 

We used the ROBIN dataset for 3,4 and 5 BHK floor plans. The dataset contains about 500 images of generalised floor plans. We processed 70 images at random from this dataset to test our algorithm.

The data can be found at: https://github.com/gesstalt/ROBIN.git

OpenCV has mainly been used for tasks like reading and writing an image,
image processing, image manipulation for obstacle addition.

Basic libraries such as Matplotlib have been used for plotting graphs,
images and figures and Numpy for calculations and manipulations of different 
data structures such as lists and dictionaries.

Glob is a unix style file manipulation library, which has been used to load
the dataset into the working environment.

Imageio Imageio is a Python library that provides an easy interface to read 
and write a wide range of image data. 
We have used it to save the final output of our working environment.

Pyglet is a cross-platform windowing and multimedia library for Python, 
intended for developing games and other visually rich applications. However,
we have used it to show only  the output of our code in a gif format.


