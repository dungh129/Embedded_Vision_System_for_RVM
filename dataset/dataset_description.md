
---

## B. `dataset/dataset_description.md`

```markdown
# Dataset Description

This dataset was collected for recyclable bottle classification under semi-structured visual conditions.

## Classes
- Plastic
- Glass
- Metal

## Dataset Properties

The dataset is organized around three visual properties:

### 1. Background
- cardboard
- black

### 2. Lighting
- direct
- indirect

### 3. Position
- side
- top/bottom

## Collection Notes

The dataset was designed to imitate deployment scenarios relevant to an embedded recycling system.
However, the collection environment was not fully controlled.

The images may still be affected by:
- natural ambient light
- small scene variation
- environmental noise
- object placement inconsistency

For this reason, the dataset should be considered **semi-structured** rather than fully controlled.

## Purpose

The purpose of this dataset design is to:
- test robustness under different viewing conditions
- compare model behavior across practical scenarios
- support deployment-oriented evaluation for Raspberry Pi-based classification

## Image Preparation

Images used in training are resized to 256×256 unless otherwise stated in the notebook.