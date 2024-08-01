# Eyes Up: Multimodel Driver Monitoring System Using Deep Learning.

## Overview

A Driver Monitoring System (DMS) is crucial for vehicle safety, assessing driver alertness using image processing, signal processing, and AI to detect drowsiness and distraction in real-time. Our system monitors eye closure, ten types of distractions, and uses voice systems to confirm drowsiness. Additionally, it employs a speaking model to detect if the driver is talking and a chatbot to engage and alert the driver.

## Project Modules

Our project consists of five interdependent modules, each designed to complement and enhance the functionality of the others, creating a cohesive system that addresses specific real-life scenarios effectively:

### 1. Distraction Detection Module
- **Purpose:** Monitor 10 driver distraction postures.
- **Technology Used:** Pre-Trained CNN (InceptionV3) and CNN-BILSTM models, fine-tuned for the task.
- **Accuracy:** 94%

### 2. Drowsiness Detection Module (Camera)
- **Purpose:** Monitor eye closure for signs of drowsiness.
- **Technology Used:** MediaPipe Face Detection and Pre-Trained CNN (InceptionV3 and Resnet50) models, fine-tuned for eye closure monitoring.
- **Accuracy:** 96%
  
### 3. Drowsiness Detection Module (Voice)
- **Purpose:** Detect drowsiness using voice analysis.
- **Technology Used:** MFCC technique for speech recognition and trained RNN and ANN models.
- **Accuracy:** 97%
  
### 4. Speaking Detection Module
- **Purpose:** Detect if the driver is talking.
- **Technology Used:** Trained RNN, ANN, and SVM models.
- **Accuracy:** 83%

### 5. Chatbot
- **Purpose:** Engage and alert the driver to keep them awake.
- **Technology Used:** Prompt engineering with chatbots like ChatterBot, ChatGPT, Llama2-13b, and DialoGPT.
- We chose ChatGPT for its ability to generate diverse and contextually appropriate responses. ChatGPT has enabled personalized interactions by remembering user preferences, integrated system functionalities to recommend and open applications, provided flexible voice option, and supported speech recognition with Google's technology for hands-free interaction.

## System Integration

To implement the system integration, we used two cameras and one microphone, applying threading for simultaneous image capture, allowing real-time drowsiness and distraction detection. The system processes camera frames for distraction detection, monitors eye closure for drowsiness, and uses voice analysis for speaking and drowsiness detection, with a chatbot to alert and engage the driver based on their status, ensuring safety through a flag-based mechanism for accurate and timely actions.

## Web Application

The DMS is integrated into a web applications in which the frontend, developed using Streamlit, focuses on user interface design, layout, and functionality, simplifying the creation of custom web applications for machine learning and data science. While the backend uses a Microsoft Excel file for simplicity, managing data operations like writing user information during signup and retrieving it during login.


## Supervision and Support

- **Supervisors:** Valeo, Eng. Mohamed Saad-Hasanin

## Acknowledgements

We extend our gratitude to Valeo and our supervisors for their invaluable support and guidance throughout this project.

## Project Diagram

![Project Diagram](https://github.com/mariamhanafy02/EyesUp_Multimodal_Driver_Monitoring_System_using_deep_learning/blob/main/gp%20flow.png)

## Project Demo

[Watch the video](https://drive.google.com/file/d/1l5mEC6EDgJrROS4RXr6Xy_kIPO01mzRX/preview)


