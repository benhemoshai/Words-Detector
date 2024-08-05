# Word Detection in Newspaper Articles

This project aims to detect different words in a newspaper article using morphology operators and connected components.

## Overview

The project processes a newspaper article image to detect and highlight individual words. It involves several key steps such as converting the image to grayscale, binarizing it, applying morphological operations, and identifying connected components to detect words.
<img width="432" alt="image" src="https://github.com/user-attachments/assets/1152e7b7-dd2e-4efd-9731-d9c00c824538">

## Installation

To run this project, you need to have Python installed along with several libraries. You can install the required libraries using pip:
pip install numpy matplotlib opencv-python

## Usage

1.Load and display the image.
2.Convert the image to binary.
3.Apply morphological operations.
4.Find and highlight words.

## Methodology

Grayscale Conversion: The original image is converted to a grayscale image. 
Binarization: The grayscale image is converted to a binary image using a threshold value. 
Morphological Operations: The image is split into headline and text regions, and morphological operations (opening) are applied with different kernels to each part. 
Connected Components: The processed image is analyzed to find connected components, which represent individual words. 
Highlight Words: Each connected component is highlighted by drawing rectangles around them. 
