# 🚀 Real-Time Object Detection using OpenCV & MobileNet SSD

A computer vision project that performs real-time object detection using the MobileNet SSD deep learning model and OpenCV. The system can detect multiple objects in an image and display bounding boxes with class labels and confidence scores.

---

## 📌 Project Overview

This project demonstrates how pre-trained deep learning models can be used for object detection without training a custom model.

Using OpenCV's DNN module together with the MobileNet SSD model, the application detects common everyday objects from images.

---

## ✨ Features

- 📷 Image Object Detection
- 🎯 MobileNet SSD Deep Learning Model
- 📦 OpenCV DNN Module
- 🏷️ Object Labels
- 📍 Bounding Boxes
- 📊 Confidence Scores
- 🖼️ Annotated Output Image
- ⚡ Fast and Lightweight

---

## 🛠 Technologies Used

- Python
- OpenCV
- NumPy
- Google Colab
- MobileNet SSD
- Deep Learning

---

## 📂 Project Structure

```
Object-Detection/
│
├── Project4_Object_Detection.ipynb
├── requirements.txt
├── final_annotated_output.jpg
├── README.md
└── models/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/object-detection-opencv.git
```

Move to project folder

```bash
cd object-detection-opencv
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

```
opencv-python
numpy
```

---

## 🔍 How It Works

1. Load the pre-trained MobileNet SSD model.
2. Read the input image.
3. Create a blob using OpenCV.
4. Perform forward propagation.
5. Detect objects.
6. Draw bounding boxes.
7. Display confidence scores.
8. Save the annotated output image.

---

## 📸 Sample Output

The detected objects are highlighted with:

- Bounding Boxes
- Object Labels
- Confidence Percentage

Example Output:

```
Person (98%)
Chair (94%)
Bottle (91%)
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Computer Vision
- Deep Learning Inference
- OpenCV DNN Module
- Image Processing
- Object Detection
- Python Programming

---

## 🚀 Future Improvements

- Real-time Webcam Detection
- YOLOv8 Integration
- Video Object Detection
- Object Tracking
- Streamlit Web App
- Flask API Deployment

---

## 👨‍💻 Author

**Muhammad Talha**

AI & Computer Vision Developer

---

## 📄 License

This project is developed for educational purposes, as a part of AI InternShip .

---

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub.
