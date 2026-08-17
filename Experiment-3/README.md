# Experiment 3: Perspective Transformation Using OpenCV

## Objective

To perform perspective transformation on an image using OpenCV and understand how an image can be transformed from one perspective to another.

## Description

Perspective transformation is an image processing technique used to change the perspective or viewpoint of an image. In this experiment, source and destination points are defined and a perspective transformation matrix is calculated to transform the input image.

## Tools & Libraries

* Python
* OpenCV
* NumPy
* Matplotlib

## Input

* `image.png` – Input image used for perspective transformation.

## Procedure

1. Load the input image using OpenCV.
2. Obtain the height and width of the image.
3. Define four source points on the original image.
4. Define four corresponding destination points.
5. Calculate the perspective transformation matrix using `cv2.getPerspectiveTransform()`.
6. Apply the transformation using `cv2.warpPerspective()`.
7. Display the original and transformed images using Matplotlib.

## Functions Used

* `cv2.imread()` – Reads the input image.
* `cv2.getPerspectiveTransform()` – Calculates the perspective transformation matrix.
* `cv2.warpPerspective()` – Applies the perspective transformation.
* `cv2.cvtColor()` – Converts the image color format for displaying with Matplotlib.

## Output

The original image and the perspective-transformed image are displayed for comparison.

![Output](output.png)

## Result

Perspective transformation was successfully applied to the input image using OpenCV. The experiment demonstrates how the viewpoint of an image can be modified using source and destination coordinates.

## Concepts Covered

* Perspective Transformation
* Image Warping
* Transformation Matrix
* Source and Destination Points
* OpenCV Image Processing
