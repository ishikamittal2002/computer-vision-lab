# Experiment 2: Camera Calibration Using Checkerboard

## Objective
To detect the corners of a checkerboard pattern and perform camera calibration using OpenCV.

## Description
This experiment demonstrates the process of camera calibration by detecting the inner corners of a checkerboard image. The calibration process estimates the camera's intrinsic parameters and distortion coefficients.

## Tools & Libraries
- Python
- OpenCV
- NumPy
- Matplotlib

## Input
- `checkerbox.png` – Checkerboard image used for corner detection.

## Procedure
1. Load the checkerboard image.
2. Convert the image to grayscale.
3. Detect checkerboard corners using `cv2.findChessboardCorners()`.
4. Generate object points corresponding to the checkerboard pattern.
5. Perform camera calibration using `cv2.calibrateCamera()`.
6. Display the camera matrix and distortion coefficients.
7. Visualize the detected checkerboard corners.

## Output
- Successfully detected checkerboard corners.
- Computed the camera intrinsic matrix.
- Computed the lens distortion coefficients.

## Results
The experiment successfully demonstrates:
- Checkerboard corner detection.
- Camera calibration.
- Estimation of camera intrinsic parameters.

## Files
```
Experiment-2/
├── experiment2.ipynb
├── checkerbox.png
├── output.png
└── README.md
```

## Sample Output
- Camera Matrix
- Distortion Coefficients
- Detected Checkerboard Image

## Concepts Covered
- Image Processing
- Checkerboard Corner Detection
- Camera Calibration
- Camera Matrix
- Distortion Coefficients
- OpenCV Computer Vision
