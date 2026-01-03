# AI-smart-gallery
AI-powered smart photo gallery built with Django and computer vision that automatically organizes images by faces, events, and timelines — similar to Google Photos.

---
# 📸 AI Smart Gallery

AI-Powered Photo Management System (Inspired by Google Photos)

Managing thousands of photos stored across devices can quickly become overwhelming. Finding a specific photo from an old event often turns into a frustrating task.

This project, AI Smart Gallery, is a self-hosted, privacy-focused solution that uses Artificial Intelligence and Computer Vision to automatically organize images by faces, events, and timelines, similar to platforms like Google Photos — but completely under your control.

## 🚀 Key Features

This is more than just an image upload tool. AI Smart Gallery is a full-fledged Digital Asset Management (DAM) system powered by deep learning models.

### 👤 Face Recognition & Intelligent Clustering

Automatically detects human faces in uploaded images

Identifies and groups the same person across different photos

Uses InsightFace embeddings combined with DBSCAN clustering and cosine similarity

Creates unique person profiles without manual labeling

### 🔍 Visual Face Search (Google Lens-like Experience)

Upload a reference image or selfie

The system scans the entire photo library

Instantly retrieves all images containing that person

### 📅 Smart Event Detection

Analyzes image timestamps during upload

Groups photos taken within a defined time window into events

Automatically labels moments such as trips, weddings, or gatherings

### 🖼️ AI-Driven Smart Cropping

Prevents poorly cropped images in collages

Uses detected face coordinates for intelligent framing

Ensures faces remain centered and clearly visible

### 🛠️ Technology Stack

Backend

Django (Python)

AI & Deep Learning

InsightFace (Buffalo_L model)

ONNX Runtime

Computer Vision

OpenCV

Pillow (PIL)

Machine Learning

Scikit-Learn (DBSCAN clustering)

Frontend

HTML5

CSS3 (Glassmorphism UI)

JavaScript

Task Handling

Python threading

Designed to scale with Celery & Redis

## 🧠 System Workflow

The application processes images through a multi-step AI pipeline:

### 1️⃣ Face Embedding Generation

Each detected face is passed through a neural network

The model converts facial features into a 512-dimensional numerical vector

### 2️⃣ Incremental Matching

New embeddings are compared against existing cluster averages

If a match is found, the image is assigned instantly

This ensures fast processing during uploads

### 3️⃣ Density-Based Clustering

For re-analysis or rescans, all embeddings are mapped into vector space

DBSCAN identifies clusters of similar faces

Enables automatic person discovery without predefined identities

---
## 🎥 Video Face Recognition
Detect and track faces inside uploaded video files

---
## 📱 Mobile Application Support
Automatic camera roll syncing using Flutter or React Native

---
### 🎓 Ideal Use Cases

Computer Vision Practice

Privacy-focused Photo Management System

Django + AI Integration Learning

---
### 👨‍💻 Author

#### Poojan Patel
Computer Engineering Student
Interested in Artificial Intelligence, Machine Learning, Computer Vision, and Backend Development

---
### ⭐ Support

If you like this project, consider giving a **star** ⭐ on GitHub!
Feel free to open issues, suggest improvements, or request new automation workflows.
This repository will continue expanding with more AI-driven systems.

