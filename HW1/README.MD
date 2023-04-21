# Image Fundamentals Exercises

This repository contains solutions to a set of exercises focused on image processing fundamentals, including quantization, interpolation, and point processing. The exercises were designed as part of a learning module to deepen understanding of image manipulation techniques and error measurement.

## Table of Contents

- [Overview](#overview)
- [Exercises](#exercises)
  - [1. Quantization & Interpolation](#1-quantization--interpolation)
  - [2. Point Processing](#2-point-processing)
- [Requirements](#requirements)

## Overview

These exercises aim to explore:

- Image quantization at different levels (4, 8, 64, 128).
- Image manipulation using different bit depths (1, 2, 4, 6 bits).
- Point processing techniques, including darkening, lightening, contrast adjustments, and inversion.

> **Note**: The use of external libraries for solving problems is restricted to basic mathematical functions. Libraries for higher-level image processing are not allowed as per the assignment requirements.

## Exercises

### 1. Quantization & Interpolation

#### 1.1 Displaying Quantized Images

- Quantize the grayscale version of the Lena image at 4, 8, 64, and 128 levels.
- Calculate and display the optimum mean square error for each quantization level.

#### 1.2 Bit Depth Reduction

- Generate new grayscale images using bit depths of 1, 2, 4, and 6.
- Compare the results by computing the mean square error.

### 2. Point Processing

#### 2.1 Image Manipulation

- Create new images from the grayscale Lena image by applying the following transformations:
  - Darkening
  - Lightening
  - Lowering contrast
  - Increasing contrast
  - Inverting colors

## Requirements

- **Python** 3.x
- Basic Python libraries (NumPy, Matplotlib for visualization)
- No advanced image processing libraries (as per guidelines)
- Jupyter Notebook
