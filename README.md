# DFU-XNet

DFU-XNet is a deep learning framework for diabetic foot ulcer (DFU) segmentation that integrates an EfficientNet-B3 encoder, a Frequency Hybrid Local Attention (FHLA) module, and a Feature Pyramid Network (FPN) for accurate multi-scale lesion segmentation.

## Architecture

The proposed framework consists of:

* EfficientNet-B3 Encoder
* Frequency Hybrid Local Attention (FHLA)
* Feature Pyramid Network (FPN)
* Segmentation Head
* Grad-CAM Explainability Module

## Experimental Results

| Metric     | Score  |
| ---------- | ------ |
| Dice Score | 0.9000 |
| IoU        | 0.8317 |
| Accuracy   | 0.9929 |
| Precision  | 0.9170 |
| Recall     | 0.9021 |
| F1-Score   | 0.9000 |
| ROC-AUC    | 0.9966 |

## Model Complexity

| Metric         | Value   |
| -------------- | ------- |
| Parameters     | 12.99 M |
| GFLOPs         | 22.8    |
| FPS            | 45.25   |
| Inference Time | 22.1 ms |

## Repository Structure

```text
DFU-XNet/
├── notebooks/
├── figures/
├── requirements.txt
└── README.md
```

## Status

Research manuscript currently under preparation.

