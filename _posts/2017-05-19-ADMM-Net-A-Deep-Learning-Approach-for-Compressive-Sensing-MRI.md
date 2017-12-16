---
layout: post
title: "ADMM-Net: A Deep Learning Approach for Compressive Sensing MRI"
date: 2017-05-19 06:33:18
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Yan Yang, Jian Sun, Huibin Li, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive sensing (CS) is an effective approach for fast Magnetic Resonance Imaging (MRI). It aims at reconstructing MR images from a small number of under-sampled data in k-space, and accelerating the data acquisition in MRI. To improve the current MRI system in reconstruction accuracy and speed, in this paper, we propose two novel deep architectures, dubbed ADMM-Nets in basic and generalized versions. ADMM-Nets are defined over data flow graphs, which are derived from the iterative procedures in Alternating Direction Method of Multipliers (ADMM) algorithm for optimizing a general CS-based MRI model. They take the sampled k-space data as inputs and output reconstructed MR images. Moreover, we extend our network to cope with complex-valued MR images. In the training phase, all parameters of the nets, e.g., transforms, shrinkage functions, etc., are discriminatively trained end-to-end. In the testing phase, they have computational overhead similar to ADMM algorithm but use optimized parameters learned from the data for CS-based reconstruction task. We investigate different configurations in network structures and conduct extensive experiments on MR image reconstruction under different sampling rates. Due to the combination of the advantages in model-based approach and deep learning approach, the ADMM-Nets achieve state-of-the-art reconstruction accuracies with fast computational speed.

##### Abstract (translated by Google)
压缩感应（CS）是快速磁共振成像（MRI）的有效方法。它旨在从k空间中的少量欠采样数据重建MR图像，并加速MRI中的数据采集。为了改善现有MRI系统的重构精度和速度，本文提出了两种新的深层结构，称为ADMM-Nets。 ADMM网络是在数据流图上定义的，这些数据流图来源于用于优化基于CS的一般MRI模型的交替方向乘法器（ADMM）算法中的迭代过程。他们将取样的k空间数据作为输入并输出重建的MR图像。此外，我们扩展我们的网络，以应付复杂价值的MR图像。在训练阶段，网的所有参数（例如变换，收缩函数等）被端对端地区别地训练。在测试阶段，它们具有类似于ADMM算法的计算开销，但是使用从基于CS的重建任务的数据中学习的优化的参数。我们研究了网络结构的不同配置，并在不同的采样率下进行了大量的MR图像重建实验。由于基于模型的方法和深度学习方法的优点相结合，ADMM-Nets以最快的计算速度实现了最先进的重构精度。

##### URL
[https://arxiv.org/abs/1705.06869](https://arxiv.org/abs/1705.06869)

##### PDF
[https://arxiv.org/pdf/1705.06869](https://arxiv.org/pdf/1705.06869)

