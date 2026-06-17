# 🚀 ASTROTWIN – Digital Twin Health Monitoring System

ASTROTWIN is an AI-powered astronaut health monitoring system that creates a digital twin of astronauts using physiological and behavioral data. The system combines webcam-based health monitoring, wearable sensor data, machine learning models, and predictive analytics to continuously track astronaut health during long-duration space missions. It can detect health drifts, forecast future risks, and generate early alerts before critical conditions occur.

## 📹 Features

* Real-time astronaut health monitoring
* Webcam-based face detection using OpenCV
* Remote heart rate estimation using rPPG
* Smartwatch/wearable sensor integration
* Digital Twin visualization of astronaut health
* Behavioral drift detection and analysis
* AI-based health risk prediction
* 30-day health forecasting
* Predictive alert generation
* Interactive health dashboard using Streamlit

## 🛠️ Tech Stack

* Python
* Streamlit
* OpenCV
* NumPy
* Pandas
* Plotly
* TensorFlow / Keras
* CNN, LSTM, Transformer Models
* Computer Vision (Face Detection)
* rPPG Signal Processing

## 🖥️ How to Run

1. Clone or download the repository
2. Install required dependencies:

pip install -r requirements.txt

3. Run the application:

streamlit run app.py

4. Open the generated local URL in your browser
5. Enable webcam access for face detection
6. Select an astronaut profile and monitor health data in real time

## ⚙️ System Workflow

1. Capture video and wearable sensor data
2. Detect face using OpenCV
3. Extract physiological signals (rPPG)
4. Generate health parameters
5. Analyze data using AI models
6. Detect behavioral drifts
7. Forecast future health risks
8. Update Digital Twin
9. Display results and alerts on dashboard

## 📊 Monitored Parameters

* Heart Rate (HR)
* Blood Pressure (BP)
* SpO₂
* Respiration Rate
* Core Temperature
* Stress Index
* Sleep Quality
* Fatigue Risk
* Cognitive Performance

## 🤖 AI Models Used

### CNN

* Health pattern recognition
* Feature extraction

### LSTM

* Time-series health forecasting
* Trend prediction

### Transformer

* Long-term dependency learning
* Advanced health prediction

## 🔔 Alert System

### Critical Alerts

* Immediate health risks
* Severe physiological deviations

### Warning Alerts

* Moderate health abnormalities
* Emerging health concerns

### Preventive Alerts

* Future risk predictions
* Early intervention recommendations

## 📌 Note

This project currently uses simulated physiological signals and wearable data for demonstration purposes. The architecture is designed to support integration with real wearable devices, medical sensors, and advanced rPPG signal processing systems in future deployments.

## 🔗 Project Status

✅ Completed and Tested

✅ Real-Time Dashboard Implemented

✅ AI Model Training Integrated

✅ Digital Twin Visualization Implemented

🚀 Ready for Demonstration and Further Development
