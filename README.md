# Towards Accurate Renal Micro-Structure Segmentation  
## An Assessment of YOLOv8 and Mask R-CNN Models
## Paper Link in IEEE - https://ieeexplore.ieee.org/document/10914804/
📄 *Published in:* 2024 IEEE International Women in Engineering (WIE) Conference on Electrical and Computer Engineering (WIECON-ECE)  
📅 *Date:* December 6, 2024  
📍 *Pages:* 326–331  
📚 *Publisher:* IEEE

---

## 🧠 Overview

This repository contains supplementary materials and insights for the research paper:

> **"Towards Accurate Renal Micro-Structure Segmentation: An Assessment of YOLOv8 and Mask R-CNN Models"**  
> *Authors:* Md Estiak Ahmed, Farhana Tazmim Pinki, Mozdaher Abdul Quader, Montaser Abdul Quader, Fateha Jannat Ayrin, Ahmed Selim Anwar, Prosenjit Roy

Our research explores the effectiveness of modern instance segmentation models—YOLOv8 and Mask R-CNN—in segmenting renal micro-structures such as *glomeruli* and *blood vessels*. Accurate segmentation in medical imaging is crucial for developing faster and more reliable nephrology diagnostics.

---

## 🧪 Methodology

We applied two advanced deep learning techniques for medical image segmentation:

- **YOLOv8** (You Only Look Once version 8)
- **Mask R-CNN** (Region-based Convolutional Neural Networks)

Key techniques include:
- Instance segmentation using annotated renal histology images
- Model training and evaluation using the **HuBMAP dataset**
- Performance measurement via metrics like Intersection over Union (IoU)

### 📊 Key Results

| Model       | IoU Score |
|-------------|-----------|
| YOLOv8      | **84.55%** |
| Mask R-CNN  | ~81%      |

YOLOv8 showed particularly strong results in segmenting renal micro-structures due to its real-time performance and refined object detection accuracy.

---

## 🗂️ Repository Structure

```bash
├── data/                   # Dataset preprocessing and annotations
├── models/                 # YOLOv8 and Mask R-CNN implementation and configs
├── results/                # Evaluation metrics, sample outputs, and visualizations
├── notebooks/              # Jupyter notebooks for experimentation
├── paper/                  # Published PDF and citation info
└── README.md               # Project overview
