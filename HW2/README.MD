# Image Processing Exercises - Jupyter Notebook

This repository contains solutions for various image processing exercises done in a Jupyter Notebook, focused on histogram adjustment, noise addition, filtering, and analysis. These exercises are a part of a course project and include implementations of common image processing techniques such as histogram equalization, median filtering, and Gaussian noise filtering.

## Table of Contents

- [Project Overview](#project-overview)
- [Exercises](#exercises)
  - [Contrast Adjustment](#contrast-adjustment)
  - [Histogram Analysis](#histogram-analysis)
  - [Noise Addition and Filtering](#noise-addition-and-filtering)
- [Requirements](#requirements)

## Project Overview

This project focuses on implementing basic image processing algorithms without using specialized libraries for the solutions, except for basic mathematical functions. It includes tasks to adjust contrast, add and filter noise, and analyze images through histogram equalization and filtering.

## Exercises

### Contrast Adjustment

1. **Histogram Calculation**: A program to compute the histogram of a grayscale image, using the "Camera Man" test image.
2. **Histogram Equalization**: A program to perform histogram equalization on a grayscale image and compare it to the original.

### Histogram Analysis

- **Noise Addition**: A program to add salt-and-pepper noise to an image with specified densities (0.05, 0.1, 0.2, and 0.4).
- **Median Filtering**: Filtering out salt-and-pepper noise with different window sizes (3, 5, 7, 9) and determining the best window size for each noise density.

### Noise Addition and Filtering

1. **Gaussian Noise**: Adding Gaussian noise with varying variance and applying average and median filters to restore the image.
2. **First-Order Difference Filters**: Implementing and comparing first-order difference filters in the x-direction on grayscale images.
3. **Custom Filters**: Designing and applying custom filters for smoothing, sharpening, and salt-and-pepper noise removal, and combining these into more complex image processing pipelines.

## Requirements

- Python 3.x
- Jupyter Notebook
- Basic libraries (NumPy, Matplotlib)
