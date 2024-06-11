# Face Recognition

This Python code uses OpenCV to detect and compare faces from two images. 
It begins by importing the OpenCV library and loading a pre-trained Haar Cascade classifier for face detection. 
Two images are loaded in grayscale. The classifier is then used to detect faces in these images, extracting the face regions. 
The detected face regions are resized to the same dimensions to facilitate comparison. The pixel-wise mean squared error (MSE) between the two face images is calculated. 
A threshold is set to determine if the faces match, and a label indicating whether the faces match or not is printed based on the MSE value. 
Finally, the original images with rectangles around the detected faces and the extracted face regions are displayed.
