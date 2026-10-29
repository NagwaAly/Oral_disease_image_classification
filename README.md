# Oral Disease Image Classification

Deep learning project for classifying oral disease images into 6 classes:

- Calculus
- Caries
- Gingivitis
- Ulcers
- Tooth Discoloration
- Hypodontia

## Models

- Custom CNN
- EfficientNetB0
- ResNet50

## Results

| Model | Test Accuracy |
|---|---:|
| ResNet50 | **93.24%** |
| EfficientNetB0 | 90.69% |
| Custom CNN | 88.85% |

ResNet50 achieved the best performance with a weighted F1-score of **0.93**.

## Workflow

Image preprocessing → Data augmentation → Class weighting → Model training → Fine-tuning → Evaluation → Best model selection.

## Gradio App

An interactive Gradio interface was built to:

**Upload an oral image → Predict the class → Display prediction confidence**

## Tools

Python, TensorFlow/Keras, ResNet50, EfficientNetB0, Scikit-learn, Gradio.

> For educational and research purposes only. This project is not intended for clinical diagnosis.
