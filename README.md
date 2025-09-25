📌 Project Overview

This project implements an image classification pipeline using PyTorch and a ResNet-18 backbone. The model is trained on a custom dataset with 8 classes, leveraging extensive data augmentation (random flips, rotations, affine transforms, color jitter, Gaussian blur, noise, random erasing) to improve generalization.

The training loop includes:

Cross-entropy loss for multi-class classification.

Adam optimizer with learning rate scheduling and early stopping.

Train/validation split with monitoring of accuracy and loss.

Model checkpointing to save the best weights.

After training, the pipeline supports:

Evaluation on the test set and CSV export of predictions.

Grad-CAM visualizations to interpret the model’s decisions and highlight the most important image regions influencing predictions.

This combination of training, validation, testing, and interpretability ensures both performance and explainability of the deep learning model.
