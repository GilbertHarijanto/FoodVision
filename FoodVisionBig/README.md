# FoodVision Big - EfficientNetB2 for 101-Class Food-101 Classification

**FoodVision Big** extends the FoodVision project to classify 101 different food categories from the Food-101 dataset using EfficientNetB2.

## Overview

- **Model:** EfficientNetB2 (modified for 101-class classification)
- **Dataset:** Food-101 (all 101 classes)
- **Accuracy:** ~65% on the test set
- **Model Size:** ~30 MB – compact and optimized for mobile platforms

## Key Features

- **Comprehensive Food Recognition:** Capable of identifying a wide variety of food categories.
- **Efficient Performance:** Maintains a small footprint while handling complex multi-class classification.
- **Data Augmentation:** Uses State-of-the-Art data augmentation (`TrivialAugmentWide`) to enhance model robustness.
- **Deployment Ready:** Comes with a Gradio demo for interactive usage and is packaged for cloud deployment (e.g., on HuggingFace Spaces).

## Project Structure

- **Data Preparation:** Downloads and processes the full Food-101 dataset, applying state-of-the-art augmentation on training data.
- **Training Pipeline:** Custom training loops with an optimizer, learning rate scheduler (`ReduceLROnPlateau`), and label smoothing to tackle the challenges of 101 classes.
- **Evaluation:** Includes tools to plot loss/accuracy curves and benchmark inference speed.
- **Deployment:** Packaged as a deployable Gradio app with instructions for local testing and cloud deployment.
