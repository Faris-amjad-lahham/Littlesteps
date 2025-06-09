# Littlesteps 👶💡
An intelligent pediatric health monitoring system for children aged 0–5. This full-stack application includes features such as symptom checking, growth tracking, vaccination reminders, and health records — helping parents and doctors make informed decisions early on.

## 📚 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [ML Model Info](#ml-model-info)
- [Screenshots / Demo](#screenshots--demo)
- [Team Members](#team-members)
- [License](#license)

## 🧠 Overview

**Littlesteps** is a smart health monitoring app designed for infants and young children (ages 0–5). It offers a centralized platform for tracking symptoms, growth, vaccines, and doctor visits. It combines traditional full-stack development with machine learning to improve early disease detection and healthcare planning.

## 🚀 Features

- 🩺 **Symptom Checker** — Predicts possible diseases based on symptom severity using an MLP neural network (Faris).
- 📈 **Growth Tracking** — Charts and monitors child height and weight over time.
- 💉 **Vaccine Reminders** — Notifies parents about upcoming or missed vaccinations.
- 🗂️ **Health Records** — Stores and manages child medical records securely.

## 🛠 Tech Stack

- **Frontend**: Flutter
- **Backend**: Flask (for ML model API)
- **Database**: Firebase
- **Machine Learning**: Python, Scikit-learn, MLP Classifier
- **Deployment**: Docker, Heroku / Firebase Hosting

## 🤖 ML Model Info (Symptom Checker)

The Symptom Checker uses a custom-trained MLP (Multi-layer Perceptron) neural network to classify 18 pediatric diseases based on symptom severity and child age. It was trained on 123,500 synthetic samples with 57 symptom features.

- Accuracy: ~96.4%
- Features: Symptom severity (0–3), child age
- Output: Predicted disease name

## 🗂️ Project Structure

```
Littlesteps/
├── android/                # Android-specific Flutter code
├── assets/                 # Images, icons, and static files
├── flutter/                # Flutter-specific config
├── ios/                    # iOS-specific Flutter code
├── lib/                    # Dart source code (UI, logic, etc.)
├── linux/                  # Linux platform support
├── macos/                  # macOS platform support
├── notifications/          # Notification service code
├── test/                   # Unit and widget tests
├── web/                    # Web platform support
├── .github/                # GitHub workflows or config
├── .idea/                  # IDE settings
├── .qodo/                  # Qodo project settings (if used)
├── .gitignore              # Git ignore rules
└── README.md
```

## 👥 Team Members

- Faris Amjad Al-Lahham – ML Model + Symptom Checker + GitHub Manager
- Issa Shehab – Vaccine Reminder & Health Record System & Deployement
- Abdullah Alsheikh – Growth Tracking

## 📄 License

MIT License — feel free to use, modify, and contribute!
