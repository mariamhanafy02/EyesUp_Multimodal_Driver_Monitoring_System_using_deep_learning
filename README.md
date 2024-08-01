# EyesUp_Multimodal_Driver_Monitoring_System_using_deep_learning
DMS utilizes image processing, signal processing, and AI to detect driver drowsiness and distraction real-time . The system includes a chatbot that alerts the driver and helps keep them awake by engaging in conversations about their interests.
# Eyes Up: Driver Monitoring System Using Deep Learning and Chatbot

## Overview

A Driver Monitoring System (DMS) is crucial for vehicle safety, assessing driver alertness using image processing, signal processing, and AI to detect drowsiness and distraction in real-time. Our system monitors eye closure, ten types of distractions, and uses voice systems to confirm drowsiness. Additionally, it employs a speaking model to detect if the driver is talking and a chatbot to engage and alert the driver.

## Project Modules

Our project consists of five modules, each addressing specific real-life scenarios:

### 1. Distraction Detection Module
- **Purpose:** Monitor 10 driver distraction postures.
- **Technology Used:** Pre-Trained CNN (InceptionV3) and CNN-BILSTM models, fine-tuned for the task.

### 2. Drowsiness Detection Module (Camera)
- **Purpose:** Monitor eye closure for signs of drowsiness.
- **Technology Used:** MediaPipe Face Detection and Pre-Trained CNN (InceptionV3 and Resnet50) models, fine-tuned for eye closure monitoring.

### 3. Drowsiness Detection Module (Voice)
- **Purpose:** Detect drowsiness using voice analysis.
- **Technology Used:** MFCC technique for speech recognition and trained RNN and ANN models.

### 4. Speaking Detection Module
- **Purpose:** Detect if the driver is talking.
- **Technology Used:** Trained RNN, ANN, and SVM models.

### 5. Chatbot
- **Purpose:** Engage and alert the driver to keep them awake.
- **Technology Used:** Prompt engineering with chatbots like ChatterBot, ChatGPT, Llama2-13b, and DialoGPT.

## System Integration

The modules integrate seamlessly, using camera detection for distractions and drowsiness, and voice models to ensure driver alertness. The system can initiate conversations via ChatGPT to keep the driver awake, rechecking drowsiness with voice models or alerting through simple engines.

## Supervision and Support

- **Supervisors:** Valeo, Eng. Mohamed Saad-Hasanin

## Acknowledgements

We extend our gratitude to Valeo and our supervisors for their invaluable support and guidance throughout this project.

---

This README provides an overview of the project and the key modules that contribute to the Driver Monitoring System. For more detailed information, please refer to the documentation provided with each module.
