# 🧠 PrismVision – AI Object Detection GUI (YOLOv8 + PyQt5)

A desktop application for real-time object detection using your webcam, powered by YOLOv8, OpenCV, PyQt5, and text-to-speech audio feedback. 

---

## ✨ Features

- **Live webcam feed with object detection** (YOLOv8)
- **Confidence threshold adjustment** with clickable buttons to fine-tune predictions  
- **Text-to-speech audio announcements** for detected objects using gTTS and pygame  
- **Simple PyQt5 GUI**: View bounding boxes, labels, and confidence scores in an intuitive window 
- **No cloud required**: Runs entirely on your local machine with your own webcam

---

## 🚀 Quick Start

1. Clone the repository
   -git clone https://github.com/rivu-intel45/Vision-Prism.git cd prismvision
2. (Optional) Create and activate a virtual environment
   -python -m venv venv
   -source venv/bin/activate # On Windows: venv\Scripts\activate
3. Install dependencies
   -pip install -r requirements.txt
4. Run the app


---

## 🖥 How It Works

- Captures frames from your webcam using OpenCV.  
- Runs YOLOv8 on each frame to detect objects and draw colored bounding boxes.  
- Displays detections in a PyQt5 window with live labels and confidence scores.  
- Announces detected objects aloud through gTTS and pygame when requested.   

---

## 🎛 Controls

- **Announce**: Speak out the objects currently detected above the confidence threshold.   
- **Increase Confidence**: Raise the detection confidence threshold (up to 0.95).   
- **Decrease Confidence**: Lower the detection confidence threshold (down to 0.05).   
- **Quit**: Close the GUI, release the webcam, and stop audio. 

---

## 📦 Technologies Used

- YOLOv8 (Ultralytics) for object detection 
- OpenCV for webcam capture and drawing bounding boxes   
- PyQt5 for the desktop GUI 
- gTTS and pygame for text-to-speech audio playback  
- Python 3 for the overall application logic  
