Real-Time Road Object Detection System
A real-time object detection system built using YOLOv8 and OpenCV to detect vehicles, pedestrians, and traffic-related objects from live video input.
Designed with real-time inference and performance monitoring, simulating a lightweight AI dashcam pipeline.
 Features
Real-time object detection using YOLOv8

Bounding boxes with confidence scores

Live FPS counter for performance monitoring

Webcam-based inference pipeline

Lightweight model (yolov8n) for edge-style deployment

🛠️ Tech Stack
Python
OpenCV
Ultralytics YOLOv8
NumPy
▶️ How to Run
git clone https://github.com/yourusername/road-object-detection.git
cd road-object-detection
then create vistual environment
python -m venv venv
venv\Scripts\activate   # Windows
install dependencies
pip install ultralytics opencv-python
then
python main.py
And press Q to exit screen
