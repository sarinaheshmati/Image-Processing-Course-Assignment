# Image Processing Course - Assignment 5

This repository contains solutions to the fifth assignment of the Image Processing course.

## Concepts Covered

- **Point Intensity Transformations**: Understanding point-wise image processing techniques for enhancing image quality, including adjustments to brightness, contrast, and color correction. These transformations help in improving the visual appeal and detail of images by manipulating pixel intensities.
  
- **Contrast Enhancement**: Techniques for improving image contrast, such as using linear transformation functions to widen the range of intensity values, resulting in clearer and more detailed images.

- **Logarithmic Intensity Transformation**: Applying logarithmic transformations to emphasize details in darker regions of an image, enhancing visibility where intensity values are low. This method is particularly useful for images where details are hidden in shadows.

- **Histogram Stretching and Equalization**: Techniques like histogram stretching to expand the intensity range, improving contrast, and histogram equalization to evenly distribute intensity levels across the image, leading to better overall contrast.

- **Image Filtering and Mask Application**: Implementing custom filtering operations on images using masks (kernels), comparing pixel values before and after applying filters, and ensuring the adaptability of filtering functions to various image types and filters.

- **Mean Filtering**: Implementing and applying a mean filter to reduce noise in images, using kernels of different sizes (e.g., 3x3 and 3x4). Mean filtering smooths the image but may reduce fine details.

- **Sobel Edge Detection**: Implementing the Sobel filter for edge detection, a crucial step in identifying edges and gradients in images. The Sobel filter uses convolution with horizontal and vertical kernels to detect edges effectively, especially in scenarios with gradual intensity changes.

## Requirements

- Python
- OpenCV
- NumPy
- Matplotlib

