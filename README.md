
# Real-Time Object Detection 🚀
This project demonstrates real-time object detection using the YOLOv8 model. It can detect and classify objects from images, video files, or webcam streams in real time.

## ✨ Features

🎥 Real-time detection from webcam/video feed

🖼️ Object detection in images with bounding boxes & labels

⚡ Powered by YOLOv8 (fast + accurate)

🖥️ Easy to run locally with Python

☁️ Ready for deployment with render.yaml


## ⚙️ Installation

### 1. Clone the repository

```bash
    git clone https://github.com/sujith232/SmartVision.git
    cd RealTimeObjectDetection

```
### 2. Create a virtual environment (optional but recommended)
```bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
```
### 3.Install dependencies
```bash
    pip install -r requirements.txt
```
## 🚀 Usage
### Run locally
```
    python app.py
```

#### * For image input, update <image_path> in app.py.
#### * For video/webcam, set the source:
```
    source = 0  # Webcam
    source = "video.mp4"  # Video file
```

## 🧠 Model Details
* Default: YOLOv8 Nano (yolov8n.pt)

* Trained on: COCO dataset (80 classes)

* Replaceable with other YOLOv8 models (yolov8s.pt, yolov8m.pt, etc.)

## ☁️ Deployment
This project includes render.yaml for Render deployment.

Steps:

* Push repo to GitHub

* Connect to Render

* Deploy using wsgi.py

## 📜 License
Licensed under the MIT License.


