# IOT-AI-Powered-Diagnosis-and-Treatment-Recommendation-Engine
This repository contains the backend intelligence layer for the IoT-AI Powered Healthcare Network System. Currently in its initial development phase, the system focuses on leveraging Machine Learning (ML) models to provide automated healthcare support by predicting diseases and suggesting treatments based on patient symptoms and vitals.

## 🚀 Project Overview
The global healthcare landscape is under immense pressure due to rising costs and a shortage of medical professionals. This project aims to bridge the gap by providing 24/7 automated healthcare support through intelligent decision assistance.

## Current Focus (Phase 1 & 2)
* AI-Based Diagnosis: Developing an engine that predicts possible diseases from patient data, including symptoms, vitals, and medical history.
* Treatment Recommendation: Designing a system that suggests personalized, evidence-based treatment plans.
* Core Algorithms: Currently utilizing robust Machine Learning models such as Linear Regression, Support Vector Classification (SVC), and ensemble methods for high accuracy.
   
## 🏗️ System Architecture
The system works as a backend intelligence layer that processes data from IoT devices or manual input.
1. Patient Data: Captures real-time physiological data through IoT sensors.
2. Preprocessing: Cleans data using k-NN imputation and normalizes vitals via Min-Max scaling.
3. Engine Processing: Analyzes symptoms and vitals to predict diseases and suggest optimal treatments.
4. Feedback Loop: Incorporates doctor validations (Accept/Modify/Reject) to improve model accuracy over time.

## 🛠️ Technology Stack (Current Phase)
Tools/Technologies: Python(numpy,pandas,matplotlib), scikit-learn, MYSql, Flask/FastAPI, GitHub.

## 📅 Roadmap & Evolution
* Current (Phase 2): Implementation of baseline ML models (SVC, Linear Regression, Random Forest) and data preprocessing pipelines.
* Future (Phase 3): Integration of Advanced Deep Learning (CNN/RNN) for time-series vital sign analysis.
* Future (Phase 4): Integration of the LLM Reasoning Layer and Retrieval-Augmented Generation (RAG) to provide natural language explanations.

## ⚖️ Ethical Considerations
* Data Privacy: All patient data is anonymized and handled in compliance with HIPAA and GDPR principles.
* Human-in-the-Loop: The system is designed as a Decision Support Tool for medical professionals, not a replacement for them.
* Accountability: Final clinical decisions and accountability remain with the human doctor.

## 👥 Contributors (MCA 3rd Sem 2025)
1. Sandeep Tomar (TL)(2400680140107)
2. Abhishek Som (2400680140005)
3. Tanya Chaudhary (2400680140131)
4. Shekhar Tomar (2400680140114)
5. Sandhya Kashyap (2400680140108)
* Supervisor: Dr. Brijesh Kr. Gupta Ph.D. (IIT-R) Prof.
Institution: Meerut Institute of Engineering & Technology (MIET), Meerut.
