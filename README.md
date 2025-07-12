# 🚗 License Plate Recognition System

![Python](https://img.shields.io/badge/python-3.8%2B-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv)
![Tesseract](https://img.shields.io/badge/Tesseract-OCR-yellow?logo=google)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

This project is a Python-based License Plate Recognition System that detects and extracts vehicle license plate numbers from images using **OpenCV** and **Tesseract OCR**.

## 👥 Team Members

- **Ankit Choudhary** (21BAI10409)  
- **Kaviya Lakshmi** (21BAI10314)  
- **R.J. Thanaraman** (21BAI10162)  
- **Sneha Chakraborty** (21BAI10204)

## 🎯 Objective

To recognize license plates from vehicle images even in challenging conditions like low light or shadows, and extract their alphanumeric content using image processing and OCR.

## 🛠️ Tech Stack

| Tool         | Purpose                       |
|--------------|-------------------------------|
| Python 3     | Core programming language     |
| OpenCV       | Image processing & detection  |
| Pytesseract  | OCR engine for text extraction |
| Pandas       | Data logging (CSV)            |
| Imutils      | Image manipulation helper     |

## 📁 Project Structure

```
📦 License-Plate-Recognition
├── src/
│   └── license_plate_recognition.py
├── docs/
│   └── TEAM_15_PROJECT_REPORT.pdf
├── README.md
└── .gitignore
```

## ⚙️ How It Works

1. Loads an input image (`filename.jpg`)
2. Preprocesses the image (grayscale, filtering, edge detection)
3. Finds contours to detect a likely license plate region
4. Extracts the plate portion using masks
5. Runs OCR via Tesseract to get the text
6. Saves the result and timestamp to `data.csv`

## 💻 Installation

### 🔧 Requirements

- Python 3.8+
- Tesseract OCR (Install: [Tesseract GitHub](https://github.com/tesseract-ocr/tesseract))

### 📦 Python Libraries

```bash
pip install opencv-python pytesseract imutils pandas
```

## 🚦 Use Cases

- Automated Toll Collection
- Parking Access Control
- Smart Traffic Management
- Law Enforcement & Surveillance


## 📘 License

This project is intended for educational and academic use.

## 🙌 Special Thanks

Thanks to the faculty and mentors of our academic institution for guidance and support throughout the project.
