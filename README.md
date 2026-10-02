# 🌿 LeafLens

<p align="center">
  <img src="https://img.shields.io/badge/LeafLens-AI%20Plant%20Health-2E7D32?style=for-the-badge" alt="LeafLens">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/AI-Computer%20Vision-1565C0?style=for-the-badge" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
</p>

<p align="center">
  <strong>Identify plant diseases from leaf images with AI.</strong>
</p>

<p align="center">
  LeafLens is an AI-powered Android application designed to help users analyze plant leaves and identify potential diseases from images.
</p>

---

## 🌱 Overview

Plant diseases can spread rapidly when they are not identified early. Traditional diagnosis often requires experience, agricultural knowledge, or access to an expert.

**LeafLens** explores how computer vision and machine learning can make preliminary plant-disease identification more accessible.

The application allows a user to provide an image of a plant leaf and receive an AI-assisted analysis of the plant's condition.

The goal is simple:

> 📷 **Capture a leaf → 🤖 Analyze it → 🌿 Understand its condition → 💡 Take informed action**

LeafLens was developed as a practical machine-learning application that brings an image-classification workflow into an Android environment.

---

## ✨ Features

### 📸 Leaf Image Analysis

Provide a plant-leaf image to the application for analysis.

### 🤖 AI-Assisted Disease Detection

LeafLens uses a machine-learning/computer-vision pipeline to analyze visual characteristics of the leaf and identify the corresponding plant-health condition supported by the model.

### 📱 Android Application

The model is integrated into an Android application, allowing inference to be performed through a mobile interface rather than requiring a separate desktop environment.

### 🌿 Plant Health Focus

The application is designed around plant and crop health, making computer-vision-based disease identification more accessible to everyday users and agriculture-focused applications.

### ⚡ Simple Workflow

The application is designed around a straightforward interaction:

```text
        ┌─────────────────┐
        │   Select / Take │
        │   Leaf Image    │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ Image Processing│
        │ / Preprocessing │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ ML Model        │
        │ Inference       │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ Prediction      │
        │ / Analysis      │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ User Result     │
        └─────────────────┘
