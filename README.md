# SEC-DIP--Coin-Detection-using-OpenCV-in-Python

## Coin Detection Using OpenCV:

This project detects and counts coins in an image using **Python and OpenCV**. It uses the **Hough Circle Transform** to identify circular coins.

## Technologies Used:

- Python
- OpenCV
- NumPy

## How It Works:

1. Read the input image.
2. Convert the image to grayscale.
3. Apply Gaussian Blur.
4. Detect circles using `cv2.HoughCircles()`.
5. Draw circles around detected coins.
6. Count the detected coins.

## Installation:

```bash
pip install opencv-python numpy
```
## Output:

The program detects and highlights each coin with a circle and displays the total number of detected coins.

# Example:

Coins Detected: 5
Applications
Automatic coin counting
Currency image processing
Digital Image Processing
Computer Vision
## Conclusion:

This project demonstrates the use of OpenCV and Hough Circle Transform for automatic coin detection and counting. It is a simple and effective application of Digital Image Processing.
