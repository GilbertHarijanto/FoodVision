# Vision Transformer (ViT) Implementation for Food-101 Dataset

This project implements a Vision Transformer (ViT) model from scratch using PyTorch, replicating the architecture from the original ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929) paper. The model is trained and evaluated on a subset of the Food-101 dataset, focusing on 3 food classes.

![Steak Example](https://raw.githubusercontent.com/GilbertHarijanto/PyTorch-ViT-Paper-Replicating/main/steak.jpg)

## Project Overview

Vision Transformers (ViT) represent a groundbreaking approach in computer vision by applying transformer architectures, originally designed for natural language processing, to image recognition tasks. This implementation:

- Builds ViT architecture from scratch using PyTorch
- Implements the key components of the original paper
- Trains and evaluates on Food-101 dataset (3-class subset)
- Provides detailed documentation and training results

## Dataset

The project uses a subset of the Food-101 dataset, focusing on 3 classes for efficient training and evaluation. The Food-101 dataset contains 101,000 images in total, with 1,000 images per food category.

### Classes Used:
- Pizza
- Steak
- Sushi

## Model Architecture

The Vision Transformer (ViT) architecture includes:

- Patch Embedding
- Position Embedding
- Multi-Head Self-Attention
- MLP Blocks
- Layer Normalization
- Classification Head

## Requirements

```bash
pytorch
torchvision
torchinfo
matplotlib
pillow
tqdm
requests
