
# DESAT – Solar Image Desaturation

[Desat.pdf](https://github.com/user-attachments/files/34769977/Desat.pdf)
<img width="1199" height="733" alt="image" src="https://github.com/user-attachments/assets/aedd4a86-c08b-4075-b233-52ae696593b6" />


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
[Desat.pdf](https://github.com/user-attachments/files/34769982/Desat.pdf)


## Authors

Beardo – Caviglia – Di Via
