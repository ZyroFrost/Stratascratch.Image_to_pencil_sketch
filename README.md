# Image to Pencil Sketch
## Description
This project requires converting a colored image into a pencil sketch image using the OpenCV library with Python.<br>
The project has some tips:
1. Convert the RGB image to grayscale - this will turn the image into a classic black-and-white photo.
2. Invert the grayscale image - this is sometimes referred to as a negative image and can be used to enhance details.
3. Mix the grayscale image with the inverted blurry image - this can be done by dividing the pixel values of the grayscale image by the pixel values of the inverted blurry image; the result should resemble a pencil sketch.
4. Experiment by applying other transformations offered by the OpenCV library to improve the effect.
## Steps Involved
1. Open the image.
2. Convert to grayscale.
3. Apply a Gaussian blur to the grayscale image.
4. Create sketch effect using division.
5. Save the output sketched image.
6. Display the image.
## Libraries Used
OpenCV (cv2)<br>
Matplotlib (matplotlib.pyplot)
## Output result
Sketched image saved as sketch_image.jpg<br>
The image is shown in JupyterLab.
