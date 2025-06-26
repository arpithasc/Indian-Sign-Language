## ✋ AI-Powered Indian Sign Language Translator

Category: Computer Vision | Accessibility | AI | Internship Project
Role: Project Developer & Documentation Author


## 🧩 Overview

The AI-Powered Indian Sign Language Translator is a real time system designed to interpret Indian Sign Language (ISL) gestures into text or speech. It leverages Computer Vision, Machine Learning, and Speech APIs to enhance communication accessibility for the deaf and hard-of-hearing community.


## 🚨 Problem Statement

In India, communication barriers between hearing-impaired individuals and the rest of society are significant due to limited knowledge of ISL. There is a lack of accessible, low-cost solutions to bridge this gap in real-time.


## 🎯 Objectives
	•	Translate static and dynamic ISL gestures into readable text and spoken output.
	•	Enable real-time interpretation using simple webcam input.
	•	Make the solution scalable and affordable using open-source technologies.

## ⚙️ Tech Stack

Technology               Purpose
Python               Programming Language
OpenCV               Real-time video processing
scikit-learn         SVM for classification
TensorFlow/Keras     CNN modeling
Google Speech API    Text-to-speech output

## 🧠 System Architecture
[ Webcam Input ]
       ↓
[ Preprocessing (OpenCV + HOG) ]
       ↓
[ Classification (SVM/CNN) ]
       ↓
[ Output to Text or Speech (TTS API) ]

## 📌 Key Features
	•	🔍 Uses HOG (Histogram of Oriented Gradients) for feature extraction
	•	🧠 Implements SVM for static gesture classification
	•	🌀 Supports dynamic gestures using CNN-based models
	•	🔈 Converts output text to speech using Google TTS API

## 📉 Limitations
	•	Works best in controlled lighting environments
	•	Currently trained on a limited dataset of ISL gestures
	•	Real-time processing speed may vary based on hardware
