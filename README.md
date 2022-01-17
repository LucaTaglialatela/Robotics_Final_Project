# Robotics_Final_Project
NTU CSIE5047 FALL 2021 GROUP 10

```image_sub.py``` is the main method of our program which links together most other files.

```object_detection.py``` is responsible for processing input images and detecting colors, shapes and centroids/orientations. For this purpose it uses the ```color_def.py``` and ```shape_detection.py``` files.

```color_def.py``` defines for each of our supported colors how to extract objects from an input image.

```shape_detection.py``` contains the logic required to define the shape of an object corresponding to an input contour.

```template_scanner.py``` contains the logic required to convert a 2-dimensional template into a 3-dimensional building plan.

```rotation.py``` is a supplementary procedure written for calibration purposes.
