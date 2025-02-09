# OpenCV Prerequisites and Setup

## 1. Introduction
OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning library. This guide outlines the prerequisites and installation steps required to set up OpenCV.

## 2. Prerequisites
### Programming Knowledge
- Basic knowledge of **Python** or **C++**.
- Understanding of fundamental programming concepts (loops, functions, data structures).

### Required Python Libraries
Ensure you have the following libraries installed:
- **NumPy** (for numerical computations)
- **Matplotlib** (for visualization)
- **Pandas** (optional, for handling datasets)

Install them using:
```bash
pip install numpy matplotlib pandas
```

### OpenCV Installation
To install OpenCV, use:
```bash
pip install opencv-python
```
For OpenCV with extra modules:
```bash
pip install opencv-contrib-python
```

## 3. Image Processing Basics
Understanding the following concepts is recommended:
- Pixels and image formats (JPEG, PNG, BMP, etc.).
- Color spaces (RGB, BGR, grayscale).
- Image transformations (scaling, rotation, thresholding).

## 4. Mathematical Foundations (Helpful but Optional)
- Linear algebra (matrix operations, transformations).
- Probability and statistics (useful for ML and vision tasks).

## 5. Computer Vision Basics
Familiarity with:
- Edge detection (Canny, Sobel, Laplacian).
- Feature extraction (SIFT, ORB, HOG).
- Contour detection and shape analysis.

## 6. Machine Learning & Deep Learning (Optional)
For ML/DL applications in OpenCV, install:
```bash
pip install tensorflow keras torch torchvision
```
Familiarity with deep learning frameworks like TensorFlow or PyTorch is beneficial.

## 7. Getting Started
To verify the installation, run the following Python code:
```python
import cv2
print(cv2.__version__)
```
If OpenCV is installed correctly, it should print the version number.

## 8. Reposiroty Code Links

| Index | Program Name | Description |
|-------|--------------|-------------|
| 1     | [Display image](https://github.com/ananthu-m-01/opencv-basics/blob/main/image-processing/display-image.ipynb) | This script reads an image using OpenCV, displays it in its original BGR format, converts it to RGB, and then displays the converted image using Matplotlib and comparing the pixel values in BGR and RGB. |
| 2     | [Splitting into 3 channel ](https://github.com/ananthu-m-01/opencv-basics/blob/main/image-processing/splitting-image.ipynb) | This script reads an image and splitting into 3 different channel using cv2. split() anad displaying each images such as red, blue and gree channel images |
| 3     | [Merged images ](https://github.com/ananthu-m-01/opencv-basics/blob/main/image-processing/merge-images.ipynb) | This script focus of merge the image according with various channel and produce the alternative combinations |

## 9. Conclusion
With these prerequisites and installations, you are now ready to start working with OpenCV. 🚀
