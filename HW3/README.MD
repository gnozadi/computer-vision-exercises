# Image Processing in Frequency and Wavelet Domains

This repository contains solutions for image processing exercises focused on Fourier and wavelet transforms. Implemented in Jupyter Notebook, these exercises include tasks such as computing Fourier transforms, applying filters in the frequency domain, and building pyramids and wavelet transformations.

## Table of Contents

- [Project Overview](#project-overview)
- [Exercises](#exercises)
  - [Frequency Domain Analysis](#frequency-domain-analysis)
  - [Wavelet Transform](#wavelet-transform)
- [Requirements](#requirements)

## Project Overview

This project aims to explore image processing in both frequency and wavelet domains by implementing fundamental techniques without using specialized libraries, except for basic mathematical functions. The exercises involve computing Fourier transforms, creating frequency filters, and building wavelet pyramids.

## Exercises

### Frequency Domain Analysis

1. **Fourier Transform**:

   - Compute the Fourier transform of various filters and illustrate their magnitude and phase response, testing on the grayscale Lena image.
   - Perform 2D DFT on grayscale Lena, Barbara, and Baboon images and display the DFT magnitude with and without shifting and logarithmic scaling. Discuss the results.

2. **Filtering**:
   - Filter the grayscale Barbara image by zeroing out certain DFT coefficients, with specific regions based on threshold values (\( T = 1/2, 1/4, 1/8 \)). Display and compare the original and filtered images.

### Wavelet Transform

1. **Pyramid Construction**:

   - For the Barbara image, build a 5-level Gaussian and Laplacian pyramid and display them in pyramid format.
   - For the Lena image, compute a 3-level approximation pyramid with a prediction residual pyramid using a 3x3 averaging filter and pixel replication.

2. **Wavelet Decomposition and Reconstruction**:
   - Compute a 5-level wavelet transform on the Lena image using Haar analysis filters.
   - Quantize the wavelet coefficients (using a step size \( \gamma = 2 \)) and reconstruct the image with Haar synthesis filters. Calculate and report PSNR values for the reconstructed image.

## Requirements

- Python 3.x
- Jupyter Notebook
- Basic libraries (NumPy, Matplotlib)
- Optional libraries for wavelet and Fourier transformations if needed
