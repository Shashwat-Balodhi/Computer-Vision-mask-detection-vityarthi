# Face Mask Detection using Computer Vision

## 📌 Problem Statement

In public spaces, ensuring that individuals wear face masks is important for health and safety. Manual monitoring is inefficient and error-prone.

This project aims to automatically detect whether a person is wearing a mask or not using computer vision techniques.

---

## 💡 Solution

This system uses:

* Face detection (OpenCV Haar Cascade)
* CNN-based classification (Mask / No Mask)

The pipeline:

1. Detect faces in an image
2. Extract face region
3. Pass it to trained CNN model
4. Predict Mask / No Mask

---

## 🛠️ Tech Stack

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📁 Project Structure

```
face-mask-detection/
│── notebook/
│── model/
│── sample_images/
│── README.md
│── report.pdf
```

---

## ⚙️ Setup Instructions

1. Clone the repository:

```
git clone https://github.com/Shashwat-Balodhi/Computer-Vision-mask-detection-vityarthi.git
cd face-mask-detection
```

2. Install dependencies:

```
pip install tensorflow opencv-python matplotlib numpy
```

3. Run the notebook:

```
Open mask_detection.ipynb in Jupyter or Colab
```

---

## 🚀 How to Use

1. Run all cells in the notebook
2. Upload an image when prompted
3. The system will:

   * Detect face
   * Predict Mask / No Mask
   * Display result with bounding box

---

## 📊 Features

* Face detection using Haar Cascade
* CNN-based classification
* Confidence-based prediction
* Handles edge cases (no face detected)

---

## ⚠️ Limitations

* Performance depends on training dataset
* Haar Cascade may fail in extreme angles
* Accuracy can improve with larger datasets

---

## 🔮 Future Improvements

* Use YOLO for better detection
* Use MobileNet for higher accuracy
* Real-time webcam integration
* Deployment as web app

---

## 👨‍💻 Author

Shashwat Balodhi

# Face Mask Detection using Computer Vision

## 📌 Problem Statement

In public spaces, ensuring that individuals wear face masks is important for health and safety. Manual monitoring is inefficient and error-prone.

This project aims to automatically detect whether a person is wearing a mask or not using computer vision techniques.

---

## 💡 Solution

This system uses:

* Face detection (OpenCV Haar Cascade)
* CNN-based classification (Mask / No Mask)

The pipeline:

1. Detect faces in an image
2. Extract face region
3. Pass it to trained CNN model
4. Predict Mask / No Mask

---

## 🛠️ Tech Stack

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📁 Project Structure

```
face-mask-detection/
│── notebook/
│── model/
│── sample_images/
│── README.md
│── report.pdf
```

---

## ⚙️ Setup Instructions

1. Clone the repository:

```
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection
```

2. Install dependencies:

```
pip install tensorflow opencv-python matplotlib numpy
```

3. Run the notebook:

```
Open mask_detection.ipynb in Jupyter or Colab
```

---

## 🚀 How to Use

1. Run all cells in the notebook
2. Upload an image when prompted
3. The system will:

   * Detect face
   * Predict Mask / No Mask
   * Display result with bounding box

---

## 📊 Features

* Face detection using Haar Cascade
* CNN-based classification
* Confidence-based prediction
* Handles edge cases (no face detected)

---

## ⚠️ Limitations

* Performance depends on training dataset
* Haar Cascade may fail in extreme angles
* Accuracy can improve with larger datasets

---

## 🔮 Future Improvements

* Use YOLO for better detection
* Use MobileNet for higher accuracy
* Real-time webcam integration
* Deployment as web app

---

## 👨‍💻 Author

Shashwat Balodhi
