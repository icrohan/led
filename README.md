# led
1️⃣ Install Required Dependencies for OpenCV and Hand Tracking
Run the following commands in your Python environment:

sh
Copy
Edit
pip install opencv-python
pip install mediapipe
pip install pyserial

4️⃣ Verify Installation
Run this script to check if OpenCV, MediaPipe, and Serial are correctly installed:

python
Copy
Edit
import cv2
import mediapipe as mp
import serial

print("OpenCV Version:", cv2.__version__)
print("MediaPipe Imported Successfully")
print("PySerial Imported Successfully")
If no errors appear, you’re ready to go! 🚀
