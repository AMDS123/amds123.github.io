---
layout: post
title: "SCAN: Structure Correcting Adversarial Network for Organ Segmentation in Chest X-rays"
date: 2017-04-10 16:18:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Detection
author: Wei Dai, Joseph Doyle, Xiaodan Liang, Hao Zhang, Nanqing Dong, Yuan Li, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Chest X-ray (CXR) is one of the most commonly prescribed medical imaging procedures, often with over 2-10x more scans than other imaging modalities such as MRI, CT scan, and PET scans. These voluminous CXR scans place significant workloads on radiologists and medical practitioners. Organ segmentation is a crucial step to obtain effective computer-aided detection on CXR. In this work, we propose Structure Correcting Adversarial Network (SCAN) to segment lung fields and the heart in CXR images. SCAN incorporates a critic network to impose on the convolutional segmentation network the structural regularities emerging from human physiology. During training, the critic network learns to discriminate between the ground truth organ annotations from the masks synthesized by the segmentation network. Through this adversarial process the critic network learns the higher order structures and guides the segmentation model to achieve realistic segmentation outcomes. Extensive experiments show that our method produces highly accurate and natural segmentation. Using only very limited training data available, our model reaches human-level performance without relying on any existing trained model or dataset. Our method also generalizes well to CXR images from a different patient population and disease profiles, surpassing the current state-of-the-art.

##### Abstract (translated by Google)
胸部X线（CXR）是最常用的医学成像程序之一，通常比其他成像模式（如MRI，CT扫描和PET扫描）多扫描2-10倍。这些大量的CXR扫描对放射科医师和医师开展了大量的工作。器官分割是获得有效的CXR计算机辅助检测的关键步骤。在这项工作中，我们提出结构纠正对抗网络（SCAN）来分割肺野和CXR图像中的心脏。 SCAN结合了评论者网络，将卷积分割网络强加于人类生理学的结构规律。在训练期间，评论者网络学习区分来自由分割网络合成的掩模的基础真实器官注释。通过这种对抗的过程，评论家网络学习更高层次的结构，引导分割模型实现切实的分割结果。大量的实验表明，我们的方法产生高度准确和自然的分割。只使用非常有限的训练数据，我们的模型在不依赖任何现有的训练模型或数据集的情况下达到人类的水平。我们的方法也很好地适用于来自不同患者群体和疾病概况的CXR图像，超过了目前的最新技术水平。

##### URL
[https://arxiv.org/abs/1703.08770](https://arxiv.org/abs/1703.08770)

##### PDF
[https://arxiv.org/pdf/1703.08770](https://arxiv.org/pdf/1703.08770)

