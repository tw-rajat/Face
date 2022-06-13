### Introduction

Object identification and face detection are probably the most popular applications of computer vision. This technology finds applications in various industries, such as security and social media. So, we’re building a face detection project through Python. 


### Objective
 
### Requirements

	Hardware
•	Hard Disk:		40GB or Above
•	RAM:			4GB
•	Processor:		Dual Core
•	System type:		64-bit OS 
•	Interface:		PC with an in-built webcam or external webcam

	Software
•	OS:		Windows 10 or Linux
•	IDE:		VS Code or PyCharm



### Technology Used

Prerequisites for this project:
•	Python – 3.8 or above
•	OpenCV – 4.5

Python:
Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991.It supports multiple programming paradigms, including structured (particularly, procedural), object-oriented, and functional programming.

OpenCV:
OpenCV is a computer vision framework that helps you do all sorts of processing on images and videos.
Since its release, it’s been a widely used tool for image processing tasks. It enables you to manipulate pixels easily, so that you can build your own image and video processing algorithms if you wish to do so. 

### Steps for Face Detection

Step #1: Install Libraries
First, you should install the required libraries, OpenCV. You can install it easily through:
pip install opencv-contrib-python 

Step #2: Detect Faces
Now, you must configure your camera and connect it to your system. The camera should work properly to avoid any issues in face detection.
Before our camera recognizes us, it first has to detect faces. We’ll use the Haar Cascade classifier for face detection. It is primarily an object detection method where you train a cascade function through negative and positive images, after which it becomes able to detect objects in other photos. 
In our case, we want our model to detect faces. OpenCV comes with a trainer and a detector, so using the Haar Cascade classifier is relatively more comfortable with this library. You can create your classifier to detect other images as well.  

### Conclusion

In this Face Detection Project, we’ve built a face detector using OpenCV in Python. We’ve used the Haar Cascade classifier in OpenCV framework for the detection. Here we’ve learned about the frame capture and some common image processing techniques.

In future we would like to improve the accuracy further and add things like recognitions of faces to implement more functions.
