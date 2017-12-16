---
layout: post
title: "GridNet with automatic shape prior registration for automatic MRI cardiac segmentation"
date: 2017-09-12 19:48:38
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: Clement Zotti, Zhiming Luo, Alain Lalande, Olivier Humbert, Pierre-Marc Jodoin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a fully automatic MRI cardiac segmentation method based on a novel deep convolutional neural network (CNN) designed for the 2017 ACDC MICCAI challenge. The novelty of our network comes with its embedded shape prior and its loss function tailored to the cardiac anatomy. Our model includes a cardiac centerof-mass regression module which allows for an automatic shape prior registration. Also, since our method processes raw MR images without any manual preprocessing and/or image cropping, our CNN learns both high-level features (useful to distinguish the heart from other organs with a similar shape) and low-level features (useful to get accurate segmentation results). Those features are learned with a multi-resolution conv-deconv "grid" architecture which can be seen as an extension of the U-Net. Experimental results reveal that our method can segment the left and right ventricles as well as the myocardium from a 3D MRI cardiac volume in 0.4 second with an average Dice coefficient of 0.90 and an average Hausdorff distance of 10.4 mm.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于为2017 ACDC MICCAI挑战设计的新型深度卷积神经网络（CNN）的全自动MRI心脏分割方法。我们网络的新颖之处在于其嵌入式的形状，以及其针对心脏解剖学的损失功能。我们的模型包括一个心脏中心质量回归模块，可以进行自动形状预先注册。此外，由于我们的方法在没有任何手动预处理和/或图像裁剪的情况下处理原始MR图像，CNN学习高级特征（用于区分具有相似形状的其他器官的心脏）和低级特征（用于获得准确的分割结果）。这些特征是通过多分辨率的转换“网格”结构来学习的，可以看作是U-Net的延伸。实验结果显示，我们的方法可以在0.4秒内从3D MRI心脏体积分割左心室和右心室以及心肌，平均Dice系数为0.90，平均Hausdorff距离为10.4mm。

##### URL
[https://arxiv.org/abs/1705.08943](https://arxiv.org/abs/1705.08943)

##### PDF
[https://arxiv.org/pdf/1705.08943](https://arxiv.org/pdf/1705.08943)

