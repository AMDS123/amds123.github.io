---
layout: post
title: "Variational reaction-diffusion systems for semantic segmentation"
date: 2016-04-01 01:04:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Paul Vernaza
mathjax: true
---

* content
{:toc}

##### Abstract
A novel global energy model for multi-class semantic image segmentation is proposed that admits very efficient exact inference and derivative calculations for learning. Inference in this model is equivalent to MAP inference in a particular kind of vector-valued Gaussian Markov random field, and ultimately reduces to solving a linear system of linear PDEs known as a reaction-diffusion system. Solving this system can be achieved in time scaling near-linearly in the number of image pixels by reducing it to sequential FFTs, after a linear change of basis. The efficiency and differentiability of the model make it especially well-suited for integration with convolutional neural networks, even allowing it to be used in interior, feature-generating layers and stacked multiple times. Experimental results are shown demonstrating that the model can be employed profitably in conjunction with different convolutional net architectures, and that doing so compares favorably to joint training of a fully-connected CRF with a convolutional net.

##### Abstract (translated by Google)
提出了一种新颖的多类语义图像分割全局能量模型，该模型允许非常有效的精确推理和导数计算以进行学习。该模型中的推理等价于特定类型的向量值高斯马尔可夫随机场中的MAP推理，最终简化为求解线性PDE的线性系统，称为反应扩散系统。解决这个系统可以实现时间缩放近似线性的图像像素的数量，通过减少到连续的FFT，在线性变化的基础。该模型的效率和可微性使其特别适合于与卷积神经网络的集成，甚至允许将其用于内部，特征生成层和多次堆叠。实验结果表明，该模型可以有效地结合不同的卷积网络体系结构使用，而且这样做与使用卷积网络的全连接CRF的联合训练相比更为有利。

##### URL
[https://arxiv.org/abs/1604.00092](https://arxiv.org/abs/1604.00092)

##### PDF
[https://arxiv.org/pdf/1604.00092](https://arxiv.org/pdf/1604.00092)

