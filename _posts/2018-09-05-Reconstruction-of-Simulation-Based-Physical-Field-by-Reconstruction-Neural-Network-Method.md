---
layout: post
title: "Reconstruction of Simulation-Based Physical Field by Reconstruction Neural Network Method"
date: 2018-09-05 02:32:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Optimization Classification
author: Yu Li, Hu Wang, Kangjia Mo, Tao Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
A variety of modeling techniques have been developed in the past decade to reduce the computational expense and improve the accuracy of modeling. In this study, a new framework of modeling is suggested. Compared with other popular methods, a distinctive characteristic is "from image based model to analysis based model (e.g. stress, strain, and deformation)". In such a framework, a reconstruction neural network (ReConNN) model designed for simulation-based physical field's reconstruction is proposed. The ReConNN contains two submodels that are convolutional neural network (CNN) and generative adversarial net-work (GAN). The CNN is employed to construct the mapping between contour images of physical field and objective function. Subsequently, the GAN is utilized to generate more images which are similar to the existing contour images. Finally, Lagrange polynomial is applied to complete the reconstruction. However, the existing CNN models are commonly applied to the classification tasks, which seem to be difficult to handle with regression tasks of images. Meanwhile, the existing GAN architectures are insufficient to generate high-accuracy "pseudo contour images". Therefore, a ReConNN model based on a Convolution in Convolution (CIC) and a Convolutional AutoEncoder based on Wasserstein Generative Adversarial Network (WGAN-CAE) is suggested. To evaluate the performance of the proposed model representatively, a classical topology optimization procedure is considered. Then the ReConNN is utilized to the reconstruction of heat transfer process of a pin fin heat sink. It demonstrates that the proposed ReConNN model is proved to be a potential capability to reconstruct physical field for multidisciplinary, such as structural optimization.

##### Abstract (translated by Google)
在过去十年中已经开发了各种建模技术以减少计算开销并提高建模的准确性。在这项研究中，建议了一个新的建模框架。与其他流行方法相比，鲜明的特征是“从基于图像的模型到基于分析的模型（例如应力，应变和变形）”。在这样的框架下，提出了一种基于仿真的物理场重建的重建神经网络（ReConNN）模型。 ReConNN包含两个子模型，即卷积神经网络（CNN）和生成对抗网络（GAN）。 CNN用于构建物理场的轮廓图像与目标函数之间的映射。随后，GAN用于生成更多与现有轮廓图像类似的图像。最后，应用拉格朗日多项式完成重构。然而，现有的CNN模型通常应用于分类任务，这似乎难以处理图像的回归任务。同时，现有的GAN架构不足以产生高精度的“伪轮廓图像”。因此，提出了基于卷积卷积（CIC）的ReConNN模型和基于Wasserstein生成对抗网络（WGAN-CAE）的卷积自动编码器。为了代表性地评估所提出的模型的性能，考虑经典的拓扑优化过程。然后将ReConNN用于重建针翅散热器的传热过程。它表明，所提出的ReConNN模型被证明是重建多学科物理场的潜在能力，例如结构优化。

##### URL
[http://arxiv.org/abs/1805.00528](http://arxiv.org/abs/1805.00528)

##### PDF
[http://arxiv.org/pdf/1805.00528](http://arxiv.org/pdf/1805.00528)

