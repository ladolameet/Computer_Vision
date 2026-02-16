# 📦 Box & Packet Detection and Counting System

A Computer Vision-based video analysis system that detects and counts boxes/packets passing through a defined region in a video stream.

This project uses **YOLO object detection + OpenCV tracking** to monitor objects in real-time and calculate total counts.

---

## 🚀 Features

* 🎯 Real-time object detection using YOLO
* 📹 Video input support (.mp4)
* 📊 Live counting of boxes/packets
* 🧠 Region-based line crossing logic
* 🖥️ Processed output video generation
* ⚡ Optimized for Google Colab execution

---

## 📁 Project Structure

```
├── Video_analysis.ipynb      # Main notebook (Detection + Counting logic)
├── amazon_video.mp4          # Input video
├── final_output.mp4          # Output processed video
├── README.md                 # Project documentation
```

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV
* YOLO (Ultralytics)
* NumPy
* Google Colab

---


---

## ▶️ How to Run

### Step 1: Open Notebook

Open `Video_analysis.ipynb` in:

* Jupyter Notebook
  OR
* Google Colab

### Step 2: Upload Input Video

Upload your video file (example: `amazon_video.mp4`).

### Step 3: Run All Cells

The notebook will:

* Load YOLO model
* Process each frame
* Detect objects
* Track and count crossings
* Generate `final_output.mp4`

---

## 🧠 How It Works

1. **Frame Extraction**

   * Video is read frame-by-frame using OpenCV.

2. **Object Detection**

   * YOLO model detects objects like boxes/packets.

3. **Tracking Logic**

   * Each object is assigned an ID.
   * When it crosses a predefined line/region, count increases.

4. **Visualization**

   * Bounding boxes drawn on objects.
   * Total count displayed on frame.
   * Output video saved.

---

## 📊 Output

* Annotated video with:

  * Bounding boxes
  * Object labels
  * Total count display
* Saved as: `final_output.mp4`

---

## 🧩 Customization

You can modify:

* Detection confidence threshold
* Counting line position
* Target object classes
* Video input source (camera/video file)

Example:

```python
model = YOLO("yolov8n.pt")
results = model(frame, conf=0.5)
```

---

## ❗ Common Issues & Fixes

### ❌ cv2.imshow() not working in Colab

Use:

```python
from google.colab.patches import cv2_imshow
```

### ❌ Backend connection error in Colab

* Restart runtime
* Check internet
* Ensure GPU runtime is enabled

### ❌ Count not updating

* Verify crossing line logic
* Ensure unique tracking IDs
* Check bounding box center calculations

---

## 📈 Future Improvements

* DeepSORT tracking for better accuracy
* Multi-class counting
* Web dashboard (Streamlit/FastAPI)
* Real-time camera integration
* CSV export of count data

---

Just tell me 👍
