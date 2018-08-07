---
layout: post
title: "Dilated Convolutions in Neural Networks for Left Atrial Segmentation in 3D Gadolinium Enhanced-MRI"
date: 2018-08-05 19:04:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Sulaiman Vesal, Nishant Ravikumar, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of the left atrial chamber and assessing its morphology, are essential for improving our understanding of atrial fibrillation, the most common type of cardiac arrhythmia. Automation of this process in 3D gadolinium enhanced-MRI (GE-MRI) data is desirable, as manual delineation is time-consuming, challenging and observer-dependent. Recently, deep convolutional neural networks (CNNs) have gained tremendous traction and achieved state-of-the-art results in medical image segmentation. However, it is difficult to incorporate local and global information without using contracting (pooling) layers, which in turn reduces segmentation accuracy for smaller structures. In this paper, we propose a 3D CNN for volumetric segmentation of the left atrial chamber in LGE-MRI. Our network is based on the well known U-Net architecture. We employ a 3D fully convolutional network, with dilated convolutions in the lowest level of the network, and residual connections between encoder blocks to incorporate local and global knowledge. The results show that including global context through the use of dilated convolutions, helps in domain adaptation, and the overall segmentation accuracy is improved in comparison to a 3D U-Net.

##### Abstract (translated by Google)
左心房的分割和评估其形态，对于提高我们对心房颤动的理解至关重要，心房颤动是最常见的心律失常类型。在3D钆增强MRI（GE-MRI）数据中自动化该过程是合乎需要的，因为手动描绘是耗时的，具有挑战性的并且依赖于观察者。最近，深度卷积神经网络（CNN）已经获得了巨大的吸引力并且在医学图像分割中获得了最先进的结果。但是，如果不使用合同（池化）层，很难合并本地和全局信息，这反过来会降低较小结构的分割精度。在本文中，我们提出了一种3D CNN用于LGE-MRI中左心房的体积分割。我们的网络基于众所周知的U-Net架构。我们采用3D完全卷积网络，在网络的最低​​层进行扩张卷积，以及编码器块之间的剩余连接，以结合本地和全球知识。结果表明，通过使用扩张卷积来包括全局上下文，有助于域适应，并且与3D U-Net相比整体分割准确性得到改善。

##### URL
[https://arxiv.org/abs/1808.01673](https://arxiv.org/abs/1808.01673)

##### PDF
[https://arxiv.org/pdf/1808.01673](https://arxiv.org/pdf/1808.01673)

