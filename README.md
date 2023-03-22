# Automatic Number Plate Recognition using YOLOv8

A real-time automatic number plate recognition (ANPR) system built with Python, YOLOv8 and EasyOCR. This project detects vehicles, locates license plates, and extracts plate text from video footage.

## Features

- Vehicle detection using YOLOv8 pretrained model
- License plate detection using a custom-trained YOLOv8 model
- OCR-based license plate text extraction using EasyOCR
- Vehicle tracking with SORT algorithm
- Missing data interpolation for smoother results
- Result visualization on video frames

## Models

- **Vehicle Detection**: YOLOv8 pretrained model (`yolov8n.pt`)
- **License Plate Detection**: Custom YOLOv8 model trained on a license plate dataset

## Dependencies

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository
2. Install dependencies
3. Run the main script:

```bash
python main.py
```

## Tech Stack

- Python
- YOLOv8 (Ultralytics)
- EasyOCR
- OpenCV
- SORT (Simple Online and Realtime Tracking)

## Author

**Jatin Chourasiya** — [GitHub](https://github.com/J3-84Ya-Work)
