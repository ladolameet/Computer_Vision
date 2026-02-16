# Computer_Vision

---

# 📌 **Computer Vision Projects Repository**

This repository collects various computer vision notebooks that you’ve worked on — ranging from basic image processing and classical vision techniques to deep learning models like U-Net and YOLOv8.

Below is a **full README** with a breakdown of each file and what you’ve implemented in them.
The descriptions are structured so someone new to your repository can understand each notebook’s purpose and key tasks.

---

## 📁 **1. CV_lab_1.ipynb**

**🔍 Focus:** Foundational Image Processing Concepts
**What You Did:**

* Loaded images using OpenCV (`cv2.imread()`)
* Converted between color spaces (BGR → RGB, Grayscale)
* Visualized different channels using Matplotlib
* Explored pixel-level operations and basic display functions

**Key Takeaways:**
This notebook introduces how images are structured (channels vs grayscale), how to load and view images, and how to use basic OpenCV + Matplotlib visualization.

---

## 📁 **2. CV_lab_2 (1).ipynb**

**🔍 Focus:** Deep Learning Image Classification with VGG16
**What You Did:**

* Imported TensorFlow and Keras
* Loaded the pretrained VGG16 model
* Built an image classification training pipeline
* Used `ImageDataGenerator` for data augmentation (scaling, flipping)
* Trained and evaluated the model’s performance

**Key Takeaways:**
This notebook shows how to use transfer learning to classify images by leveraging powerful pretrained ConvNet features.

---

## 📁 **3. Classical Face Decation.ipynb**

**🔍 Focus:** Classical Face Detection Techniques
**What You Did:**
*(Based on filename — not included in the existing README but inferred from repo)*

* Applied traditional face cascades (like Haar or LBP)
* Detected faces without deep learning
* Visualized bounding boxes on detected faces

**Key Takeaways:**
This notebook focuses on old-school computer vision methods for face detection using cascade classifiers.

---

## 📁 **4. Classical_CV_Pipeline.ipynb**

**🔍 Focus:** Traditional End-to-End Computer Vision Pipeline
**What You Did:**

* Built a full pipeline from image load → preprocess → feature extraction
* Covered image filtering, morphology, and shape extraction
* Object classification based on features

**Key Takeaways:**
A broader, structured overview of classical computer vision workflows without deep learning models.

---

## 📁 **5. feature_detectors.ipynb**

**🔍 Focus:** Detecting Keypoints Using Multiple Algorithms
**What You Did:**

* Multi-scale Harris Corner Detection (detecting interest points)
* Implemented FAST (Features from Accelerated Segment Test)
* Applied Non-Maximum Suppression (NMS) to refine corners
* Sub-pixel refinement for more accurate point locations

**Key Takeaways:**
Shows how to compute image features and refine them for reliable landmark detection.

---

## 📁 **6. feature_matching.ipynb**

**🔍 Focus:** Matching Features Between Images
**What You Did:**

* Extracted SIFT descriptors (float features)
* Extracted ORB descriptors (binary features)
* Used BFMatcher for brute-force matching
* Employed Lowe’s ratio test to filter good matches

**Key Takeaways:**
This notebook demonstrates matching across images and evaluating corresponding keypoints.

---

## 📁 **7. Semantic_Segmentation_U_Net_.ipynb**

**🔍 Focus:** Semantic Segmentation (U-Net)
**What You Did:**

* Built a U-Net architecture from scratch using TensorFlow/Keras
* Designed downsampling and upsampling blocks
* Prepared and normalized input images and masks
* Trained for pixel-wise classification on medical images (tumor segmentation)
* Evaluated model performance

**Key Takeaways:**
You implemented a deep segmentation network to predict masks over medical images.

---

## 📁 **8. Yolo8.ipynb**

**🔍 Focus:** Real-Time Object Detection Using YOLOv8
**What You Did:**

* Used `yt-dlp` to download YouTube videos
* Loaded the YOLOv8 pretrained model
* Ran object detection on frames
* Drew bounding boxes + class labels on detected objects
* Exported a processed result video

**Key Takeaways:**
Practical YOLO usage for video processing and real-world object detection.

---

## 📁 **9. Xerox Task.ipynb**

**🔍 Focus:** Image Compression Comparison (Lossy vs Lossless)
**What You Did:**

* Converted images to binary format
* Performed thresholding to separate foreground from background
* Compared compressed (lossy) and original (lossless) data
* Analyzed structural differences between formats

**Key Takeaways:**
Explores effects of compression and visual quality loss quantitatively.

---

## 📁 **10. Traffic_monitoring.ipynb**

**🔍 Focus:** Monitoring Moving Objects (Traffic)
**What You Did:**

* Used frame differencing to detect moving vehicles
* Applied background subtraction
* Tracked motion flow and vehicle density
* Visualized traffic activity in video sequences

**Key Takeaways:**
Classical motion analysis for traffic monitoring and object flow detection.

---
