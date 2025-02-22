# FoodVision Mini - EfficientNetB2 for 3-Class Food Classification

**FoodVision Mini** is a fast and efficient food classification model built using EfficientNetB2. It is trained on a subset of the Food-101 dataset, focusing on three classes: **Pizza, Steak, and Sushi**.

## Overview

- **Model:** EfficientNetB2 (pretrained on ImageNet with a modified classifier head)
- **Classes:** 3 (Pizza, Steak, Sushi)
- **Accuracy:** ~96.88% on the test set
- **Model Size:** ~30 MB – optimized for mobile deployment

<img src="https://raw.githubusercontent.com/GilbertHarijanto/FoodVision/main/images/results.png" alt="results" style="max-width:150px; display:block; margin: 0 auto;" />

## Key Features

- **Fast Inference:** Designed for rapid predictions with minimal latency.
- **High Accuracy:** Achieves high performance on a curated 3-class dataset.
- **Deployment Ready:** Packaged with a Gradio demo for interactive testing and easy sharing.

## Project Structure

- **Data Handling:** Custom data loaders built with PyTorch’s `ImageFolder` for training and testing.
- **Training:** Implements training and evaluation loops with detailed tracking of loss and accuracy.
- **Inference:** A dedicated prediction function processes images, measures inference time, and outputs class probabilities.
- **Deployment:** Includes a Gradio interface demo and is packaged for deployment as a standalone app.
