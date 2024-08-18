# Real-Time-QR-Code-and-Barcode-Scanner


Real-Time QR Code and Barcode Scanner with OpenCV and Pyzbar


This project implements a real-time QR code and barcode scanner using OpenCV and the Pyzbar library. The system captures video from a webcam, detects QR codes and barcodes in the video feed, and displays the decoded data directly on the video stream. The detected codes are highlighted with a bounding box, and their decoded information is displayed on the screen.

Features
Real-Time Scanning: Detects and decodes QR codes and barcodes in a live video feed in real-time.
Multiple Code Support: Supports both QR codes and various types of barcodes.
Overlay Information: Displays the decoded data on the video feed alongside the detected codes.
Easy-to-Use: Simple and straightforward implementation that runs directly from the command line.
Requirements
Python 3.x
OpenCV 4.x (opencv-python package)
Pyzbar (pyzbar package)
Installation
To set up this project, follow these steps:

Install Required Python Packages:

Install the necessary Python packages using pip:

bash
Copy code
pip install opencv-python pyzbar numpy
Usage
Run the QR Code and Barcode Scanner:

Execute the Python script to start the real-time scanning:

bash
Copy code
python scanner.py
Quit the Application:

Press q on the keyboard to exit the application and close the video feed.

How It Works
Video Capture: Captures video from the default webcam.
Code Detection: Uses Pyzbar to detect and decode any QR codes or barcodes present in the video frames.
Overlay Information: Draws a bounding box around the detected codes and overlays the decoded information on the video stream.
Display Results: Displays the processed video feed with highlighted codes and their decoded data.
File Descriptions
scanner.py: The main Python script that runs the real-time QR code and barcode scanner using OpenCV and Pyzbar.
Contributing
Contributions to improve the project are welcome. Please fork the repository and submit a pull request with your changes.
