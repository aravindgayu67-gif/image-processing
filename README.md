# image-processing
This project demonstrates a complete image processing pipeline using OpenCV and NumPy. It performs point detection, edge detection, and line detection on an input image using multiple techniques in both grayscale and RGB formats.
🔍 Features
📷 Load and display an image
⚫ Convert image to grayscale and apply Gaussian blur
📌 Point Detection using Laplacian (Grayscale & RGB)
📏 Edge Detection using:
Prewitt Operator
Sobel Operator
📐 Line Detection using:
Canny Edge Detection
Hough Transform
⚙️ Techniques Used
Laplacian Operator – Detects sharp intensity changes (points)
Prewitt Operator – Basic edge detection using gradients
Sobel Operator – Improved edge detection with noise reduction
Canny Edge Detector – Accurate edge detection
Hough Transform – Detects straight lines in images
🧠 Workflow
Input Image
Grayscale Conversion
Noise Removal (Gaussian Blur)
Point Detection (Laplacian)
Edge Detection (Prewitt & Sobel)
Line Detection (Canny + Hough Transform)
🎯 Output
The program displays:
Original Image
Grayscale & Blurred Image
Point Detection Results
Edge Detection Results (Prewitt & Sobel)
Detected Lines on Image
🚀 Use Cases
Computer Vision Projects
Object Boundary Detection
Lane Detection Systems
Image Analysis Tasks
