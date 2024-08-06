# SentiNet

This project aim to use satellite images to detect roads.
Alternatively, this also translate to completing the DeepGlobe Challenge regarding Road Detection.

## Goals
Here's the established main goals regarding the content of the project:
- [ ] Data preparation // Preprocessing
    - [ ] Download and show images of the datasets.
    - [ ] Preprocess images.
    - [ ] Split into train/dev/test datasets.
- [ ] Model Development 
    - [ ] Implement U-Net for Segmentation.
    - [ ] Improve U-Net with either (optionnal):
        - [ ] Residual connections (ResNet).
        - [ ] Attention mechanism (Attention).
    - [ ] Train and evaluate using the proper metrics F1 and Intersection over Union (IoU).
- [ ] Model evaluation 
    - [ ] Evaluate model on test and ensure good generalization
    - [ ] Monitor metrics and display predicted images.
- [ ] Optimization 
    - [ ] Fine-Tune model's parameters.
    - [ ] Implement data augmentation.
    - [ ] Optimize model to fit my HW without sacrificing metrics. 
- [ ] Metrics goal
    - [ ] F1 Score of >= 0.75.
    - [ ] IoU of >= 0.70.

### Computing Capabilities

The computer used  for this project is having:
- 12Gb of RAM
- 1 Quadro P5000 GPU 

## Sub-goals

Atfer the main goal is completed and I'm happy with it the sub-goals with this project are:
- Expand the segmentation task to buildings, greenlands, etc... (either if a relevant dataset is available, or if I labels images myself)
- Use this pre-trained models to adapt it to hot-fetched date from other satellites like sentinel-2 and map road on it.