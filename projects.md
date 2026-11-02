---
layout: page
title: "Projects"
description: "Research, machine learning, and software projects."
permalink: /projects/
---

## Research Projects

### ArtFAE-Net: Explainable Emotion Recognition in Visual Art *(in progress)*

**National Taichung University of Education**, Taiwan · TEEP Research Internship · Sep 2026 – Present

- Proposed model for artwork emotion recognition and explainable aesthetic assessment.
- Fine-tuning ResNet50 and CLIP models on ArtEmis for artwork emotion classification.
- Developing methods to explain model predictions and relate them to aesthetic features of artworks.

### ClaimGraph-BT: Claim Extraction and Cross-Paper Comparison for Brain Tumor AI Literature

**Novosibirsk State University**, Russia · Published at AIST 2026

- Detects scientific claims in 1,585 brain tumor AI papers (17,304 sentences) using fine-tuned PubMedBERT and BioBERT.
- Extracts structured fields (model, task, dataset, metric, value, comparison, domain) with Flan-T5.
- Links claims across papers with SPECTER2 clustering and graph layers.
- The best claim-detection model (PubMedBERT) reached 0.84 accuracy and 0.93 AUC.
- **Dataset:** [BrainTumorClaims on Zenodo](https://doi.org/10.5281/zenodo.20364566)

### MedSETNER: Dataset-Name Extraction from Medical Literature

**Novosibirsk State University**, Russia · Published at AIST 2026 · Co-author

- Benchmark corpus of 691 medical articles with 9,376 annotated dataset-name mentions (Fleiss' κ = 0.85).
- Contributed to dataset annotation.

---

## Machine Learning Projects

- **[Diabetes Prediction](https://github.com/nawazpatana/Diabetes-Prediction-DCS-NSU)** — Trained and compared machine learning models on clinical data (glucose, BMI, insulin, blood pressure, age and other features) to predict diabetes; tracked experiments with MLflow, versioned data with DVC, and deployed the model as a Dockerised app.

- **MLOps Workflow** — Built a reproducible machine learning workflow with Docker, Redis, MLflow, DagsHub and FastAPI for experiment tracking, model management and deployment.

- **Age and Gender Prediction** — Python application for facial age and gender estimation using DeepFace.

---

## Software Projects

### Smart Agriculture Chatbot

[GitHub](https://github.com/nawazpatana/SMART-AGRICULTURE-CHATBOT)

- Flutter app that gives farmers agricultural advice through a chatbot assistant.
- Integrated Firebase Authentication, Cloud Firestore, REST APIs and real-time weather forecasting.
- Includes SoilPedia, farming tips and location-based services.
- **Technologies:** Flutter, Dart, Firebase, REST APIs, Geolocation

### Quran Application

[GitHub](https://github.com/nawazpatana/Quran-App)

- Cross-platform Flutter app with Quran reading, prayer times, Qibla direction, Azkar and daily Duas.
- Uses GPS-based location services and SQLite for offline storage.
- **Technologies:** Flutter, Dart, SQLite, Provider, Geolocator, Material Design

### Hajj & Umrah Guide App

[GitHub](https://github.com/nawazpatana/Hajj-Umrah-App)

- Flutter app with step-by-step Hajj and Umrah guidance.
- Integrated Firebase Authentication, GPS-based prayer times, Qibla direction, weather updates and local storage.
- Includes modules for Duas, hotels, transportation, visa information and emergency contacts.
- **Technologies:** Flutter, Dart, Firebase, SQLite, REST APIs, Google Maps, Geolocation

### Gems Bazar (B.S. Final-Year Project)

- E-commerce website for dry fruits and gemstones with retail and wholesale purchasing, custom orders and multiple payment methods.
- **Technologies:** HTML, CSS, JavaScript, PHP, MySQL
