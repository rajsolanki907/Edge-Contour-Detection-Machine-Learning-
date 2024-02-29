# Edge-Contour-Detection-Machine-Learning-
Edge &amp; Contour Detection - Machine Learning using CV2

**Description**
This Python project demonstrates basic image processing techniques using OpenCV to identify and count black squares in an image. It performs the following steps:

**Image Loading**: Loads an image containing black shapes.
**Grayscale Conversion**: Converts the image to grayscale for easier edge detection.
**Canny Edge Detection**: Applies the Canny edge detector to extract edges from the grayscale image.
**Contour Finding**: Identifies and isolates individual shapes (contours) within the image.
**Counting Contours**: Counts the number of detected contours, which correspond to the black squares in this specific case.
**Visualization**: Displays the original image with green outlines drawn around the identified squares.

**Requirements**
  - Python 3.x (https://www.python.org/downloads/)
  - OpenCV library (pip install opencv-python)

**Instructions**
1. Install OpenCV: Open a terminal or command prompt and run:

**Bash**
pip install opencv-python

2. Download the Image: Download the image named pexels-pixabay-219906.jpg and place it in the same directory as this Python file (script.py).

3. Run the Script: Open a terminal in the project directory and execute:

**Bash**
python script.py

**Output**
The script will display the original image with green outlines drawn around the detected black squares. It will also print the number of detected contours to the console.

**Additional Notes**
 - This code is a basic example and can be extended to handle different shapes, colors, or more complex scenarios.
 - Feel free to experiment with different image inputs and OpenCV functions to explore additional image processing capabilities.
