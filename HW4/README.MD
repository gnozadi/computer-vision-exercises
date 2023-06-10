# Image Processing Exercises

This repository contains solutions for Homework 4 exercises related to color space conversion, color quantization, and feature detection using Harris Corner and SIFT/SURF features. The exercises are implemented in a Jupyter Notebook.

## Table of Contents

- [Instructions](#instructions)
- [Exercises](#exercises)
  - [Color](#color)
    - [Color Space Conversion](#color-space-conversion)
    - [Quantization](#quantization)
  - [Features](#features)
    - [Harris Corner Detector](#harris-corner-detector)
    - [Scene Stitching with SIFT/SURF](#scene-stitching-with-siftsurf)
- [Requirements](#requirements)

## Instructions

All homework submissions should be sent through VU. Ensure the report is in PDF format named as `4-FirstName-LastName.pdf`. Pay attention to the deadlines and avoid plagiarism. You may compare your results with MATLAB outputs optionally.

## Exercises

### Color

#### Color Space Conversion

1. **Convert Lena to HSV**

   - Convert the Lena image to HSV format.
   - Display the H, S, V components as separate grayscale images.

2. **New Color Space Conversion**
   - Present Lena in a new color space not introduced in class.
   - Manually convert R, G, and B to the new color space components.

#### Quantization

1. **Color Reduction for Weaving**
   - Reduce the number of colors in the Baboon image for weaving into 32, 16, and 8 color modes.
   - Compare using MSE and PSNR.
   - Display the results.

### Features

#### Harris Corner Detector

1. **Interest Points Extraction**
   - Implement the Harris Corner detector.
   - Apply it at a minimum of 4 different scales on `harris.JPG`.
   - Observe and document consistent interest points across scales.

#### Scene Stitching with SIFT/SURF

1. **Feature Matching and Alignment**
   - Use OpenCV's SIFT or SURF to detect interest points.
   - Establish correspondences between images `sl.jpg`, `sm.jpg`, and `sr.jpg`.
   - Discuss results and demonstrate the output for each method.

## Requirements

- Python 3.x
- Jupyter Notebook
- Basic libraries (NumPy, Matplotlib)
