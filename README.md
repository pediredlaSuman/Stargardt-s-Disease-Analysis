# 👁️ Detection and Analysis of Stargardt's Disease

A research-focused project that leverages advanced image processing, genetic understanding, and AI algorithms to detect and monitor **Stargardt macular dystrophy (SMD)** — a genetic disease that causes progressive vision loss in children and adolescents.

---

## 📌 Table of Contents

1. [Introduction](#introduction)
2. [Motivation](#motivation)
3. [Problem Statement](#problem-statement)
4. [Proposed Framework](#proposed-framework)
5. [Experimental Results](#experimental-results)
6. [Conclusion & Future Work](#conclusion--future-work)
7. [Technologies Used](#technologies-used)

---

## 📖 Introduction

**Stargardt Disease (SMD)** is caused by mutations in the **ABCA4 gene**, leading to macular degeneration and central vision loss. This project combines imaging techniques such as Fundus Autofluorescence (FAF), Optical Coherence Tomography (OCT), and AI-based detection to improve diagnosis and progression monitoring.

---

## 🎯 Motivation

- **Clinical Need**: Early and accurate diagnosis is crucial due to the irreversible nature of vision loss.
- **Impact on Life**: SMD significantly reduces quality of life at a young age.
- **Research Innovation**: Combining ophthalmology, genetics, and computational biology.
- **Therapy Gap**: No current cure; research is essential for new therapies.

---

## ❗ Problem Statement

Stargardt Disease diagnosis is often delayed due to overlapping symptoms with other retinal disorders. Traditional diagnostic methods lack precision, and treatment options are limited. This project aims to:

- Accurately detect damaged retinal areas using image processing.
- Quantify fat layer areas using OCT.
- Develop scalable image analysis techniques for clinical diagnosis.

---

## 🧠 Proposed Framework

### 🔹 Fundus Image Analysis

- **Preprocessing**: Grayscale conversion, Histogram Equalization, Adaptive Thresholding
- **Detection**: Highlight damaged areas by comparing preprocessed and original images.
- **Visualization**: Damaged areas are clearly marked on fundus images.

![Fundus Methodology](https://github.com/user-attachments/assets/acbcc8bc-fa93-48c6-9f3a-b3894e5425e2)

---

### 🔹 OCT Image Analysis

- **Thresholding**: Segment retinal layers.
- **Contour Detection**: Find the largest layer for fat region analysis.
- **Area Calculation**: Convert pixel area to cm².
- **Output**: Visualized and quantitative segmentation.

---

## 📊 Experimental Results

### ✅ Fundus Image Analysis

- Normal images showed **no highlighted areas** in black-and-white processed results.
- Diseased images showed **clear detection of retinal damage** in unchanged regions after thresholding.

![Fundus Results](https://github.com/user-attachments/assets/79862076-7d28-4cda-b93a-3c405a1b6a9e)

---

### ✅ OCT Image Analysis

- Normal OCT images: fat layer < 150 cm².
- Diseased OCT images: excess fat layer detected and highlighted.
- Saved segmented output for offline analysis.

![OCT Results](https://github.com/user-attachments/assets/08ba1a63-c58d-443d-bf69-f1dcc7510523)

---

## 📌 Conclusion & Future Work

- Demonstrated effective detection of Stargardt’s disease using imaging + computational techniques.
- Future directions:
  - AI-based disease progression modeling.
  - Integration of **high-resolution OCT**, **adaptive optics**, and **genomic data**.
  - Deployment on clinical platforms for real-time diagnostics.

---

## 🛠 Technologies Used

`Python` | `OpenCV` | `NumPy` | `Matplotlib` | `Image Processing` | `OCT Imaging` | `Fundus Analysis` | `Medical Diagnostics` | `AI in Healthcare`



