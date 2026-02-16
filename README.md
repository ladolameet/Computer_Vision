# Computer_Vision

Based on the detailed contents of your repository, here is a complete README file that documents the specific steps and implementation details for each of your computer vision projects.

# Computer Vision Projects Repository

This repository contains a specialised collection of Computer Vision projects, ranging from fundamental image processing to advanced deep learning models for object detection and medical segmentation.

---

## Detailed File Descriptions

### [1. CV_lab_1.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/CV_lab_1.ipynb)

**Focus:** Foundational Image Processing.

* **Key Steps:**
* **Image Acquisition:** Loading images using `cv2.imread()`.
* **Colour Space Conversion:** Converting BGR images to Grayscale and RGB for visualisation.
* **Visualisation:** Using `matplotlib` to display multi-channel and single-channel data.



### [2. CV_lab_2 (1).ipynb](https://www.google.com/search?q=uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/CV_lab_2%2520(1).ipynb)

**Focus:** Deep Learning Classification with VGG16.

* **Key Steps:**
* **Library Setup:** Importing TensorFlow, Keras, and the pre-trained `VGG16` model.
* **Preprocessing:** Using `ImageDataGenerator` for image augmentation and scaling.
* **Model Building:** Utilising pre-trained weights for feature extraction and classification tasks.



### [3. Classical_CV_Pipeline.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d. . .)

**Focus:** End-to-End Traditional Pipeline.

* **Key Steps:**
* **Step 1: Image Acquisition:** Establishing the raw input source.
* **Pipeline Logic:** Covers the standard sequence: Image  Preprocessing,  Feature Detection, and  Classification.



### [4. feature_detectors.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/feature_detectors.ipynb)

**Focus:** Advanced Interest Point Detection.

* **Key Steps:**
* **Multi-scale Harris Corner Detection:** Uses structure tensors, Sobel gradients, and Gaussian filters to identify corners across different scales.
* **FAST (Features from Accelerated Segment Test):** * Implementation of a "quick test" (ML-style acceleration) to reject non-corners early.
* **Non-Maximum Suppression (NMS):** Eliminates redundant detections within a specified radius.
* **Sub-pixel Refinement:** Uses a 2D quadratic fit to improve corner accuracy beyond integer coordinates.





### [5. feature_matching.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/feature_matching.ipynb)

**Focus:** Corresponding Features across Images.

* **Key Steps:**
* **Feature Extraction:** Computes SIFT (float-based) and ORB (binary-based) descriptors.
* **BFMatcher (Brute Force):** Compares descriptors using  norm (SIFT) or Hamming distance (ORB).
* **Lowe's Ratio Test:** Filters out ambiguous matches by ensuring the best match is significantly closer than the second best.



### [6. Semantic_Segmentation_U_Net_.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/Semantic_Segmentation_U_Net_.ipynb)

**Focus:** Medical Image Tumour Detection.

* **Key Steps:**
* **Architecture Definition:** Builds a "Mini U-Net" consisting of custom convolutional blocks (`Conv2D`, ReLU).
* **Input Pipeline:** Processes images to  format and normalise pixel values.
* **Optimisation:** Uses the `Adam` optimiser for precise mask prediction.



### [7. Yolo8.ipynb](uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/Yolo8.ipynb)

**Focus:** Real-time Object Detection.

* **Key Steps:**
* **Stream Acquisition:** Uses `yt-dlp` to download video directly from a YouTube URL.
* **Inference:** Loads the YOLOv8 model and runs detection on the downloaded MP4 stream.
* **Output:** Generates a processed video with bounding boxes and class labels.



### [8. Xerox Task.ipynb](https://www.google.com/search?q=uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/Xerox%2520Task.ipynb)

**Focus:** Lossy vs. Lossless Compression Analysis.

* **Key Steps:**
* **Binarization:** Converts images into binary format using `cv2.threshold`.
* **Statistical Analysis:** Compares structural data between compressed formats to quantify data loss.



### [9. Traffic_monitoring.ipynb](https://www.google.com/search?q=uploaded:ladolameet/computer_vision/Computer_Vision-535d5b4924fa2a6d1bd753bbe9a4566b5d51eace/Traffic%2520monitoring/Traffic_monitoring.ipynb)

**Focus:** Motion and Vehicle Analysis.

* **Key Steps:**
* **Frame Differencing:** Analyses consecutive frames to detect moving vehicles.
* **Background Subtraction:** Isolates foreground objects for tracking flow and density.
