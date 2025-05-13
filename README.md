# AI-Wildlife-Detection-and-Geolocation-based-Alert-System

This project implements an **AI-driven wildlife monitoring system** designed to detect and classify animal species in real-time using **YOLOv8**. The system was developed using the **NTLNP dataset**, which includes over **2,000 annotated images** of wild animals (e.g., *Amur tiger, wild boar*), domestic animals (e.g., *cow, dog*), and humans — captured during both **day and night**.


## 🚀 Key Features

- ### 🎯 Object Detection with YOLOv8
  Achieved **91% training accuracy** and **95% validation accuracy** across **17 animal and human classes** using a lightweight YOLOv8 model.

- ### 📊 Interactive Dashboard
  Built with **React** and **Python (Flask/FastAPI)** backend, enabling:
  - Real-time detection logs
  - Visual analytics of species statistics
  - Manual image upload & detection interface

- ### 🗺️ Geolocation and Smart Alerts
  - Integrated **Leaflet.js** for live map-based visualization of wildlife detections
  - Real-time **Twilio SMS alerts** triggered when wildlife is detected near vulnerable zones


## 🌍 Purpose

This system aims to address **human-wildlife conflict** by enabling real-time, location-aware wildlife detection and automated alerting. The solution offers practical applications in:
- **Wildlife conservation**
- **Rural and agricultural safety**
- **Smart surveillance in protected zones**


## 📷 Dataset

The model is trained on the **NTLNP (Northeast Tiger and Leopard National Park)** dataset:
- 2,000+ annotated images
- 17 classes including wild animals, domestic animals, and humans
- Separated by **day/night conditions** for improved temporal robustness


## 🛠️ Technologies Used

- **YOLOv8** – Object detection
- **React.js** – Frontend dashboard
- **Python (Flask/FastAPI)** – Backend inference & API
- **Leaflet.js** – Map-based detection visualization
- **Twilio API** – SMS alert integration
- **Ultralytics YOLO** – Training & evaluation framework

