---
title: "Saliency Map Prediction with Deep ConvNets"
excerpt: "CNN-based saliency map prediction inspired by 'Shallow and Deep Convolutional Networks for Saliency Prediction'.<br/><img src='/images/saliency.jpg'>"
collection: projects
---

This project implements a convolutional neural network for **saliency map prediction**, inspired by the Deep ConvNet architecture proposed in *“Shallow and Deep Convolutional Networks for Saliency Prediction”* (CVPR 2016). The goal is to predict regions of an image that are most likely to attract human visual attention.

The framework uses the **2000cat** dataset, a smaller subset of the SALICON dataset, and follows the paper’s methodology with a reduced-depth Deep ConvNet to keep memory and computation manageable. Training is performed with an **L2 loss** on saliency maps, using an **85%-15% train–validation split** with uniform sampling across classes. All key hyperparameters, dataset paths, and output directories are configurable via a dedicated `config` file.

During training, the code saves the trained model, logs, and **visualization plots** of the predicted saliency maps, enabling qualitative and quantitative analysis of the model’s behavior.

👉 [View the code on GitHub](https://github.com/Alireza-Ghafouri/Saliency-Map-Prediction)
