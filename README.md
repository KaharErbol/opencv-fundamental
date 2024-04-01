# opencv-fundamental

This repository is a go-to resource for mastering OpenCV fundamentals, the leading open-source library for computer vision and image processing tasks.

## Content

0. Libraries and Modules
1. Basic Image Manipulation
2. Image Annotation
3. Image Enhancement
4. Accessing the Camera
5. Read and Write Videos
6. Image Filtering and Edge Detection
7. Image Features and Image Alignment
8. Image Stitching and Creating Panoramas
9. High Dynamic Range Imaging (HDR)
10. Object Tracking
11. Face Detection
12. Object Detection
13. Pose Estimation using OpenPose


## Libraries and Modules
`cv2`, `numpy`, `matplotlib.pyplot`, `IPython.display`

In IPython, when using `IPython.display.Image`, the image will be displayed in its actual size by default. Unlike in `Matplotlib`, where you often need to explicitly set the figure size or use specific functions to adjust the size of the displayed image, `IPython.display.Image` will **render** the image in its original dimensions.


`matplotlib.pyplot` is a module within the `Matplotlib` library.`Matplotlib` is a comprehensive library for creating static, animated, and interactive visualizations in Python. It provides a MATLAB-like interface for creating plots, charts, histograms, and other types of visualizations.

The `imshow()` function in Matplotlib's pyplot module does not display images at their real size by default. Instead, it scales the image to fit within the size of the plot area, which may result in the image being displayed larger or smaller than its actual dimensions.

However, you can control the size of the displayed image by adjusting the aspect ratio and the size of the figure.

 NumPy provides support for multi-dimensional arrays (ndarrays), which are used to represent images in OpenCV. These arrays allow for efficient manipulation and processing of image data, such as pixel-wise operations, slicing, and arithmetic operations.
