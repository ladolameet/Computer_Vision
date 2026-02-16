Here is a professional **README.md** file for your **Traffic Monitoring System – Classical Computer Vision Project** based on your notebook and video outputs.

---

# 🚦 Traffic Monitoring System – Classical Computer Vision Project


## 📌 Project Overview

This system analyzes a traffic video and performs:

* ✅ Moving vehicle detection
* ✅ Vehicle counting
* ✅ Lane monitoring
* ✅ Traffic congestion detection
* ✅ Real-time video annotation
* ✅ Processed video output generation

It is built for **educational purposes** to understand classical computer vision techniques.

---

## 🎥 Sample Files Included

* `traffic.mp4` → Input traffic video
* `output.mp4` → Processed output video
* `Traffic_monitoring.ipynb` → Main notebook implementation

---

## 🧠 Techniques Used

### 1️⃣ Background Subtraction

* MOG2
* KNN

Used to separate moving vehicles from static background.

### 2️⃣ Optical Flow

* Lucas-Kanade (Sparse Optical Flow)
* Farneback (Dense Optical Flow)

Used to track vehicle motion.

### 3️⃣ Contour Detection

* Bounding box generation
* Area filtering
* Noise removal

### 4️⃣ Vehicle Counting Logic

* Virtual counting line
* Object centroid tracking
* Entry/exit detection

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV
* NumPy
* Google Colab (for execution)

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-link>
cd traffic-monitoring
```

### 2️⃣ Install Dependencies

```bash
pip install opencv-python numpy
```

If using Jupyter/Colab:

```bash
pip install opencv-python-headless
```

---

## ▶️ How to Run

### Option 1: Run in Jupyter Notebook

Open:

```
Traffic_monitoring.ipynb
```

Run all cells.

---



---

## 📊 Output

The system produces:

* Real-time annotated video
* Vehicle count display
* Congestion alert (if threshold exceeded)
* Output video file: `output.mp4`

---

## 📈 Features

* ✔ Real-time FPS display
* ✔ Vehicle bounding boxes
* ✔ Total vehicle counter
* ✔ Traffic congestion indicator
* ✔ Video saving capability

---

