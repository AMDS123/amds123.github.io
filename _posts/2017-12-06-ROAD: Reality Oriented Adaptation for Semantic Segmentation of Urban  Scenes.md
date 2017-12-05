---
layout: post
title: 'ROAD: Reality Oriented Adaptation for Semantic Segmentation of Urban  Scenes'
date: 2017-12-06 01:34:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Yuhua Chen, Wen Li, Luc Van Gool
---

* content
{:toc}

##### Abstract
Exploiting synthetic data to learn deep models has attracted increasing attention in recent years. However, the intrinsic domain difference between synthetic and real images usually causes a significant performance drop when applying the learned model to real world scenarios. This is mainly due to two reasons: 1) the model overfits to synthetic images, making the convolutional filters incompetent to extract informative representation for real images; 2) there is a distribution difference between synthetic and real data, which is also known as the domain adaptation problem. To this end, we propose a new reality oriented adaptation approach for urban scene semantic segmentation by learning from synthetic data. First, we propose a target guided distillation approach to learn the real image style, which is achieved by training the segmentation model to imitate a pretrained real style model using real images. Second, we further take advantage of the intrinsic spatial structure presented in urban scene images, and propose a spatial-aware adaptation scheme to effectively align the distribution of two domains. These two components can be readily integrated into existing state-of-the-art semantic segmentation networks to improve their generalizability when adapting from synthetic to real urban scenes. We achieve a new state-of-the-art of 39.4% mean IoU on the Cityscapes dataset by adapting from the GTAV dataset.

##### Abstract (translated by Google)
利用综合数据学习深度模型近年来受到越来越多的关注。然而，合成和真实图像之间的内在区域差异通常会导致在将学习模型应用于真实世界场景时显着的性能下降。这主要是由于两个原因：1）模型过度适合合成图像，使得卷积滤波器无法提取真实图像的信息表示; 2）合成数据和真实数据之间存在分布差异，也称为域适应问题。为此，本文提出了一种新的面向城市场景语义分割的面向现实的自适应方法。首先，我们提出了一种目标引导式蒸馏方法来学习真实的图像风格，这是通过训练分割模型来实现，使用真实的图像来模仿预训练的真实风格模型。其次，进一步利用城市场景图像中的内在空间结构，提出空间感知适应方案，有效对齐两个域的分布。这两个组件可以很容易地集成到现有的最先进的语义分割网络中，以提高从合成到真实城市场景的适应性时的普遍性。我们通过从GTAV数据集中进行调整，在Cityscapes数据集上实现了39.4％的平均IoU最新技术水平。

##### URL
[https://arxiv.org/abs/1711.11556](https://arxiv.org/abs/1711.11556)

