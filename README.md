# Implementation-of-different-CNN-models-
This project focuses on classifying maize leaf diseases using different Convolutional Neural Network (CNN) models. I implemented and compared several models to evaluate their performance on the same dataset.
### 📊 Model Comparison

The table below compares all the implemented CNN models based on:
- Training Accuracy
- Test Accuracy
- Number of Parameters
- Model Size (in MB)

This helps identify models that balance **accuracy**, **complexity**, and **efficiency** for real-world deployment.

| Model         | Train Accuracy | Test Accuracy | Parameters    | Size     |
|---------------|----------------|---------------|---------------|----------|
| Custom CNN    | 98.36%         | 89.66%        | 9,680,580     | 36.93 MB |
| VGG16         | 98.74%         | 93.87%        | 27,562,308    | 105.14 MB|
| VGG19         | 97.48%         | 95.00%        | 33,002,308    | 125.89 MB|
| ResNet18      | 99.96%         | 92.00%        | 11,192,964    | 42.70 MB |
| ResNet34      | 94.16%         | 91.20%        | 63,877,198    | 243.67 MB|
| ResNet50      | 71.19%         | 75.10%        | 24,638,854    | 93.99 MB |
| Inception V1  | 92.32%         | 91.95%        | 6,236,908     | 23.79 MB |
| Inception V2  | 86.11%         | 89.46%        | 22,328,356    | 207.35 MB|
| Inception V3  | 92.63%         | 90.04%        | 27,562,308    | 85.18 MB |
| MobileNetV2   | 94.31%         | 91.20%        | 2,586,948     | 9.87 MB  |
| AlexNet       | 99.25%         | 88.89%        | 46,764,804    | 178.39 MB|

> 📌 *Table: Model performance comparison for maize leaf disease classification*
