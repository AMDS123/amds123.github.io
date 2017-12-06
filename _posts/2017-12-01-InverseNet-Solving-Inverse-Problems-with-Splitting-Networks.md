---
layout: post
title: 'InverseNet: Solving Inverse Problems with Splitting Networks'
date: 2017-12-01 06:04:05
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Deep_Learning
author: Kai Fan, Qi Wei, Wenlin Wang, Amit Chakraborty, Katherine Heller
---

* content
{:toc}

##### Abstract
We propose a new method that uses deep learning techniques to solve the inverse problems. The inverse problem is cast in the form of learning an end-to-end mapping from observed data to the ground-truth. Inspired by the splitting strategy widely used in regularized iterative algorithm to tackle inverse problems, the mapping is decomposed into two networks, with one handling the inversion of the physical forward model associated with the data term and one handling the denoising of the output from the former network, i.e., the inverted version, associated with the prior/regularization term. The two networks are trained jointly to learn the end-to-end mapping, getting rid of a two-step training. The training is annealing as the intermediate variable between these two networks bridges the gap between the input (the degraded version of output) and output and progressively approaches to the ground-truth. The proposed network, referred to as InverseNet, is flexible in the sense that most of the existing end-to-end network structure can be leveraged in the first network and most of the existing denoising network structure can be used in the second one. Extensive experiments on both synthetic data and real datasets on the tasks, motion deblurring, super-resolution, and colorization, demonstrate the efficiency and accuracy of the proposed method compared with other image processing algorithms.

##### Abstract (translated by Google)
我们提出了一种使用深度学习技术来解决逆问题的新方法。反演问题以学习从观测数据到地面真相的端到端映射的形式进行。受正则化迭代算法中广泛使用的分裂策略的启发，将映射分解为两个网络，一个处理与数据项相关的物理正演模型的反演，一个处理来自前者的输出的去噪网络，即与先验/正则化术语相关联的反转版本。两个网络联合训练，学习端到端映射，摆脱两步训练。训练是退火，因为这两个网络之间的中间变量弥合了输入（输出的降级版本）和输出之间的差距，逐渐接近地面事实。所提出的称为InverseNet的网络是灵活的，因为大多数现有的端到端网络结构可以在第一网络中被利用，并且大部分现有的去噪网络结构可以被用在第二网络结构中。针对任务，运动去模糊，超分辨率和彩色化的合成数据和实际数据集的大量实验证明了与其他图像处理算法相比所提出的方法的效率和准确性。

##### URL
[https://arxiv.org/abs/1712.00202](https://arxiv.org/abs/1712.00202)

