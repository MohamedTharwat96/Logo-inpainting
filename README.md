# Logo-inpainting
This project implements an image inpainting algorithm using the SIFT feature detector and the FLANN based matcher in OpenCV. The algorithm identifies the bounding box of a reference image within an input image, then inpaints that bounding box using the average color of the surrounding pixels.

#  Function
The provided function takes two arguments (input_path, output_path) and thee output is the processed image. 

# Files
*  Notebook.ipynp: Contains the main inpainting function.
*  ref.png: The reference image used to find and inpaint in the input images.
*  input.zip: A directory containing the input images to be processed.

# Output
*  output directory contains all the processed images.

