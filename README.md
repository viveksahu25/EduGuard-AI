# EduGuard-AI

An AI-based student proctoring system for detecting suspicious exam behavior using telemetry data, rolling features, and machine learning.

## 📌 Project Overview

EduGuard-AI is a machine learning-based student proctoring project designed to analyze exam-related telemetry and system event data. The system uses behavioral and sensor-related information to identify potentially suspicious activity during an examination.

## 🎯 Objective

The main objective of this project is to develop a data-driven system that can:

- Analyze student telemetry data
- Detect suspicious examination behavior
- Reduce false alarms caused by short-duration sensor fluctuations
- Use rolling-window features to create more stable predictions
- Evaluate different classification thresholds
- Provide high-confidence suspicious activity flags for human review

## 📂 Project Structure

```text
EduGuard-AI/
│
├── AI_Student_code.ipynb
├── Project_Statement.pdf
├── README.md
│
└── Data/
    ├── video_telemetry.csv
    └── system_events.csv
