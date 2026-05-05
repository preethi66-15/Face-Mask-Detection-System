# Face-Mask-Detection-System
Real-time safety monitoring powered by AI

**Overview**
The Face Mask Detection System is an AI-powered object detection project designed to improve safety compliance in industrial environments. It automatically detects whether individuals are wearing masks properly using real-time image and video processing.

**The system classifies faces into three categories:**

✅ With Mask

❌ Without Mask

⚠️ Improper Mask

**Objective**

Develop a real-time mask detection system for safety monitoring

Accurately classify mask usage (proper, improper, none)

Enable automated detection to reduce manual supervision

Improve workplace safety and compliance

**Features**

🎥 Real-time detection using webcam/video streams

🧠 Multiple object detection models (YOLOv8, Faster R-CNN, SSD)

📦 Bounding box detection with confidence scores

⚡ Fast and accurate classification

📊 Visualization of detection results

**Tech Stack**

**Programming Language:** Python

**Models:** YOLOv8, Faster R-CNN, SSD

**Libraries:** OpenCV, NumPy, Pandas, Matplotlib

**Dataset**

**Source:** Kaggle Face Mask Detection Dataset

**Annotations:** XML (converted to YOLO format)

**Classes:** With Mask, Without Mask, Improper Mask

**How It Works**

Input image or video stream is captured

Object detection model identifies faces

Model classifies mask status

Bounding boxes with confidence scores are displayed

Output is shown in real-time

**Output**

Detects multiple faces in real-time

Displays bounding boxes

Shows mask classification with confidence score
