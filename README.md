# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/krishnaik06/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=entbappy \
MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)



# 🚀 Kidney Disease Classification Using Deep Learning

## 📌 Project Overview

**Kidney Disease Classification Using Deep Learning** is an end-to-end Computer Vision and Deep Learning project designed to automatically detect and classify kidney diseases from medical images. The application leverages **Convolutional Neural Networks (CNNs)** and **Transfer Learning** to provide accurate, reliable, and scalable disease classification, supporting healthcare professionals in early diagnosis and clinical decision-making.

This project demonstrates the complete Deep Learning lifecycle—from data collection and image preprocessing to model training, evaluation, deployment, and inference. Built with a production-ready architecture, it showcases how Artificial Intelligence can be applied to solve real-world healthcare challenges.

---

## 🎯 Business Problem

Kidney diseases affect millions of people worldwide, and delayed diagnosis can lead to severe health complications, including chronic kidney disease and kidney failure. Manual interpretation of medical images is time-consuming and depends heavily on clinical expertise.

This project addresses these challenges by developing an AI-powered image classification system capable of automatically identifying kidney disease patterns from medical images, enabling faster diagnosis, reducing manual effort, and improving healthcare efficiency.

---

## 💡 Solution

The system processes medical images, performs preprocessing and feature extraction using Deep Learning, and predicts the presence of kidney disease through a trained Convolutional Neural Network.

The complete pipeline includes:

* Data Ingestion
* Data Validation
* Image Preprocessing
* Data Augmentation
* Feature Extraction
* Transfer Learning
* Model Training
* Hyperparameter Tuning
* Model Evaluation
* Model Selection
* Prediction Pipeline
* Model Deployment

---

## ⚙️ Key Features

* ✅ End-to-End Deep Learning Pipeline
* ✅ Medical Image Classification
* ✅ Image Preprocessing & Data Augmentation
* ✅ Transfer Learning for Improved Accuracy
* ✅ Automated Prediction Pipeline
* ✅ Production-Ready Project Structure
* ✅ Exception Handling & Logging
* ✅ REST API for Inference
* ✅ Dockerized Deployment
* ✅ Modular & Scalable Architecture

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras
* Convolutional Neural Networks (CNN)
* Transfer Learning

### Data Processing

* NumPy
* Pandas
* OpenCV

### Visualization

* Matplotlib
* Seaborn

### Deployment

* Flask / FastAPI
* Docker
* GitHub
* AWS / Render

### MLOps

* MLflow
* DVC (Optional)
* Logging
* Pipeline Automation

---

## 📊 Deep Learning Workflow

1. Data Collection
2. Data Validation
3. Image Preprocessing
4. Data Augmentation
5. Model Development
6. Transfer Learning
7. Model Training
8. Hyperparameter Optimization
9. Model Evaluation
10. Model Deployment
11. Prediction API

---

## 📈 Expected Outcome

The trained Deep Learning model accurately classifies kidney disease from medical images, enabling faster diagnosis, reducing manual screening efforts, and supporting healthcare professionals with AI-assisted clinical decision-making.

---

## 🌟 Project Highlights

* Real-World Healthcare AI Application
* End-to-End Deep Learning Pipeline
* Medical Image Classification
* CNN-Based Feature Learning
* Transfer Learning for High Performance
* Production-Ready Architecture
* REST API Deployment
* Dockerized Application
* Clean, Modular, and Scalable Codebase
* Industry-Oriented MLOps Practices

---

## 🎓 Skills Demonstrated

* Deep Learning
* Computer Vision
* Convolutional Neural Networks (CNNs)
* Transfer Learning
* Medical Image Processing
* Data Augmentation
* Model Optimization
* TensorFlow & Keras
* REST API Development
* Dockerization
* MLOps Fundamentals
* Software Engineering Best Practices
* Git & GitHub
* Cloud Deployment

---

## 💼 Why This Project Matters

Artificial Intelligence is transforming modern healthcare by enabling faster, more accurate, and scalable diagnostic systems. This project demonstrates how Deep Learning and Computer Vision can assist in medical image analysis, helping healthcare professionals improve diagnostic efficiency while reducing manual workload.

This repository showcases not only expertise in Deep Learning and Computer Vision but also software engineering, deployment, and production-level system design. It reflects the practical skills required for **Data Scientist, Machine Learning Engineer, Deep Learning Engineer, Computer Vision Engineer, AI Engineer, and Healthcare AI** roles.
