# Open-Set Real-Time Object Detection and Tracking System

## 📌 Overview
This project implements a real-time computer vision system capable of detecting unknown objects (open-set detection) and tracking a user-selected object in live video streams.

The system combines deep learning-based object detection with classical tracking techniques and provides an interactive graphical interface for human-in-the-loop control.

---

## 🚀 Features
- Real-time webcam video processing
- Open-set object detection using YOLOv8
- Snapshot-based object detection
- Manual target selection via GUI
- Real-time object tracking using CSRT tracker
- PyQt5-based interactive user interface

---

## 🧠 Technologies Used
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- PyTorch
- PyQt5
- NumPy

---

## 🔄 System Workflow
1. Capture a snapshot from live video
2. Detect objects using YOLOv8
3. Display detected objects in GUI
4. User selects an object to track
5. Initialize tracker
6. Perform real-time object tracking

---

## 📂 Project Structure
