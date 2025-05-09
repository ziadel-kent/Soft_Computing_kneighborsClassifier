# Malware Classification using Soft Computing Techniques

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Dataset](https://img.shields.io/badge/Dataset-TUNAdromd-orange)

A comparative study of machine learning models (Random Forest, SVM, KNN) enhanced with evolutionary algorithms (GA, PSO) for static malware detection in PE files.

## 📌 Overview
This project implements a robust malware classifier that:
- Processes **Windows PE files** using 256 static features (headers, opcodes)
- Optimizes feature selection via **Genetic Algorithm** and **Particle Swarm Optimization**
- Compares three classifiers: **Random Forest (94% accuracy)**, SVM (92%), and KNN (89%)

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/Soft_Computing_Malware_Classifier.git
cd Soft_Computing_Malware_Classifier
pip install -r requirements.txt
