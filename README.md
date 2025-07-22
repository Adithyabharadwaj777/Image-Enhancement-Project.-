# MATLAB Image Enhancement using Denoising and Histogram Equalization

This project enhances a grayscale image by first denoising it using median filtering, then applying histogram equalization to improve contrast. It also computes and displays useful image statistics.


##  Features

- Converts color image to grayscale
- Removes noise using **median filtering**
- Enhances contrast using **histogram equalization**
- Displays:
  - Original, Denoised, and Enhanced images
  - Histograms of each
  - Statistics: Mean, Std Dev, Min, Max
- Measures and displays execution time for each step


##  Requirements

- MATLAB (any version that supports `medfilt2`, `histeq`, etc.)
- Image Processing Toolbox

##  How It Works

1. **Read & Convert**: Loads color image → grayscale.
2. **Denoising**: Uses `medfilt2()` to reduce salt-and-pepper noise.
3. **Enhancement**: Uses `histeq()` to stretch contrast.
4. **Display & Stats**: Plots and console output.





