# 🖥️ Lab 10 — Computer Vision with YOLOv8 & OpenCV

A hands-on computer vision lab exploring real-world detection and analysis use cases using **YOLOv8 (Ultralytics)** and **OpenCV**.

---

## 📌 Use Cases Covered

| # | Application | Techniques Used |
|---|-------------|-----------------|
| 1 | 🏫 Smart Classroom Attendance | YOLOv8 person detection, Haar Cascade face detection |
| 2 | 🚗 Smart Parking Lot Monitor | YOLOv8 vehicle detection, Canny edge detection, license plate localization |
| 3 | 🐘 Wildlife Conservation Tracking | YOLOv8 multi-animal detection across species |
| 4 | 🏭 Industrial Defect Detection | YOLOv8 + contour-based anomaly detection |

---

## 🛠️ Tech Stack

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) — object detection model
- [OpenCV](https://opencv.org/) — image processing & computer vision
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) — license plate text extraction
- [Matplotlib](https://matplotlib.org/) — visualization
- [Pillow](https://python-pillow.org/) & [NumPy](https://numpy.org/) — image utilities

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/cv-lab10-yolov8-opencv.git
cd cv-lab10-yolov8-opencv
```

### 2. Install dependencies
```bash
pip install ultralytics opencv-python-headless matplotlib pillow requests pytesseract scikit-image
```

> For Tesseract OCR (license plate text extraction):
> ```bash
> sudo apt-get install tesseract-ocr
> ```

### 3. Run the notebook
Open `Lab_10_CV.ipynb` in Jupyter or Google Colab and run all cells.

---

## 📂 Project Structure
