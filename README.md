# Motion Detection & Car Counting  
**Computer Vision Project using OpenCV**  

This project uses computer vision techniques to detect and track vehicles in traffic video footage. It applies background subtraction and contour-based detection to estimate the number of moving cars and their flow rate.

## About

### Project Goal  
To build a Python-based video analysis system that automatically detects and counts cars moving through a defined region of interest in traffic surveillance footage.

## Key Features  
- **Background Subtraction**: Uses `cv2.createBackgroundSubtractorMOG2()` to extract moving objects from static scenes  
- **Morphological Operations**: Cleans up noise using OpenCV operations  
- **Contour Detection**: Identifies moving objects based on contour area and aspect ratio  
- **Non-Max Suppression**: Reduces overlapping bounding boxes for more accurate vehicle tracking  
- **Car Counting**: Increments counter only when objects cross a defined line and aren't duplicates  
- **Rate Calculation**: Outputs the number of cars per minute using frame rate and duration

Link -> https://bydakid.com/car/car
