# 🌱 CropDoctor Platform

CropDoctor is an end-to-end AI-powered plant disease diagnosis platform integrating a CNN-based image classification model with a full-stack web system.

This project demonstrates practical AI integration within a production-style architecture, from model training to cloud deployment.

---

## 🚀 Project Overview

CropDoctor enables users to:

- Upload plant images
- Receive AI-based disease classification
- Get treatment recommendations
- Maintain crop growth diaries
- Participate in a community board

The focus of this project was to design a scalable AI-integrated system rather than a standalone ML experiment.

---

## 🏗 System Architecture

User (Frontend)
↓
Backend API (Authentication & Business Logic)
↓
AI Inference Service (CNN Model)
↓
Database & Cloud Infrastructure

---

## 🔗 Repository Structure

### 🌐 Frontend
https://github.com/JinLee0811/cropdoctor-frontend

### 🧩 Backend
https://github.com/JinLee0811/cropdoctor-backend

### 🧠 AI Module
https://github.com/JinLee0811/cropdoctor-ai-module

---

## 🧠 AI Component

The AI module uses:

- MobileNetV2 (transfer learning)
- Multi-class image classification (20 plant disease categories)
- Data augmentation (rotation, crop, flip)
- Weighted cross-entropy for class imbalance
- FastAPI-based inference service

Model training included hyperparameter tuning and validation analysis (confusion matrix, accuracy tracking).

---

## 👥 Team & My Role

This project was developed by a team of 4 members.

I served as the team leader and led the AI development track.

My responsibilities included:

- Designing overall system architecture and service boundaries
- Leading CNN model selection and training (MobileNetV2 transfer learning)
- Handling dataset preprocessing and class imbalance strategies
- Coordinating integration between frontend, backend, and AI modules
- Managing technical milestones and project direction

The project was developed with technical guidance from a senior manager, ensuring architectural quality and structured development practices.

---

## ☁️ Cloud & Security

- AWS EC2 hosting
- AWS S3 storage
- JWT-based authentication (Access & Refresh Tokens)
- Role-based access control
- Modular service separation

---

## 📊 Technical Focus

- Separation of AI inference and business logic
- Production-style API architecture
- Secure authentication workflow
- End-to-end AI integration
- Scalable system design

---

## 📑 Project Documentation

Project Presentation (PPT):  
https://docs.google.com/presentation/d/1AqkFJvT3NqN3fuDDluk8VCY4vVHavrAQhvV15ZNNjFs/edit?usp=sharing

---

## 👨‍💻 Author

Jin Lee  
AI-focused Software Engineer  
Sydney, Australia
