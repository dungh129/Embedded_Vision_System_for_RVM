# Deployment

This folder contains Raspberry Pi deployment materials for the embedded bottle classification system.

## Contents

- `capture_images.py`  
  Captures images using Raspberry Pi Camera Module 3 and saves them into organized dataset folders.

- `load_run_classify.py`  
  Loads a trained `.pth` model and performs inference on captured images.

- `models/`  
  Contains trained models for different deployment scenarios.

## Model Scenarios

The models are named based on the visual conditions they were trained or evaluated under:

- background
- position
- lighting

Example:
- `direct.pth` 
- `indirect.pth` 

## Notes

These scripts are intended to support on-device experimentation and deployment for the embedded recycling classification system.

