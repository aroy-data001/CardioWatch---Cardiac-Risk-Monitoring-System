# IoT-Based Real-Time Health Monitoring and Cardiac Risk Prediction System

An IoT-integrated healthcare monitoring system that combines real-time physiological data collection with Machine Learning to assess cardiovascular risk and support early intervention.

## Overview

Traditional heart disease prediction systems primarily rely on static clinical datasets. Although these models can achieve reasonable prediction performance, they lack continuous monitoring capabilities and cannot directly process incoming physiological data.

This project aims to develop an integrated system that collects physiological parameters through IoT-enabled sensors, processes the incoming data using a Machine Learning model, and generates cardiac risk classifications in real time.

## Objectives

- Develop a Machine Learning model for cardiac risk prediction.
- Integrate IoT sensors for continuous physiological data collection.
- Process incoming sensor readings through a backend system.
- Generate cardiac risk classifications: Low, Medium, and High.
- Develop a real-time dashboard for health monitoring.
- Implement an alert mechanism for abnormal risk levels.

## Proposed Architecture

The system is designed around four major layers:

1. **Sensor Layer:** Collect physiological parameters using wearable sensors and an ESP32 microcontroller.
2. **Processing Layer:** Receive, clean and preprocess incoming sensor data.
3. **Machine Learning Layer:** Apply trained classification models to assess cardiac risk.
4. **Output Layer:** Display real-time health metrics, predictions and alerts through a dashboard.

## Technology Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Model Persistence | Joblib |
| Backend | FastAPI |
| Database | PostgreSQL (planned) |
| IoT Hardware | ESP32 (planned) |
| Sensors | Heart Rate / ECG (planned) |
| Communication | Wi-Fi / HTTP (planned) |
| Dashboard | To be finalized |

## Machine Learning Approach

The initial development phase will focus on training and evaluating supervised Machine Learning models using benchmark cardiovascular datasets.

Models under consideration:

- Logistic Regression
- Random Forest Classifier

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The best-performing model will subsequently be integrated into the real-time prediction pipeline.

## Project Structure

```text
cardiac-risk-monitoring-system/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── src/
│   ├── data/
│   ├── models/
│   ├── preprocessing/
│   └── evaluation/
│
├── tests/
├── models/
├── docs/
│
├── .gitignore
├── requirements.txt
└── README.md
```

## Development Roadmap

- [ ] Dataset collection and exploration
- [ ] Data preprocessing and feature engineering
- [ ] Machine Learning model development
- [ ] Model evaluation and optimization
- [ ] Model serialization
- [ ] FastAPI backend development
- [ ] IoT sensor integration
- [ ] Real-time data processing
- [ ] Dashboard development
- [ ] End-to-end system testing

## Project Team

- **Arkapravo Roy**
- Arghya Saha
- Arkonil Sarkar
- Arnab Ghosh

**Department:** Computer Science and Engineering  
**Institution:** Government College of Engineering and Ceramic Technology, Kolkata

**Project Supervisor:** Dr. Bijoy Kumar Mandal

---

*Status: In Development*

This project is an academic final-year B.Tech project. The proposed system is currently under development; the architecture and features described above represent the intended implementation.