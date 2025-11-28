---
title: "Image Reconstruction from Feature Maps"
excerpt: "Reconstruct images from CNN feature maps using decoder networks trained on Tiny ImageNet.<br/><img src='/images/img_rep_rec.png'>"
collection: projects
link: "https://github.com/Alireza-Ghafouri/Image-reconstruction-from-feature-maps"
---

This project investigates the feature representations learned by convolutional neural networks (CNNs) by reconstructing images from the feature maps of different layers of a pre-trained AlexNet model, inspired by *“Understanding Deep Image Representations by Inverting Them”* (Dosovitskiy & Brox, 2016).

We:
- Use **Tiny ImageNet**, selecting a subset of classes for training and evaluation.
- Train separate reconstruction models for feature maps from `conv2`, `conv5`, `fc6`, and `fc8`.
- Base decoder architectures on the structures in the original paper, with reduced depth for computational efficiency.
- Produce **loss plots** and **visualizations of reconstructed images**.

👉 Full code and detailed description:  
[Image Reconstruction from Feature Maps on GitHub](https://github.com/Alireza-Ghafouri/Image-reconstruction-from-feature-maps)
