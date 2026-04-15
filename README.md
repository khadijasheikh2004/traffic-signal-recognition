# Traffic Signal Recognition using Computer Vision (OpenCV)

## Overview
This project implements a computer vision-based system to recognize traffic signal states (Red, Yellow, Green) from real-world images.

The system processes images one by one, detects dominant color regions using HSV color space, and classifies the traffic light state accordingly.

---

## Problem Statement
Punjab Safe City aims to develop an automated traffic signal recognition system using computer vision.

This project captures real images of traffic signals and classifies their state (Red, Yellow, Green) using image processing techniques.

---

## Why I Built This
I built this project to:
- Apply computer vision techniques to a real-world problem
- Understand color-based object detection
- Work with HSV color space for robust color segmentation
- Build a simple traffic signal recognition system

---

## Methodology

1. Image Input:
   - Images are loaded from a folder

2. Preprocessing:
   - Resize images for consistency
   - Convert from BGR to HSV color space

3. Color Detection:
   - Apply thresholding for:
     - Red
     - Yellow
     - Green

4. Classification:
   - Count number of pixels for each color mask
   - Select the color with the highest count

5. Output:
   - Display image with predicted traffic signal label

---

## Key Concepts Used
- OpenCV image processing
- HSV color space
- Color thresholding
- Pixel-wise masking
- Basic classification logic

---

## Tech Stack
- Python
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib

---

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Open Jupyter Notebook:
jupyter notebook

3. Run:
traffic_signal_recognition.ipynb

4. Upload or place your own traffic light images inside an `images/` folder

5. Run all cells to:
- Process images
- Detect signal color
- Display labeled outputs

---

## Input
- Folder: `images/`
- Contains traffic signal images (.jpg format)

Users can upload their own images of traffic lights for testing.

---

## Output
- Each image is displayed with a predicted label:
  - RED
  - YELLOW
  - GREEN
