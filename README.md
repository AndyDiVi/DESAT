
# DESAT – Solar Image Desaturation

![alt text](image-1.png)

## Overview

This project focuses on the reconstruction of saturated regions in solar images acquired by the Atmospheric Imaging Assembly (AIA) aboard the Solar Dynamics Observatory (SDO).

The objective is to recover information lost due to sensor saturation and blooming effects.

## Methodology

The DESAT algorithm is implemented using MATLAB and consists of the following main steps:

1. Identification of the saturation region.
2. Detection of diffraction fringes.
3. Estimation of the primary saturation region using correlation analysis.
4. Reconstruction of the saturated signal using the Expectation Maximization (EM) algorithm.
5. Image synthesis and desaturation.

## Technologies

- MATLAB
- Numerical methods
- Expectation Maximization
- Image processing

## Documentation

The complete theoretical explanation, mathematical formulation, MATLAB implementation and experimental results are available in:

[Desatv15.pdf](Desatv15.pdf)

## Authors

Beardo – Caviglia – Di Via
