# Image Filtering

## Image as a function
We can think of a (grayscale) image as a function, f, from R^2 to R:
- f(x, y) gives the intensity at position (x, y)
- A digital image is a discrete (sampled, quantized) version of this function.#

## Image transformations
- As with any function, we can apply operators to an image

## Image filtering
- Form a new image whose pixels are certain statistics of the original pixels.
- Modify the pixels in an image based on some function of a local neighborhood of
each pixel.

Reason?
To get useful information from images
- Extract edges or contours (to understand shape)
- Preprocess image to detect corners or features
To enhance the image
- Remove or reduce noise
- Sharpen and “enhance image”
A key operator in Convolutional Neural Networks

## Summary
- Image: definition and representation
- Sliding window: cross-correlation and convolution
- Linear filtering: box and Gaussian filter, sharpening
- Non-linear filtering: median filtering, thresholding