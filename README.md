# Sentry Secure – AI Construction Site Monitoring System

## 📌 Overview
Sentry Secure is an AI-powered construction site monitoring system designed to improve worker safety by detecting safety violations and generating real-time alerts using computer vision and machine learning techniques.

The system uses YOLO-based object detection to identify safety compliance such as helmet usage and unsafe conditions.

---

## ⚙️ Features
- Real-time object detection using YOLO model
- Construction site safety monitoring
- Hazard detection alerts
- Backend API support for inference
- Configurable detection settings

---

## 🧠 Tech Stack
- Python
- YOLO (Object Detection Model)
- OpenCV
- Machine Learning
- Flask / WSGI (Backend)

---

## 📁 Project Structure
- app.py → Main application logic
- train.py → Model training script
- config.py → Configuration settings
- wsgi.py → Server deployment entry point
- yolov8n.pt → Pretrained YOLO model

---

## 🚀 How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
