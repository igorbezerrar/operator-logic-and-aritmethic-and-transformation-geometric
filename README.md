
# Operator logic and aritmethic and Transformation Geometric

This script is an activity from a computer vision course that applies some image operations, such as negative transformation, gamma correction, logarithm operator, and exponential operator. The code reads three images, an image in JPEG format, a PNG image, and a JPEG image, and performs the operations mentioned above.

## Libraries
This code uses some libraries to work with images and to plot the results. The libraries are:

- numpy
- pandas
- cv2 (OpenCV)
- matplotlib

## Operations
The code applies four different image operations to the input images. These are:

- Negative Transformation: Inverts the color of each pixel of the image, creating a "negative" of the image.
- Gamma Correction: Changes the intensity levels of the image by applying a non-linear transformation to the input pixels. This method can increase or decrease the intensity of the image.
- Logarithm Operator: Enhances the contrast of low-intensity pixels while compressing the high-intensity pixels.
- Exponential Operator: Opposite of the logarithm operator, enhances the contrast of high-intensity pixels while compressing the low-intensity pixels.


## Running the code
To run this code, you can copy it and paste it into a Python environment or run it directly on Google Colab. This code requires the input images to be in the same directory as the script.

After running the script, it will plot the original images and the processed images side by side for comparison.

## Autores

- [@igorbezerrar](https://www.github.com/igorbezerrar)

