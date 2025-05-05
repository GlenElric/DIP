Edge Detection Using OpenCV
Team Members

•	Glen Elric Fernandes
USN: 4SO22CD021

•	Muhammed Zaid Sattar
USN: 4SO22CD033
________________________________________
 Problem Statement
 
Edge detection is a fundamental task in computer vision and image processing. The goal is to identify points in an image where the brightness changes sharply—these points typically correspond to object boundaries. Accurate edge detection serves as a base for applications like object recognition, image segmentation, and scene understanding.
________________________________________
Project Description

This project implements an edge detection system using OpenCV in Python. The system loads an image, applies different edge detection filters such as Sobel, Laplacian, and Canny, and visualizes the results. The project is developed using a Jupyter notebook to allow interactive exploration of techniques and visual output for analysis.
________________________________________
 Techniques Used
 
The following edge detection techniques are implemented:

1.	Grayscale Conversion:
	Converts the image to grayscale for simplified processing.
2.	Gaussian Blur:
	Reduces noise using Gaussian blurring before edge detection.
3.	Sobel Operator:
	Detects edges using gradient magnitude in X and Y directions.

	Useful for directional edge detection.
5.	Laplacian Operator:
	A second-order derivative method that highlights regions of rapid intensity change.
6.	Canny Edge Detection:
	A multi-stage edge detection algorithm known for its accuracy.

	Involves noise reduction, gradient calculation, non-maximum suppression, and hysteresis thresholding.
________________________________________
 Program Flow
1.	Import Libraries:
	Uses OpenCV (cv2) and Matplotlib (matplotlib.pyplot) for image processing and visualization.
2.	Read and Display the Image:
	Load the input image using OpenCV.
3.	Convert Image to Grayscale:
	Simplifies further processing by reducing color complexity.
4.	Apply Gaussian Blur:
	Removes noise which might lead to false edge detection.
5.	Apply Edge Detection Filters:
	Sobel X and Y

	Laplacian

	Canny
7.	Display the Results:
	Plots the output of each method side-by-side for visual comparison.
________________________________________
 How to Run:
1.	Clone the repository:
2.	git clone https://github.com/your-repo-name.git
3.	cd your-repo-name
4.	Install required libraries (preferably in a virtual environment):
5.	pip install opencv-python matplotlib
6.	Launch the Jupyter Notebook:
7.	jupyter notebook 6_edge_detection.ipynb
________________________________________


