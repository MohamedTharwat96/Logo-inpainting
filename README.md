# Logo-inpainting
This project implements an image inpainting algorithm using the SIFT feature detector and the FLANN based matcher in OpenCV. The algorithm identifies the bounding box of a reference image within an input image, then inpaints that bounding box using the average color of the surrounding pixels.
# Files
*  Notebook.py: Contains the main inpainting function.
*  ref.png: The reference image used to find and inpaint in the input images.
*  input/: A directory containing the input images to be processed.
*  output/: A directory where the inpainted images will be saved.
