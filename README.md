# AI Intruder Detection System

This project implements an AI-based surveillance system that detects potential intruders from CCTV footage using computer vision techniques.

The system analyzes video frames to identify individuals, verify authorized personnel, and detect suspicious behaviors.

---

## Features

- Person detection from video frames
- Face recognition for identifying registered employees
- Uniform verification using color analysis
- Pose estimation for detecting suspicious behaviors
- Intruder classification

---

## Computer Vision Pipeline

1. Person detection using YOLOv8
2. Face recognition using InsightFace
3. Uniform color verification
4. Pose estimation using MediaPipe
5. Intruder detection decision

---

## Notebook

The full implementation is available in the Jupyter Notebook:

`Intruder_Detection_System.ipynb`

---

## Run on Google Colab

You can open and run the notebook directly on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18RpGh4vzkmBRvodA6DDIEWv0a9esm53D?usp=sharing)

---

## Technologies

- Python
- PyTorch
- OpenCV
- YOLOv8
- InsightFace
- MediaPipe
- NumPy

---

## Use Cases

- Smart CCTV monitoring
- Workplace security systems
- Automated surveillance
