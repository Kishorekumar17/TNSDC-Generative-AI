# TNSDC-Generative-AI
# Image-to-Image Translation using Conditional GANs

This repository contains the code for training and testing a Conditional Generative Adversarial Network (cGAN) for image-to-image translation tasks. In particular, it focuses on translating images from one domain to another while preserving semantic content.

## Introduction

Image-to-image translation is a task of transforming an image from one domain (source domain) to another domain (target domain) while retaining essential characteristics of the input image. Conditional GANs (cGANs) are a popular approach for achieving this task by incorporating conditional information into the generative model.

This project aims to provide a framework for training and testing cGANs for various image-to-image translation tasks, such as:
- Day to night image conversion
- Style transfer
- Sketch to photo conversion
- etc.

## Requirements

- Python (>=3.6)
- TensorFlow (>=2.0) or PyTorch (>=1.0)
- NumPy
- Matplotlib (for visualization)
- (Optional) CUDA-enabled GPU for faster training

## Getting Started

1. Prepare your dataset:
- Collect a dataset of paired images, where each pair consists of an input image from the source domain and its corresponding target image from the target domain.
- Preprocess the dataset as necessary (resize, normalize, augment, etc.)
2. Train cGAN
3. Evaluate the trained model


## Architecture

The cGAN architecture consists of:
- Generator (G): Transforms an input image from the source domain to the target domain.
- Discriminator (D): Distinguishes between real target images and fake generated images.
- Conditional Information: Both G and D are conditioned on the input source image.

## Results

[Include sample results or links to demo images/videos here]



