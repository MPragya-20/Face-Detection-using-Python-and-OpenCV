# Face-Detection-using-Python-and-OpenCV
First commit-Face detection by Pragya -->

This project comprises of simple face detection in an image using Python and OpenCV.

First import matplotlib,numpy and most importantly OpenCV (cv2). Make sure you have pre-installed OpenCV using pip.
Next read the image from where you would like to detect faces.
Make sure to convert the image file format to RGB, since OpenCV interprets the image file in BGR format.
Then get the Haar Cascade Classifier which is a pre-trained classifier. Here we will use frontal_face classifier(make sure to save the provided XML file in the same project folder you are working in)
Then use detectMultiScale() function to detect the faces (basically the coordinates) and write a loop to draw a rectangle around the detected coordinates of faces.
Fianlly show the image with detected face(note the rectangles drawn with the coordinates to show the detected faces from the image).
