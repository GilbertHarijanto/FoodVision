# FoodVision Projects Overview

<img src="https://raw.githubusercontent.com/GilbertHarijanto/FoodVision/main/images/FoodVision-HF.png" alt="FoodVision" style="max-width:150px; display:block; margin: 0 auto;" />

Welcome to **FoodVision** – a suite of mobile-friendly food classification projects that leverage state-of-the-art deep learning models for efficient and accurate image recognition. This repository contains three related projects:

- **FoodVision Big:** An EfficientNetB2 model trained on 101 food classes from the Food-101 dataset.
- **FoodVision Mini:** A lightweight EfficientNetB2 model trained on a 3-class subset (Pizza, Steak, Sushi) optimized for speed and high accuracy.
- **ViT Paper Replicating:** A replication of the Vision Transformer (ViT) architecture on a 3-class subset of Food-101, following the original ["An Image is Worth 16x16 Words"](https://arxiv.org/abs/2010.11929) paper.

Check out our interactive demo on [HuggingFace Spaces](https://huggingface.co/spaces/GilbertHarijanto/FoodVision).

Each project has its own README with detailed instructions for training, evaluation, and deployment. Below you will find links to each project's documentation:

- [FoodVision Big README](./FoodVisionBig/README.md)
- [FoodVision Mini README](./FoodVision_Mini/README.md)
- [ViT Paper Replicating README](./PyTorch-ViT-Paper-Replicating/README.md)

---

## Common Highlights

- **Model Architecture:** All projects utilize modern architectures. FoodVision projects use EfficientNetB2 for its optimal balance between speed, size (~30 MB), and accuracy.
- **Performance:**
  - *FoodVision Mini* achieves approximately **96.88% accuracy** on a 3-class dataset.
  - *FoodVision Big* reaches around **65% accuracy** on the full Food-101 dataset.
- **Deployment:** All models are designed to be lightweight and mobile-friendly, with interactive demos built using Gradio.
- **Requirements:**  
  - PyTorch  
  - TorchVision  
  - torchinfo  
  - matplotlib  
  - pillow  
  - tqdm  
  - requests  
  - gradio

Enjoy exploring and feel free to contribute or deploy these models on your device!
