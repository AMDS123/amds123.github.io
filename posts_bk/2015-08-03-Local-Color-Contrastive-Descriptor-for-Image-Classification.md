---
layout: post
title: "Local Color Contrastive Descriptor for Image Classification"
date: 2015-08-03 03:29:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Classification Classification Deep_Learning
author: Sheng Guo, Weilin Huang, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Image representation and classification are two fundamental tasks towards multimedia content retrieval and understanding. The idea that shape and texture information (e.g. edge or orientation) are the key features for visual representation is ingrained and dominated in current multimedia and computer vision communities. A number of low-level features have been proposed by computing local gradients (e.g. SIFT, LBP and HOG), and have achieved great successes on numerous multimedia applications. In this paper, we present a simple yet efficient local descriptor for image classification, referred as Local Color Contrastive Descriptor (LCCD), by leveraging the neural mechanisms of color contrast. The idea originates from the observation in neural science that color and shape information are linked inextricably in visual cortical processing. The color contrast yields key information for visual color perception and provides strong linkage between color and shape. We propose a novel contrastive mechanism to compute the color contrast in both spatial location and multiple channels. The color contrast is computed by measuring \emph{f}-divergence between the color distributions of two regions. Our descriptor enriches local image representation with both color and contrast information. We verified experimentally that it can compensate strongly for the shape based descriptor (e.g. SIFT), while keeping computationally simple. Extensive experimental results on image classification show that our descriptor improves the performance of SIFT substantially by combinations, and achieves the state-of-the-art performance on three challenging benchmark datasets. It improves recent Deep Learning model (DeCAF) [1] largely from the accuracy of 40.94% to 49.68% in the large scale SUN397 database. Codes for the LCCD will be available.

##### Abstract (translated by Google)
图像表示和分类是多媒体内容检索和理解的两个基本任务。在当前的多媒体和计算机视觉社区中，形状和纹理信息（例如，边缘或方向）是视觉表示的关键特征的想法是根深蒂固和主导的。已经通过计算本地梯度（例如SIFT，LBP和HOG）提出了许多低级特征，并已经在众多的多媒体应用上取得了巨大的成功。在本文中，我们通过利用色彩对比的神经机制，提出了一种简单而有效的图像分类局部描述符，称为局部颜色对比描述符（LCCD）。这个想法源于神经科学中的观察，即颜色和形状信息在视觉皮层处理中是不可分割地联系在一起的。色彩对比度为视觉色彩感知提供关键信息，并提供颜色和形状之间的强大联系。我们提出了一种新的对比机制来计算空间位置和多个通道的颜色对比度。通过测量两个区域的颜色分布之间的\ emph {f} -divergence来计算颜色对比度。我们的描述符用颜色和对比度信息丰富了局部图像表示。我们通过实验验证，它可以强有力地补偿基于形状的描述符（例如SIFT），同时保持计算简单。图像分类的广泛实验结果表明，我们的描述符基本上通过组合提高了SIFT的性能，并在三个具有挑战性的基准数据集上实现了最新的性能。在大规模SUN397数据库中，它最近改进了最近的深度学习模型（DeCAF）[1]，其准确性从40.94％提高到了49.68％。 LCCD的代码将可用。

##### URL
[https://arxiv.org/abs/1508.00307](https://arxiv.org/abs/1508.00307)

##### PDF
[https://arxiv.org/pdf/1508.00307](https://arxiv.org/pdf/1508.00307)

