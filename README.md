
# 👥 Real-Time Vision-Based Crowd Risk Detection System

> AI-powered real-time crowd monitoring, forecasting, and automated emergency response system for safety-critical environments.

<img width="942" height="387" alt="image" src="https://github.com/user-attachments/assets/14a861a9-2831-42de-a53b-875c632fa3b6" />

---

## 📌 Overview

This project is a **real-time computer vision system** designed to:

* Detect and count people using **YOLOv8**
* Classify crowd density risk levels
* Forecast future crowd growth using **Facebook Prophet**
* Automatically trigger **Telegram + Email + Voice Alerts**
* Visualize live crowd hotspots using interactive heatmaps
* Maintain historical event logs for analysis

It demonstrates a **scalable AI deployment pipeline** for smart city and public safety applications.

---

## 🔍 Real-Time Detection

<img width="380" height="397" alt="image" src="https://github.com/user-attachments/assets/4f9b600f-873e-4e60-bfe1-89d379fa04d4" />

---


## 🌡 Heatmap Visualization

<img width="392" height="358" alt="image" src="https://github.com/user-attachments/assets/4ba40cef-e71c-4f19-8f7f-005c42e943c0" />

---

## 🚨 Emergency Alert System

<img width="401" height="155" alt="image" src="https://github.com/user-attachments/assets/ef69171e-895c-4ba5-b2fd-1bac172ff57d" />

---

# 🚀 Key Features

## 🧠 Computer Vision

* YOLOv8-based people detection
* Bounding box visualization
* Confidence-based filtering

## 📊 Predictive Risk Forecasting

* Prophet time-series modeling
* Adjustable forecast horizon (10–60 minutes)
* Early warning system

## 🚨 Automated Emergency Response

* Telegram Bot notifications
* Gmail SMTP alerts
* Voice evacuation announcements (gTTS)
* SOS protocol trigger

## 🗺 Crowd Flow & Hotspot Monitoring

* Interactive Mapbox heatmaps
* Risk color classification
* Event-level tracking

## 🗂 Event Logging System

* JSON-based structured storage
* Historical trend analysis
* Alert history dashboard

---

# 🏗 System Architecture

(Add architecture diagram image here)

<img width="503" height="364" alt="image" src="https://github.com/user-attachments/assets/0bf4f7f0-4b99-4d80-9fbb-fbd747a116e8" />

Architecture Flow:

```
Camera/Image Input
        ↓
YOLOv8 Detection
        ↓
Risk Classification
        ↓
Prophet Forecasting
        ↓
Alert Engine (Telegram + Email + Voice)
        ↓
Heatmap + Dashboard Visualization
```

---

# 🛠 Tech Stack

| Layer         | Technology                       |
| ------------- | -------------------------------- |
| Vision        | YOLOv8 (Ultralytics)             |
| Forecasting   | Prophet                          |
| Backend Logic | Python                           |
| UI            | Streamlit                        |
| Visualization | Plotly + Mapbox                  |
| Notifications | Telegram API + Gmail SMTP        |
| Data Storage  | JSON                             |
| Deployment    | Streamlit / Local / Docker-ready |

---

# ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/real-time-crowd-risk-detection.git
cd real-time-crowd-risk-detection
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Setup Environment Variables

Create `.env` file:

```
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
TELEGRAM_TOKEN=your_bot_token
TELEGRAM_CHAT_ID=your_chat_id
```

---

### 4️⃣ Run App

```bash
streamlit run app.py
```

---

# 📈 Performance Metrics

Based on trained YOLOv8 model:

* mAP@50: **0.90**
* Precision: **94.3%**
* Recall: **~88%**
* Overall Accuracy: **~90%**

Forecasting:

* 60-minute ahead prediction window
* Early-warning alert threshold logic

---

# 🌍 Applications

* Smart City Surveillance
* Stadium Crowd Monitoring
* Religious Gatherings
* Railway Stations
* Metro Hubs
* Public Protests
* Event Management
* Disaster Prevention Systems

---

# 🔐 Ethical Considerations

* No facial recognition
* No personal identity tracking
* Density-based analysis only
* Privacy-preserving crowd intelligence

---

# 🔮 Future Enhancements

* Multi-camera support
* CCTV video pipeline
* Edge device deployment (Jetson Nano)
* Docker containerization
* Cloud deployment (AWS / Azure)
* Real-time API backend using FastAPI
* Multi-class crowd behavior analysis

---

# 👨‍💻 Author

Sachin Navi
B.Tech – AI & ML
Real-Time AI Systems & Computer Vision Developer

---

# 📜 License

MIT License

---
