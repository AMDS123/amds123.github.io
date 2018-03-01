---
layout: post
title: "Neural Photometric Stereo Reconstruction for General Reflectance Surfaces"
date: 2018-02-28 09:47:20
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Tatsunori Taniai, Takanori Maehara
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel convolutional neural network architecture for photometric stereo (Woodham, 1980), a problem of recovering 3D object surface normals from multiple images observed under varying illuminations. Despite its long history in computer vision, the problem still shows fundamental challenges for surfaces with unknown general reflectance properties (BRDFs). Leveraging deep neural networks to learn complicated reflectance models is promising, but studies in this direction are very limited due to difficulties in acquiring accurate ground truth for training and also in designing networks invariant to permutation of input images. In order to address these challenges, we propose a reconstruction based unsupervised learning framework where surface normals and BRDFs are predicted by the network and fed into the rendering equation to synthesize observed images. The network is trained during testing by minimizing reconstruction loss between observed and synthesized images. Thus, our learning process does not require ground truth normals or even pre-training on external images. Our method is shown to achieve the state-of-the-art performance on a challenging real-world scene benchmark.

##### Abstract (translated by Google)
我们提出了一种用于光度立体的新型卷积神经网络架构（Woodham，1980），这是一种从在不同照明下观察到的多个图像中恢复3D物体表面法线的问题。尽管其在计算机视觉方面有着悠久的历史，但这个问题仍然表现出对于具有未知的一般反射特性（BRDF）的表面的基本挑战。利用深度神经网络来学习复杂的反射模型是有希望的，但由于难以获得准确的训练基础真实性，以及设计不变排列输入图像的网络，因此在这方面的研究非常有限。为了解决这些挑战，我们提出了基于重建的无监督学习框架，其中表面法线和BRDF由网络预测并馈送到渲染方程中以合成观察图像。网络在测试期间通过最小化观察和合成图像之间的重建损失来训练。因此，我们的学习过程不需要基本事实正常，甚至不需要对外部图像进行预培训。我们的方法被证明可以在具有挑战性的真实世界场景基准测试中实现最先进的性能。

##### URL
[http://arxiv.org/abs/1802.10328](http://arxiv.org/abs/1802.10328)

##### PDF
[http://arxiv.org/pdf/1802.10328](http://arxiv.org/pdf/1802.10328)

