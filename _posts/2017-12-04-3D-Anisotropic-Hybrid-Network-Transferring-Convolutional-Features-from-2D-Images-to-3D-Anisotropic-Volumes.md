---
layout: post
title: "3D Anisotropic Hybrid Network: Transferring Convolutional Features from 2D Images to 3D Anisotropic Volumes"
date: 2017-12-04 01:54:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Detection
author: Siqi Liu, Daguang Xu, S. Kevin Zhou, Thomas Mertelmeier, Julia Wicklein, Anna Jerebko, Sasa Grbic, Olivier Pauly, Weidong Cai, Dorin Comaniciu
---

* content
{:toc}

##### Abstract
While deep convolutional neural networks (CNN) have been successfully applied for 2D image analysis, it is still challenging to apply them to 3D anisotropic volumes, especially when the within-slice resolution is much higher than the between-slice resolution and when the amount of 3D volumes is relatively small. On one hand, direct learning of CNN with 3D convolution kernels suffers from the lack of data and likely ends up with poor generalization; insufficient GPU memory limits the model size or representational power. On the other hand, applying 2D CNN with generalizable features to 2D slices ignores between-slice information. Coupling 2D network with LSTM to further handle the between-slice information is not optimal due to the difficulty in LSTM learning. To overcome the above challenges, we propose a 3D Anisotropic Hybrid Network (AH-Net) that transfers convolutional features learned from 2D images to 3D anisotropic volumes. Such a transfer inherits the desired strong generalization capability for within-slice information while naturally exploiting between-slice information for more effective modelling. The focal loss is further utilized for more effective end-to-end learning. We experiment with the proposed 3D AH-Net on two different medical image analysis tasks, namely lesion detection from a Digital Breast Tomosynthesis volume, and liver and liver tumor segmentation from a Computed Tomography volume and obtain the state-of-the-art results.

##### Abstract (translated by Google)
虽然深层卷积神经网络（CNN）已经成功地应用于二维图像分析，但将其应用于三维各向异性体积仍然具有挑战性，特别是当片内分辨率远高于片间分辨率和3D卷相对较小。一方面，用三维卷积核对CNN进行直接学习，缺乏数据，可能导致泛化能力差; GPU内存不足限制了模型的大小或代表性的能力。另一方面，将具有可概化特征的二维CNN应用于二维切片会忽略层间信息。由于LSTM学习的困难，将2D网络与LSTM耦合以进一步处理片间信息并不是最佳的。为了克服上述挑战，我们提出了一个三维各向异性混合网络（AH-Net），将从二维图像学习的卷积特征转移到三维各向异性体积。这样的转移继承了所希望的片内信息的强泛化能力，同时自然地利用片间信息进行更有效的建模。焦点损失进一步用于更有效的端到端学习。我们在两个不同的医学图像分析任务上进行了实验，即数字乳房断层成像体积的病灶检测和计算机断层扫描体积的肝脏和肝脏肿瘤分割，并获得了最新的结果。

##### URL
[http://arxiv.org/abs/1711.08580](http://arxiv.org/abs/1711.08580)

