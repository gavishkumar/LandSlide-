# LandSlide-
# 🌍 Landslide Detection Using Satellite Imagery 🌍

**Author**: Gavish Kumar  
**Project**: Landslide Detection and Mapping  
**Technology**: Machine Learning, Satellite Imagery, Deep Learning Models  

---

![Landslide Detection Banner](https://via.placeholder.com/1000x300.png?text=Landslide+Detection+Using+Satellite+Imagery)  
*Detecting landslides with precision through advanced deep learning techniques.*

---

## 📖 Overview

This project leverages **satellite imagery** and **machine learning models** to accurately detect landslides. Using advanced deep learning techniques, this system identifies and maps landslide-prone areas, providing critical information for disaster management and environmental monitoring. This project implements multiple model architectures, including **ResNet18**, **Autoencoder**, and an **Attention Mechanism** to maximize detection accuracy.

---

## 🧰 Features

- **High Accuracy Detection**: Achieves accuracy up to 93.03% using Autoencoder.
- **Multiple Model Comparison**: Compares ResNet18, Autoencoder, and Attention Mechanism for best performance.
- **Noise Reduction**: Autoencoder model enhances feature clarity by removing irrelevant data.
- **Targeted Detection**: Attention Mechanism prioritizes high-risk regions, increasing focus on critical areas.
- **Visual Output**: Generates visual outputs for detected landslides, enabling easier interpretation.

---

## 🚀 Project Architecture

The project follows an agile and modular design, broken down into stages for efficient workflow. The architecture includes:

1. **Data Collection**: Satellite imagery data is collected and preprocessed.
2. **Model Training**: Trains on ResNet18, Autoencoder, and Attention Mechanism.
3. **Evaluation**: Compares models based on accuracy, with results visualized in comparative charts.
4. **Deployment**: Deploys the trained model with optimized parameters for real-time or batch processing.

---

## 📊 Model Comparison

| Model               | Accuracy (%) |
|---------------------|--------------|
| **ResNet18**        | 90.15%       |
| **Autoencoder**     | 93.03%       |
| **Attention Mechanism** | 88.50%   |

- **ResNet18**: Reliable baseline for feature extraction.
- **Autoencoder**: Best performance with refined, noise-free features.
- **Attention Mechanism**: Focuses on high-risk areas, reducing false positives.

---

## 🛠️ Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/gavishkumar/landslide-detection.git
   cd landslide-detection
