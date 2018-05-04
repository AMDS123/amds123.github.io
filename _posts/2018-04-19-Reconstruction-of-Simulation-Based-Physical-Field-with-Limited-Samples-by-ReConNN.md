---
layout: post
title: "Reconstruction of Simulation-Based Physical Field with Limited Samples by ReConNN"
date: 2018-04-19 08:17:08
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Optimization Classification
author: Yu Li, Hu Wang, Kangjia Mo, Tao Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
A variety of modeling techniques have been developed in the past decade to reduce the computational expense and increase the calculation accuracy. In this study, the distinctive characteristic compared to classical modeling models is "from image based model to mechanical based model (e.g. stress, strain, and deformation)". In such framework, a neural network architecture named ReConNN is proposed and the ReConNN mainly contains two neural networks that are CNN and GAN. A classical topology optimization is considered as an experimental example, and the CNN is employed to construct the mapping between contour images during topology optimization and compliance. Subsequently, the GAN is utilized to generate more contour images to improve the reconstructed model. Finally, the Lagrange polynomial is applied to complete the reconstruction. However, typical CNN architectures are commonly applied to classification problems, which appear powerless handling with regression of images for simulation problems. Meanwhile, the existing GAN architectures are insufficient to generate high-accuracy "pseudo contour images". Therefore, a Convolution in Convolution (CIC) architecture and a Convolutional AutoEncoder based on Wasserstein Generative Adversarial Network (WGAN-CAE) architecture are suggested. Specially, extensive experiments and comparisons with existing architectures of CNN and GAN demonstrate that the CIC is highly accurate and corresponding computational cost also can be significantly reduced when handling the regression problem of contour images, and the WGAN-CAE achieves significant improvements on generating contour images. The results demonstrate that the proposed ReConNN has a potential capability to reconstruct physical field for further researches, e.g. optimization.

##### Abstract (translated by Google)
过去十年中已经开发了各种建模技术，以降低计算成本并提高计算精度。在这项研究中，与传统建模模型相比，其独特特征是“从基于图像的模型到基于机械的模型（例如应力，应变和变形）”。在此框架下，提出了一个名为ReConNN的神经网络体系结构，ReConNN主要包含两个CNN和GAN神经网络。经典的拓扑优化被认为是一个实验例子，并且CNN被用来在拓扑优化和顺从期间构建轮廓图像之间的映射。随后，GAN被用来生成更多的轮廓图像以改善重建的模型。最后，应用拉格朗日多项式完成重建。然而，典型的CNN体​​系结构通常被应用于分类问题，这些分类问题通过图像回归来解决模拟问题显得无能为力。同时，现有的GAN体系结构不足以生成高精度的“伪轮廓图像”。因此，提出了基于Wasserstein生成对抗网络（WGAN-CAE）体系结构的卷积卷积（CIC）体系结构和卷积自动编码器。特别是，广泛的实验和与CNN和GAN现有体系结构的比较表明，CIC在处理轮廓图像的回归问题时具有高度的准确性并且相应的计算成本也可以显着降低，并且WGAN-CAE在生成轮廓图像方面取得显着改进。结果表明，所提出的ReConNN具有重建用于进一步研究的物理场的潜力。优化。

##### URL
[https://arxiv.org/abs/1805.00528](https://arxiv.org/abs/1805.00528)

##### PDF
[https://arxiv.org/pdf/1805.00528](https://arxiv.org/pdf/1805.00528)

