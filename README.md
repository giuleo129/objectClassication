# Object Classification with PyTorch

This project implements an image classification pipeline using PyTorch and a ResNet-18 backbone on a custom dataset with 8 classes. Data augmentation techniques are applied to improve model generalization.

## Objective
Train a deep learning model to classify images into 8 categories while ensuring model interpretability and robustness.

## Tools & Technologies
- Python, PyTorch  
- Jupyter Notebooks  
- Data augmentation: random flips, rotations, affine transforms, color jitter, Gaussian blur, noise, random erasing  
- Grad-CAM for model interpretability  

## Training & Evaluation
- **Training:** Cross-entropy loss, Adam optimizer, learning rate scheduling, early stopping  
- **Validation:** Monitor accuracy and loss on validation split  
- **Checkpointing:** Save best model weights  
- **Testing:** Evaluate on test set and export predictions to CSV  

## Model Interpretability
- Grad-CAM visualizations highlight image regions most influencing model decisions, supporting explainable AI.

## Key Takeaway
This project demonstrates practical skills in deep learning, model training, evaluation, and interpretability techniques, applied to real-world image classification problems.

<img width="551" height="568" alt="Screenshot 2025-12-28 112008" src="https://github.com/user-attachments/assets/b5c98bcb-d864-4bb6-90dd-4219a182616e" />
