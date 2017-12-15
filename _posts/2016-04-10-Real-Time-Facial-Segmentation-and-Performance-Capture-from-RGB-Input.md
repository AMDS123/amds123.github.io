---
layout: post
title: "Real-Time Facial Segmentation and Performance Capture from RGB Input"
date: 2016-04-10 07:04:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Tracking CNN Semantic_Segmentation Deep_Learning
author: Shunsuke Saito, Tianye Li, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of unconstrained real-time 3D facial performance capture through explicit semantic segmentation in the RGB input. To ensure robustness, cutting edge supervised learning approaches rely on large training datasets of face images captured in the wild. While impressive tracking quality has been demonstrated for faces that are largely visible, any occlusion due to hair, accessories, or hand-to-face gestures would result in significant visual artifacts and loss of tracking accuracy. The modeling of occlusions has been mostly avoided due to its immense space of appearance variability. To address this curse of high dimensionality, we perform tracking in unconstrained images assuming non-face regions can be fully masked out. Along with recent breakthroughs in deep learning, we demonstrate that pixel-level facial segmentation is possible in real-time by repurposing convolutional neural networks designed originally for general semantic segmentation. We develop an efficient architecture based on a two-stream deconvolution network with complementary characteristics, and introduce carefully designed training samples and data augmentation strategies for improved segmentation accuracy and robustness. We adopt a state-of-the-art regression-based facial tracking framework with segmented face images as training, and demonstrate accurate and uninterrupted facial performance capture in the presence of extreme occlusion and even side views. Furthermore, the resulting segmentation can be directly used to composite partial 3D face models on the input images and enable seamless facial manipulation tasks, such as virtual make-up or face replacement.

##### Abstract (translated by Google)
通过在RGB输入中的显式语义分割，我们引入了无约束的实时3D面部表情捕捉的概念。为了确保鲁棒性，尖端的监督学习方法依赖野外捕获的面部图像的大型训练数据集。虽然大量可见的脸部表现出令人印象深刻的跟踪质量，但是由于头发，配件或手部对脸部姿势的任何遮挡都会导致明显的视觉伪影和跟踪精确度的损失。由于其外观变化的巨大空间，遮挡的建模大多被避免。为了解决这个高维度的诅咒，我们在无约束的图像中执行跟踪，假设非面部区域可以被完全遮蔽。随着最近在深度学习上的突破，我们证明像素级面部分割是可能的实时通过重新设计卷积神经网络原来设计的一般语义分割。我们开发了一种基于具有互补特性的双流反卷积网络的高效架构，并引入了精心设计的训练样本和数据增强策略，以提高分割精度和鲁棒性。我们采用先进的基于回归的面部跟踪框架，将分割后的人脸图像作为训练，在极端遮挡甚至侧视的情况下展示准确和不间断的面部表情捕捉。此外，最终的分割可以直接用于在输入图像上合成部分3D人脸模型，并实现无缝的面部操作任务，如虚拟化妆或面部替换。

##### URL
[https://arxiv.org/abs/1604.02647](https://arxiv.org/abs/1604.02647)

##### PDF
[https://arxiv.org/pdf/1604.02647](https://arxiv.org/pdf/1604.02647)

