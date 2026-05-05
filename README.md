# Face-Mask-Detection-System
Real-time safety monitoring powered by AI

**Overview**
The Face Mask Detection System is an AI-powered object detection project designed to improve safety compliance in industrial environments. It automatically detects whether individuals are wearing masks properly using real-time image and video processing.


**The system classifies faces into three categories:**

✅ With Mask

❌ Without Mask

⚠️ Improper Mask


**Objective**

1. Develop a real-time mask detection system for safety monitoring

2. Accurately classify mask usage (proper, improper, none)

3. Enable automated detection to reduce manual supervision

4. Improve workplace safety and compliance


**Features**

🎥 Real-time detection using webcam/video streams

🧠 Multiple object detection models (YOLOv8, Faster R-CNN, SSD)

📦 Bounding box detection with confidence scores

⚡ Fast and accurate classification

📊 Visualization of detection results


**Tech Stack**

**Programming Language:** Python

1. **Models:** YOLOv8, Faster R-CNN, SSD

2. **Libraries:** OpenCV, NumPy, Pandas, Matplotlib

**Dataset**

1. **Source:** Kaggle Face Mask Detection Dataset

2. **Annotations:** XML (converted to YOLO format)

3. **Classes:** With Mask, Without Mask, Improper Mask


**How It Works**

1. Input image or video stream is captured

2. Object detection model identifies faces

3. Model classifies mask status

4. Bounding boxes with confidence scores are displayed

5. Output is shown in real-time


**Output**

1. Detects multiple faces in real-time

2. Displays bounding boxes

3. Shows mask classification with confidence score
