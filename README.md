# License-plate-detection
This project is a Vehicle License Plate Detection system that can automatically detect and read license plates from images or videos.
# Vehicle License Plate Detection and Recognition

## Description
This project is a **Vehicle License Plate Detection and Recognition system** that automatically detects and reads license plates from images or videos. It combines **object detection** and **optical character recognition (OCR)** to locate license plates and extract text accurately.

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
