# Week-2
This project uses AI-based image classification to automatically identify waste types like plastic, paper, metal, and glass. Using a CNN model trained on the Kaggle Garbage Classification dataset, it aims to improve recycling efficiency and promote sustainability through smart, automated waste management systems.

## 🧠 Project Overview

This project focuses on **automatically classifying waste images** into categories such as *plastic, metal, paper, glass, cardboard, etc.* using **image classification techniques**.  
The goal is to assist in **smart waste management systems** that promote sustainability and environmental protection through efficient sorting and recycling.

---

## 🎯 Problem Statement

With the rapid growth of waste generation worldwide, manual waste sorting has become inefficient and labor-intensive.  
Recyclable materials like **plastic, glass, and metal** are often mixed with general waste, making recycling processes expensive and time-consuming.

The objective of this project is to **build a machine learning model** that can classify images of waste into their respective categories.  
This will help automate segregation processes, reduce human effort, and contribute to cleaner, more sustainable waste management.

---

## 🧩 Dataset Information

We are using the **Garbage Classification Dataset** from Kaggle:
[https://www.kaggle.com/datasets/mostafaabla/garbage-classification](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)

### Dataset Details:
- **Total images:** ~15,150  
- **Number of classes:** 12  
- **Categories:**  
  `cardboard`, `glass`, `metal`, `paper`, `plastic`, `trash`, `white-glass`, `brown-glass`, `green-glass`, `biological`, `battery`, `clothes`

---

## 🏗️ Step 1: Environment Setup

### Prerequisites
Make sure you have Python 3.9–3.11 installed.  
Then install the required libraries:

```bash
pip install tensorflow==2.15.0 numpy==1.26.4 matplotlib pillow
```

---

## 📘 Step 2: Dataset Loading and Exploration

### 🎯 Objective
In this step, we:
- Download the **Garbage Classification Dataset** from Kaggle.  
- Load and explore the dataset directory.  
- Display sample images from different waste categories.


