# Driver-Drowsiness-Detection-System
# 🚗 Driver Drowsiness Detection System

## 📌 Overview

The **Driver Drowsiness Detection System** is a Computer Vision-based project designed to monitor a driver's alertness in real-time using a webcam. The system detects the driver's face and provides a foundation for detecting drowsiness to help prevent road accidents.

---

## 🎯 Objective

* To detect the presence of a driver using face detection
* To build a base system that can be extended for drowsiness detection
* To demonstrate real-time Computer Vision using OpenCV

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy

---

## ⚙️ How It Works

1. The system captures live video using a webcam
2. Each frame is converted to grayscale
3. Haar Cascade Classifier is used to detect faces
4. Detected faces are highlighted with bounding boxes
5. Output is displayed in real-time

---

## ▶️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/drowsiness-detection.git
cd drowsiness-detection
```

### 2. Install Dependencies

```bash
pip install opencv-python numpy
```

### 3. Run the Project

```bash
python drowsiness_detection.py
```

---

## 📂 Project Structure

```
drowsiness-detection/
│
├── drowsiness_detection.py
├── haarcascade_frontalface_default.xml
├── README.md
└── report.pdf
```

---

## 📊 Output

* Real-time webcam feed
* Face detection using rectangles

---

## 🚀 Future Enhancements

* Eye detection using facial landmarks
* Eye Aspect Ratio (EAR) for blink detection
* Alarm system for drowsiness alert
* Deep learning-based detection (CNN)

---

## 📸 Sample Output

(Add your screenshot here)

---

## 👨‍💻 Author

Adityesh Singh

---

## 📄 License

This project is for educational purposes only.

