---
layout: post
title: "End-to-end 3D face reconstruction with deep neural networks"
date: 2017-04-17 16:31:12
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Pengfei Dou, Shishir K. Shah, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular 3D facial shape reconstruction from a single 2D facial image has been an active research area due to its wide applications. Inspired by the success of deep neural networks (DNN), we propose a DNN-based approach for End-to-End 3D FAce Reconstruction (UH-E2FAR) from a single 2D image. Different from recent works that reconstruct and refine the 3D face in an iterative manner using both an RGB image and an initial 3D facial shape rendering, our DNN model is end-to-end, and thus the complicated 3D rendering process can be avoided. Moreover, we integrate in the DNN architecture two components, namely a multi-task loss function and a fusion convolutional neural network (CNN) to improve facial expression reconstruction. With the multi-task loss function, 3D face reconstruction is divided into neutral 3D facial shape reconstruction and expressive 3D facial shape reconstruction. The neutral 3D facial shape is class-specific. Therefore, higher layer features are useful. In comparison, the expressive 3D facial shape favors lower or intermediate layer features. With the fusion-CNN, features from different intermediate layers are fused and transformed for predicting the 3D expressive facial shape. Through extensive experiments, we demonstrate the superiority of our end-to-end framework in improving the accuracy of 3D face reconstruction.

##### Abstract (translated by Google)
由于其广泛的应用，单个2D面部图像的单目3D面部形状重建一直是一个活跃的研究领域。受深度神经网络（DNN）的成功启发，我们提出了一种基于DNN的方法从单个二维图像端到端三维重建（UH-E2FAR）。与最近使用RGB图像和初始3D面部形状渲染以迭代方式重建和改善3D人脸的工作不同，我们的DNN模型是端到端的，因此可以避免复杂的3D渲染过程。此外，我们在DNN架构中集成了两个部分，即多任务丢失函数和融合卷积神经网络（CNN），以改善面部表情重建。利用多任务丢失函数，将三维人脸重建分为中性三维人脸重建和表情三维人脸重建。中性3D面部形状是特定于类别的。因此，更高层的功能是有用的。相比之下，富有表现力的3D面部形状有利于较低或中间层的特征。融合CNN将不同中间层的特征融合转化，预测三维表情面部形态。通过广泛的实验，我们证明了我们的端到端框架在提高三维人脸重建精度方面的优势。

##### URL
[https://arxiv.org/abs/1704.05020](https://arxiv.org/abs/1704.05020)

##### PDF
[https://arxiv.org/pdf/1704.05020](https://arxiv.org/pdf/1704.05020)

