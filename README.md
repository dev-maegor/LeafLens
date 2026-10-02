<p align="center">
  <strong>Bridging Traditional Knowledge with Cutting-Edge Technology</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%2FML-Deep%20Learning-2E7D32?style=for-the-badge" alt="AI/ML">
  <img src="https://img.shields.io/badge/Computer%20Vision-Plant%20Recognition-388E3C?style=for-the-badge" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT License">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Species-20%2B-43A047" alt="20+ Species">
  <img src="https://img.shields.io/badge/Reported%20Accuracy-%3E97%25-2E7D32" alt="Reported Accuracy">
  <img src="https://img.shields.io/badge/Test%20Accuracy-98.41%25-1B5E20" alt="Test Accuracy">
  <img src="https://img.shields.io/badge/Expert%20Validation-95%25-558B2F" alt="Expert Validation">
</p>

# 🌿 LeafLens

### Bridging Traditional Knowledge with Cutting-Edge Technology

> **LeafLens is an AI/ML-based plant identification system designed to recognize Indian medicinal plants from leaf images and connect identified species with traditional medicinal knowledge.**

LeafLens explores how computer vision and deep learning can support both **plant recognition** and the **digital preservation of India's botanical heritage**.

---

## 🌱 Why LeafLens?

India has a long tradition of medicinal-plant knowledge, but this knowledge can be difficult to preserve and access because it is distributed across traditional practitioners, communities, manuscripts, and other sources.

LeafLens addresses this through two connected goals:

1. **Visual identification** — identify a plant from an image of its leaf.
2. **Knowledge integration** — connect the identified species with information about traditional medicinal uses and properties.

The project report describes the broader objective as using AI and ML to preserve, analyze, and make Indian medicinal-plant heritage more accessible.

---

## 🎯 Problem Statement

### 🌳 Biodiversity Loss

Environmental degradation and the loss of experienced practitioners can contribute to the disappearance of plant-related knowledge.

### 📚 Scattered Knowledge

Traditional information can exist across manuscripts, oral traditions, communities, and other sources instead of one accessible digital system.

### 🔬 Expert Dependency

Manual plant identification can require substantial botanical knowledge and experience, making the process difficult to scale.

### 💾 Lack of Digital Preservation

Important botanical and traditional knowledge can be difficult to preserve and retrieve when it is not systematically digitized.

---

# 🔎 How LeafLens Works

```text
Leaf Image
    │
    ▼
Image Preprocessing
Resize • Normalize • Augment
    │
    ▼
Deep Learning Model
CNN / MobileNet / Xception
    │
    ▼
Plant Species Prediction
    │
    ├── Species
    └── Confidence
    │
    ▼
Medicinal Knowledge Integration
Traditional Uses • Properties • Context
```

The project report describes the methodology as:

**Data Collection → Preprocessing → Feature Extraction → Model Training → Medicinal Database Integration → Expert Validation**

---

# ✨ Key Features

| Feature | Description |
|---|---|
| 🌿 **Automated Leaf Recognition** | Identifies plant species from leaf images |
| 🧠 **Deep Learning Classification** | CNN-based image classification |
| ⚡ **Transfer Learning** | Uses pretrained MobileNet and Xception architectures |
| 📸 **Image Processing** | Resizing, normalization and augmentation |
| 📚 **Traditional Knowledge Integration** | Links species with medicinal information |
| 🎯 **Confidence-Based Prediction** | Presentation describes prediction results with confidence scores |
| 📱 **Mobile-Oriented Deployment** | Presentation describes a lightweight smartphone-oriented architecture |
| 🌍 **Knowledge Preservation** | Makes botanical information easier to access |

---

# 🧠 Machine Learning Approach

## Convolutional Neural Network

CNNs learn visual representations from leaf images, progressing from low-level patterns to shapes, textures, and higher-level plant representations.

## Transfer Learning

LeafLens uses pretrained architectures:

### MobileNet

An efficient architecture aligned with the project's mobile-deployment direction.

### Xception

An advanced architecture used for high-accuracy image classification.

## Softmax

Softmax is used for multi-class probability output.

## Adam

Adam is used to optimize the model during training.

---

# 🖼️ Dataset & Preprocessing

The report states that the dataset was curated from public sources, including Kaggle, and contains leaf images captured under different environmental conditions.

### Preprocessing

- Image resizing
- Normalization
- Image-tensor preparation
- Visual feature processing

### Augmentation

- Rotation
- Flipping
- Scaling / zooming
- Brightness or color adjustments

These techniques increase training diversity and improve robustness to lighting, orientation, and background changes.

---

# 🌿 Current Recognition Scope

The presentation reports **20+ plant species** currently recognized.

The classes visible in the evaluation confusion matrix include:

- Aloe vera
- Amla
- Ashoka
- Ashwagandha
- Bamboo
- Brahmi
- Curry Leaf
- Guava
- Hibiscus
- Jasmine
- Lemon
- Lemongrass
- Mango
- Mint
- Neem
- Papaya
- Pepper
- Pomegranate
- Rose
- Tulasi

---

# 📊 Results & Evaluation

The project presentation reports:

| Metric / Result | Reported Value |
|---|---:|
| Classification accuracy | **>97%** |
| Test accuracy shown with confusion matrix | **98.41%** |
| Species currently recognized | **20+** |
| Expert validation | **95%** |

The confusion matrix in the presentation is labelled **“Test acc 0.9841”**, corresponding to approximately **98.41%** for that evaluation.

> These figures should be interpreted in the context of their associated dataset/test setup rather than as a universal guarantee of field accuracy.

### Confusion Matrix

The evaluation matrix contains 20 class labels and shows most evaluated samples on the diagonal, with a small number of off-diagonal predictions between classes.

Recommended repository asset:

```text
docs/images/confusion-matrix.png
```

---

# 🔬 Data Structures & Algorithms

## Data Structures

### Arrays & Tensors

Store multidimensional image data, pixels, and model representations.

### Pandas DataFrames

Manage structured dataset and plant metadata.

### Dictionaries

Support mappings such as class IDs, labels, and medicinal information.

## Algorithms

| Algorithm | Role |
|---|---|
| CNN | Feature extraction and classification |
| Transfer Learning | Reuse pretrained visual representations |
| MobileNet | Efficient classification architecture |
| Xception | Advanced classification architecture |
| Image Augmentation | Increase training diversity |
| Softmax | Multi-class probability output |
| Adam | Model optimization |

---

# 🛠️ Technology Stack

### Programming

- Python

### Deep Learning

- PyTorch
- Keras
- CNN
- MobileNet
- Xception

### Computer Vision / Processing

- OpenCV

### Application Layer

- Flask

### Development

- Jupyter Notebook
- Kaggle dataset

---

# 📱 Application Concept

```text
User
 │
 ▼
Capture / Select Leaf Image
 │
 ▼
Image Processing
 │
 ▼
AI Classification
 │
 ▼
Plant Identified
 │
 ▼
┌──────────────────────┐
│ Species              │
│ Confidence           │
│ Traditional Uses     │
│ Medicinal Properties │
└──────────────────────┘
```

The presentation describes a lightweight, smartphone-oriented deployment concept for field identification.

---

# 📚 Traditional Knowledge Integration

A key distinction of LeafLens is that the system is intended to go beyond returning a plant label.

```text
Image
  ↓
Plant Identification
  ↓
Species Metadata
  ↓
Traditional Uses
  ↓
Medicinal Properties
  ↓
Cultural / Preparation Information
```

The report specifically describes linking identified species with a traditional medicinal-properties database to provide information about their uses and significance in Ayurveda.

This makes LeafLens a combination of:

**Computer Vision + Deep Learning + Knowledge Integration + Digital Preservation**

---

# 🧪 Robustness

The project presentation identifies:

- Varying lighting conditions
- Different backgrounds
- Different leaf orientations
- Augmented training data
- Real-world / field testing

as important areas of evaluation.

---

# 🎯 Project Goals

### 01 — Automatic Plant Species Recognition

Build a deep-learning system capable of identifying medicinal plant species from leaf images.

### 02 — Traditional Medicinal Data Integration

Connect recognized species with traditional uses, preparation methods, and cultural significance.

### 03 — Accuracy, Accessibility & Scalability

Maintain high-precision recognition while supporting future dataset expansion.

### 04 — Digital Preservation

Create a sustainable digital representation of indigenous botanical knowledge.

---

# 🚀 Future Roadmap

## 🌍 Global Medicinal Plant Integration

Expand beyond Indian species to medicinal plants from other traditions and regions.

## 📡 IoT-Based Smart Agriculture

Explore integration with sensors and drones for large-scale monitoring.

## 🏥 Healthcare Research Integration

Explore connections with healthcare and natural-medicine research.

## 📱 Real-Time Mobile Field Scanning

Add stronger mobile and offline capabilities for remote environments.

---

# ⚠️ Limitations & Responsible Use

LeafLens should be understood as a **plant-identification and knowledge-access project**, not a medical diagnostic system.

- Recognition is limited to supported classes.
- Performance can vary on images substantially different from training data.
- Visually similar species can remain challenging.
- Traditional medicinal information is informational context, not medical advice.
- Expanding the system requires additional high-quality labelled data.
- Real-world botanical identification may require expert confirmation.

---

# 📂 Suggested Repository Structure

```text
LeafLens/
├── README.md
├── LICENSE
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
│
├── data/
│   └── README.md
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── model_evaluation.ipynb
│
├── models/
│   └── README.md
│
├── src/
│   ├── preprocessing/
│   ├── training/
│   ├── inference/
│   └── utils/
│
├── app/
│   └── ...
│
├── docs/
│   └── images/
│       └── confusion-matrix.png
│
└── requirements.txt
```

> This is a recommended GitHub structure. The exact filenames should match the actual source repository.

---

# 🛠️ Installation

```bash
git clone https://github.com/dev-maegor/LeafLens.git
cd LeafLens
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

> The final `requirements.txt` should be generated from the actual source repository.

---

# ▶️ Running the Project

The presentation identifies Flask as part of the project stack. The exact application entry point should follow the final source tree.

For a typical Flask entry point:

```bash
python app.py
```

Then open the local URL shown by Flask.

---

# 📊 Reproducibility Checklist

A complete ML repository should document:

- Dataset source
- Number of classes
- Number of images
- Train/validation/test split
- Image dimensions
- Batch size
- Number of epochs
- Optimizer
- Learning rate
- Augmentation settings
- Model architecture
- Test-set size
- Accuracy
- Precision / Recall / F1
- Confusion matrix

---

# 👥 Team

| Member | Enrollment |
|---|---|
| **Dishubh Singh** | S24CSEU0808 |
| **G. Ramanjaneya Reddy** | S24CSEU0787 |
| **Divya Kumar** | S24CSEU0857 |

**Faculty Guide:** Susmita Das

**School:** School of Computer Science Engineering and Technology, Bennett University

---

# 🎓 Academic Context

**Project:** LeafLens  
**Degree:** B.Tech in Computer Science  
**Institution:** Bennett University  
**Faculty Guide:** Susmita Das

The submitted report describes LeafLens as an academic project applying AI/ML to Indian medicinal plant identification and preservation of associated traditional knowledge.

---

# 🌿 Vision

LeafLens connects traditional botanical knowledge with modern AI:

```text
TRADITIONAL KNOWLEDGE
          │
          ▼
       LEAFLENS
 AI + Computer Vision
          │
          ▼
DIGITAL BOTANICAL KNOWLEDGE
```

The long-term vision is to make botanical knowledge easier to identify, organize, preserve, and access while providing a foundation for future research and technological applications.

---

# 📌 Project Highlights

| 🌿 | 🧠 | 📊 | 📚 |
|---|---|---|---|
| **20+** | **AI/ML** | **>97%** | **Knowledge Integration** |
| Species | Deep Learning | Reported Accuracy | Traditional Medicine |

---

# ⭐ Key Takeaway

**LeafLens is more than a leaf classifier.**

It is a project exploring how **computer vision and deep learning can become an interface for preserving and accessing traditional botanical knowledge**.

```text
🌿 Plant Images
      +
🧠 Deep Learning
      +
📸 Computer Vision
      +
📚 Traditional Knowledge
      +
💾 Digital Preservation
      ↓
   LEAFLENS
```

---

# 🤝 Contributing

Potential contribution areas include:

- Adding new plant classes
- Improving preprocessing
- Experimenting with model architectures
- Improving evaluation and reproducibility
- Improving the application interface
- Adding multilingual plant information
- Improving offline/mobile inference
- Expanding the knowledge database

Ensure that datasets, models, images, and external knowledge sources permit the intended use before redistributing them.

---

# 📜 License

## 📜 License

LeafLens is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for the full license text.

> **Note:** The MIT License applies to the project's source code. Datasets, pretrained models, images, plant information, and other third-party materials may be subject to their own licenses and attribution requirements.

---

<div align="center">

## 🌿 LeafLens

**AI × Computer Vision × Traditional Botanical Knowledge**
</div>
