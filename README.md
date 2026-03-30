# Embedded Vision System for Reverse Vending Machine

This repository presents an embedded computer vision system for recyclable bottle classification using deep learning and Raspberry Pi deployment.

The project focuses on classifying bottles into three material classes:
- Plastic
- Glass
- Metal

The system combines:
- Dataset collection under semi-structured real-world conditions
- MobileNetV2-based image classification
- Model deployment on Raspberry Pi
- Scenario-based evaluation across background, lighting, and position variations

This work is part of a Master’s thesis on intelligent recycling and Reverse Vending Machine (RVM) development.

---

## Project Overview

The dataset was collected under intentionally varied but not fully controlled conditions.
The design includes three visual properties:

- **Background**
  - cardboard
  - black

- **Lighting**
  - direct
  - indirect

- **Position**
  - side
  - top/bottom

Although the dataset was organized with these factors in mind, it is still influenced by natural light and environmental variation, making it closer to real-world deployment conditions than a fully controlled laboratory dataset.

---

## Repository Structure

- `Recycle_RVM.ipynb`  
  Main Google Colab / Jupyter notebook containing preprocessing, training, evaluation, and model export.

- `dataset/`  
  Dataset organization and documentation based on background, lighting, and position.

- `deployment/`  
  Raspberry Pi scripts for image capture and model inference, plus trained model files.

- `docs/`  
  Survey results, diagrams, and supplementary documentation.

---

## Dataset Design

The dataset is organized by three visual properties:

- `background/`
- `lighting/`
- `position/`

This organization supports scenario-based analysis and helps document how visual conditions affect classification performance.

For more detail, see:
- `dataset/dataset_description.md`

---

## Notebook

Main implementation:
- `/Recycle_RVM.ipynb`

The notebook includes:
- dataset loading
- preprocessing
- augmentation
- MobileNetV2 training
- evaluation
- confusion matrix
- model export

---

## Deployment

The `deployment/` folder contains:
- Raspberry Pi camera image capture script
- Raspberry Pi inference script
- trained `.pth` models for deployment scenarios

See:
- `deployment/README.md`

---

## Survey

A survey was conducted to understand recycling behavior, user perception, and acceptance of automated recycling systems.

Summary materials are available in:
- `docs/survey/`

Only summarized and non-identifiable survey information is included.

---


## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

---


## Acknowledgements

This project was developed with reference to the following open-source resources:

- Daniel Bourke's PyTorch Deep Learning repository  
  https://github.com/mrdbourke/pytorch-deep-learning  

Parts of the training workflow, structure, and PyTorch practices were inspired by this resource.
All dataset design, experimentation, and deployment components in this project are original work.
