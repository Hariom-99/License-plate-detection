# Vehicle License Plate Detection and Recognition

![Python](https://img.shields.io/badge/Python-3.12-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8-brightgreen)
![EasyOCR](https://img.shields.io/badge/EasyOCR-1.6-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Colab](https://img.shields.io/badge/Google_Colab-Notebook-orange)

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="30" height="30"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" alt="OpenCV" width="30" height="30"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="30" height="30"/>

---

## Description
This project is a **Vehicle License Plate Detection and Recognition system** that automatically detects and reads license plates from images or videos. It combines **object detection** (YOLOv8/ANPR) and **optical character recognition (OCR)** to locate license plates and extract text accurately.

It can be used for applications such as **traffic monitoring, parking management, toll collection, and security systems**.

---

## Features
- **Automatic Detection:** Detects license plates using a pre-trained YOLOv8/ANPR model.
- **Text Recognition:** Extracts license plate numbers using EasyOCR or Plate Recognizer API.
- **Video Processing:** Processes videos frame by frame with annotated outputs.
- **Secure API Handling:** API keys can be stored securely using environment variables or Colab Secrets.
- **Output Options:** Annotated images/videos with bounding boxes and detected plate numbers; optional CSV log for tracking detected plates.

---

## Technologies Used
- **Python** – Programming language
- **OpenCV** – Image and video processing
- **YOLOv8 / ANPR Model** – License plate detection
- **EasyOCR / Plate Recognizer API** – Text recognition
- **Google Colab** – Development and testing environment

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/vehicle-license-plate-detection.git
cd vehicle-license-plate-detection
