# Academic Attendance System: *AI-Based Signature and Absence Detection*

<p align="left">
  <img src="https://github.com/user-attachments/assets/95158053-8b7c-4f5f-99f8-9932755f595f" width="170" height="320" alt="Login">
  <img src="https://github.com/user-attachments/assets/0c686179-8cce-4af0-97e1-de55986b23e5" width="170" height="320" alt="Add Course">
  <img src="https://github.com/user-attachments/assets/c4913801-f71e-49eb-9828-0ccd52a7f565" width="170" height="320" alt="Capture Sheet">
  <img src="https://github.com/user-attachments/assets/0a53b7d5-057b-495f-a479-8a602b0825e8" width="170" height="320" alt="View Attendance">
  <img src="https://github.com/user-attachments/assets/3cb2a3e5-a391-47bf-9150-088338367124" width="170" height="320" alt="Statistics 1">
  <img src="https://github.com/user-attachments/assets/7cfe22e9-e15d-4644-9a2d-6fad28eed7e4" width="170" height="320" alt="Statistics 2">
  <img src="https://github.com/user-attachments/assets/5b1f9a3b-4c04-4263-a21c-71a53dbd7c38" width="170" height="320" alt="Signature Grouping">
  <img src="https://github.com/user-attachments/assets/5bed6930-89cd-44c8-af81-26fd76137319" width="170" height="320" alt="Logout">

## Overview
This project introduces an AI-powered mobile application for automating academic attendance. Developed by a two-person team, it offers efficient management of attendance sheets by recognizing signatures, detecting fraudulent entries, and tracking student absences. The system enhances the accuracy of attendance records and significantly reduces the workload of instructors.

## Project Description
This system leverages machine learning techniques and image processing tools to digitize and validate attendance records from physical sheets. Key processes include signature comparison using neural networks and automated tracking of students' attendance data. It is designed for seamless integration with both Android and iOS platforms, ensuring a broad reach and user-friendly experience for academic professionals.

### Objectives
1. **Signature Recognition and Fraud Detection:** Uses CNN and SNN models to match signatures and identify inconsistencies.
2. **Automated Absence Tracking:** Captures attendance from scanned sheets and records student absences in real time.
3. **User Notifications:** Notifies students who approach or exceed absence limits.
4. **Cross-Platform Compatibility:** Supports both Android and iOS devices through React Native.

## Features
- **AI-Powered Signature Matching:** Automates the detection of fraudulent signatures.
- **Automated Attendance Processing:** Simplifies tracking and storing absence data.
- **Notifications:** Alerts students and instructors about attendance updates.
- **Cloud Database Integration:** Utilizes MongoDB for efficient data management.
- **User-Friendly Interface:** Easy upload of attendance sheets with real-time feedback.

## Technologies
- **Frontend:** React Native, Expo
- **Backend:** Flask API for image analysis and processing
- **Machine Learning Models:** CNN, SNN implemented with TensorFlow and Keras
- **Database:** MongoDB for secure storage of attendance records
- **Image Processing Libraries:** OpenCV, NumPy for preprocessing and feature extraction
- **Visualization Tools:** Matplotlib, Seaborn

## System Requirements
- **Operating Systems:** Android 8.0+ / iOS 11+
- **RAM:** Minimum 2 GB (Recommended 4 GB)
- **Camera:** At least 8 MP for optimal image capture
- **Storage:** 4 GB minimum, 8 GB recommended

## How It Works
1. **Attendance Sheet Upload:** Instructors upload a photo of the attendance sheet via the app.
2. **Signature Matching:** The system analyzes and compares signatures using pre-trained models.
3. **Absence Calculation:** Absences are automatically tracked and updated in the database.
4. **Notifications:** Alerts are sent to students with critical absence records, and detailed reports are available for instructors.

## Contributors
- Büşra Güral
- Emir Oğuz
