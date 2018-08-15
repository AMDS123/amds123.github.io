---
layout: post
title: "Deep Retinex Decomposition for Low-Light Enhancement"
date: 2018-08-14 07:20:55
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement
author: Chen Wei, Wenjing Wang, Wenhan Yang, Jiaying Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Retinex model is an effective tool for low-light image enhancement. It assumes that observed images can be decomposed into the reflectance and illumination. Most existing Retinex-based methods have carefully designed hand-crafted constraints and parameters for this highly ill-posed decomposition, which may be limited by model capacity when applied in various scenes. In this paper, we collect a LOw-Light dataset (LOL) containing low/normal-light image pairs and propose a deep Retinex-Net learned on this dataset, including a Decom-Net for decomposition and an Enhance-Net for illumination adjustment. In the training process for Decom-Net, there is no ground truth of decomposed reflectance and illumination. The network is learned with only key constraints including the consistent reflectance shared by paired low/normal-light images, and the smoothness of illumination. Based on the decomposition, subsequent lightness enhancement is conducted on illumination by an enhancement network called Enhance-Net, and for joint denoising there is a denoising operation on reflectance. The Retinex-Net is end-to-end trainable, so that the learned decomposition is by nature good for lightness adjustment. Extensive experiments demonstrate that our method not only achieves visually pleasing quality for low-light enhancement but also provides a good representation of image decomposition.

##### Abstract (translated by Google)
Retinex模型是低光图像增强的有效工具。它假设观察到的图像可以分解成反射和照明。大多数现有的基于Retinex的方法都精心设计了手工制作的约束和参数，用于这种高度不适合的分解，当应用于各种场景时，可能会受到模型容量的限制。在本文中，我们收集包含低/正常光图像对的LOw-Light数据集（LOL），并提出在该数据集上学习的深度Retinex-Net，包括用于分解的Decom-Net和用于照明调整的Enhance-Net。在Decom-Net的训练过程中，没有分解反射和照明的基本事实。仅利用关键约束来学习网络，包括由成对的低/正常光图像共享的一致反射率以及照明的平滑度。基于分解，随后通过称为Enhance-Net的增强网络对照明进行亮度增强，并且对于联合去噪，存在对反射率的去噪操作。 Retinex-Net是端到端的可训练的，因此学习的分解本质上有利于亮度调整。大量实验表明，我们的方法不仅实现了低光增强的视觉上令人愉悦的质量，而且提供了图像分解的良好表示。

##### URL
[http://arxiv.org/abs/1808.04560](http://arxiv.org/abs/1808.04560)

##### PDF
[http://arxiv.org/pdf/1808.04560](http://arxiv.org/pdf/1808.04560)

