---
layout: post
title: "Extended depth-of-field in holographic image reconstruction using deep learning based auto-focusing and phase-recovery"
date: 2018-03-21 20:59:33
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Yichen Wu, Yair Rivenson, Yibo Zhang, Zhensong Wei, Harun Gunaydin, Xing Lin, Aydogan Ozcan
mathjax: true
---

* content
{:toc}

##### Abstract
Holography encodes the three dimensional (3D) information of a sample in the form of an intensity-only recording. However, to decode the original sample image from its hologram(s), auto-focusing and phase-recovery are needed, which are in general cumbersome and time-consuming to digitally perform. Here we demonstrate a convolutional neural network (CNN) based approach that simultaneously performs auto-focusing and phase-recovery to significantly extend the depth-of-field (DOF) in holographic image reconstruction. For this, a CNN is trained by using pairs of randomly de-focused back-propagated holograms and their corresponding in-focus phase-recovered images. After this training phase, the CNN takes a single back-propagated hologram of a 3D sample as input to rapidly achieve phase-recovery and reconstruct an in focus image of the sample over a significantly extended DOF. This deep learning based DOF extension method is non-iterative, and significantly improves the algorithm time-complexity of holographic image reconstruction from O(nm) to O(1), where n refers to the number of individual object points or particles within the sample volume, and m represents the focusing search space within which each object point or particle needs to be individually focused. These results highlight some of the unique opportunities created by data-enabled statistical image reconstruction methods powered by machine learning, and we believe that the presented approach can be broadly applicable to computationally extend the DOF of other imaging modalities.

##### Abstract (translated by Google)
全息照相仅以强度记录的形式对样品的三维（3D）信息进行编码。然而，为了从其全息图解码原始样本图像，需要自动聚焦和相位恢复，这对于数字化执行通常是麻烦且耗时的。在这里，我们展示了基于卷积神经网络（CNN）的方法，该方法在全息图像重建中同时执行自动对焦和相位恢复以显着扩展景深（DOF）。为此，CNN通过使用随机去聚焦后向传播全息图及其相应的对焦相位恢复图像对来训练。在此训练阶段之后，CNN将3D样本的单个后向传播全息图作为输入，以迅速实现相位恢复并在显着扩展的DOF上重建样本的焦点图像。这种基于深度学习的自由度扩展方法是非迭代的，并且显着地改进了从O（nm）到O（1）的全息图像重构算法的时间复杂度，其中n是指样本内单个对象点或粒子的数量体积，并且m代表聚焦搜索空间，在其中每个对象点或粒子需要单独聚焦。这些结果突出强调了由机器学习支持的数据启用统计图像重建方法创造的一些独特机会，并且我们相信所提出的方法可以广泛地适用于计算地扩展其他成像模式的DOF。

##### URL
[https://arxiv.org/abs/1803.08138](https://arxiv.org/abs/1803.08138)

##### PDF
[https://arxiv.org/pdf/1803.08138](https://arxiv.org/pdf/1803.08138)

