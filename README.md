# Automated Detection System for White Spot Disease (WSD) in Shrimp Aquaculture

This project contains the implementation of an **Automated Detection System for White Spot Disease (WSD) in Shrimp Aquaculture** using **Deep Learning** techniques. The project addresses the significant challenge posed by WSD, a viral infection that causes high mortality rates in shrimp farming, leading to severe economic losses.

## Key Features
- **Hybrid CNN-LSTM Model:** Combines spatial feature extraction (CNN - ResNet50) and sequential modeling (LSTM) for robust disease classification.
- **Dataset Processing:** Handles class imbalance, empty label files, and includes data augmentation for improved model performance.
- **High Performance:** Achieved training accuracy of 95.2%, validation accuracy of 91.3%, and test accuracy of 89.5%.
- **User-Friendly Interface (Planned):** Enables real-time disease diagnostics by allowing shrimp images to be uploaded.
- **Scalability:** Suitable for both small-scale and large-scale shrimp farms.

## Objectives
- Early detection of WSD for timely intervention.
- Reduction in economic losses and enhancement of sustainability in aquaculture.
- Development of a system that minimizes reliance on manual inspections and human error.

## Technical Details
- **Dataset:** Consists of images labeled in YOLO format for binary classification (Healthy vs. Infected).
- **Model Architecture:** Utilizes ResNet50 as the backbone for feature extraction and LSTM for sequential data processing.
- **Preprocessing Techniques:** Includes resizing, normalization, oversampling, and augmentation to improve robustness.

## Future Enhancements
- Integration of attention mechanisms for better feature interpretability.
- Deployment using Flask/FastAPI for real-time predictions.
- Extension to multi-class classification for broader disease detection.

