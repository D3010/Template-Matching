# 🧠 Template Matching in Computer Vision  
A Python implementation using SAD and NCC with support for multi-scale template matching.

---

## 📌 Overview

This project presents a hands-on demonstration of **template matching**, a classical approach in computer vision for finding the presence and location of a template image within a larger image. The implementation showcases two popular similarity measures:

- **Sum of Absolute Differences (SAD)**
- **Normalized Cross-Correlation (NCC)**

The project is implemented using **Python**, with **OpenCV**, **NumPy**, and **Matplotlib**, and includes detailed image visualization and multi-scale detection capabilities.

---

## 🧪 Objective

The main goal is to:

- Understand the core mechanics behind template matching techniques.  
- Compare and visualize how SAD and NCC work in detecting patterns.  
- Extend basic template matching to **multi-scale template matching**, making the solution more robust to object size variations.

---

## 🔍 Methods Used

### 1. Sum of Absolute Differences (SAD)  
SAD compares a template with a region of the image by computing the sum of the absolute pixel-wise differences. A lower SAD value indicates a closer match.

### 2. Normalized Cross-Correlation (NCC)  
NCC is a robust statistical approach that measures similarity while accounting for lighting and contrast variations. A higher NCC score suggests a better match.

---

## 🔧 Features

✅ Custom implementation of **2D Convolution**  
✅ Dynamically generated **Gaussian Kernel** for image smoothing  
✅ **Single and Multi-scale Template Matching**  
✅ Matches visualized with **bounding boxes**  
✅ Visualization handled using **matplotlib** for clarity  
✅ **Zero-padding** support in convolution  

---

## 📁 Project Structure

