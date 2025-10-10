# 🧠 AI-SurCam: Real-Time Anomaly Detection for Urban Areas

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-orange?logo=ultralytics)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Google-red?logo=google)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Platform](https://img.shields.io/badge/Platform-Windows%20|%20Linux-lightgrey)
![Status](https://img.shields.io/badge/Status-Active-success)

> 🚨 **AI-SurCam** is an intelligent surveillance system that integrates **Face Recognition**, **Object Detection**, and **Pose Estimation** to detect anomalies in real-time and send **automated email alerts** — making urban environments smarter and safer.

---

## 🌟 Key Features

| 🚀 Feature | 🧩 Description |
|-------------|----------------|
| 👤 **Face Recognition** | Detects & identifies known/unknown faces using OpenCV's **LBPH algorithm** |
| 🎯 **Object Detection** | Detects real-world objects via **YOLOv8 (Ultralytics)** in real-time |
| 🧍 **Pose Estimation** | Uses **Google MediaPipe** to analyze human posture and keypoints |
| 📸 **Email Alerts** | Automatically sends an **alert with attached image** for unknown faces |
| 🔢 **Person Tracking** | Assigns **unique IDs** to each detected face and maintains detection history |
| 🧠 **Hybrid AI Model** | Combines multiple vision models for enhanced situational awareness |

---

## 🧠 YOLOv8 Object Detection Results

The YOLOv8 model was trained and evaluated on multi-class datasets. Below is an example of performance visualization — showing **per-class F1-scores**, **bounding box overlay**, and **object distribution**.

<p align="center">
  <img src="images/image_2.png" alt="YOLOv8 Analysis" width="700" style="border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1);">
</p>

---

## 🛠️ Technology Stack

| Category | Technologies |
|-----------|---------------|
| **Programming Language** | ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) |
| **Computer Vision** | ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv) |
| **Object Detection** | ![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-orange?logo=ultralytics) |
| **Pose Estimation** | ![MediaPipe](https://img.shields.io/badge/MediaPipe-Google-red?logo=google) |
| **Machine Learning Backend** | ![PyTorch](https://img.shields.io/badge/PyTorch-1.9%2B-orange?logo=pytorch) |
| **Data Processing** | ![NumPy](https://img.shields.io/badge/NumPy-1.19%2B-blue?logo=numpy) ![Pandas](https://img.shields.io/badge/Pandas-1.2%2B-purple?logo=pandas) |
| **Email & Alerts** | ![SMTP](https://img.shields.io/badge/SMTP-Gmail-lightgrey?logo=gmail) ![dotenv](https://img.shields.io/badge/Dotenv-Env%20Config-green?logo=dotenv) |
| **Reporting & Visualization** | ![ReportLab](https://img.shields.io/badge/ReportLab-3.6%2B-orange?logo=adobeacrobatreader) |
| **Framework** | ![Ultralytics](https://img.shields.io/badge/Ultralytics-AI-blue?logo=ultralytics) |
| **License** | ![MIT](https://img.shields.io/badge/License-MIT-yellow) |

---

## 📹 Real-Time Detection & Tracking

During real-time surveillance, AI-SurCam identifies each face with unique IDs and confidence scores, along with keypoints for pose tracking.

<p align="center">
  <img src="images/image_6.png" alt="Detection Example" width="700" style="border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1);">
</p>

---

## ✉️ Email Alert Example

When an **unknown person** is detected near a **known individual**, the system automatically captures the frame and sends an alert email with an image attachment.

<p align="center">
  <img src="images/image_7.png" alt="Email Alert Example" width="600" style="border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1);">
</p>

---

## ⚙️ Customization

| Parameter           | Default | Description                  |
| ------------------- | ------- | ---------------------------- |
| `confidence < 80`   | 80      | Face recognition sensitivity |
| `elapsed_time > 30` | 30s     | Time before alert trigger    |
| `scaleFactor=1.2`   | 1.2     | Face detection scale         |
| `minNeighbors=5`    | 5       | Face detection accuracy      |

---

## 📸 Sample Outputs

| 🧠 Detection        | 📷 Example                             |
| ------------------- | -------------------------------------- |
| **Face Detection**  | ![Sample Output 1](images/image_8.png) |
| **Pose Estimation** | ![Sample Output 2](images/image_7.png) |

---

## 🏙️ Real-World Use Cases

* 🏠 **Smart Home Security**
* 🏢 **Corporate Building Monitoring**
* 🛒 **Retail Theft Prevention**
* 🚦 **Urban Surveillance Networks**
* 🎟️ **Event Safety & Crowd Management**

---

## 🧩 Future Enhancements

* 🔍 Intruder Behavior Prediction using Deep Learning  
* ☁️ Cloud-based Alert Dashboard (AWS / Firebase)  
* 📱 Mobile App Notification System  
* 🧾 Automated Report Generation (PDF/Heatmap)

---

## 📜 License

This project is licensed under the **MIT License**.  
© 2025 Hariprasath. All rights reserved.
