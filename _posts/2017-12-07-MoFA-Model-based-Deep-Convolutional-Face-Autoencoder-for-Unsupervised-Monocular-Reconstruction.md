---
layout: post
title: "MoFA: Model-based Deep Convolutional Face Autoencoder for Unsupervised Monocular Reconstruction"
date: 2017-12-07 20:38:13
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Ayush Tewari, Michael Zollh&#xf6;fer, Hyeongwoo Kim, Pablo Garrido, Florian Bernard, Patrick P&#xe9;rez, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a novel model-based deep convolutional autoencoder that addresses the highly challenging problem of reconstructing a 3D human face from a single in-the-wild color image. To this end, we combine a convolutional encoder network with an expert-designed generative model that serves as decoder. The core innovation is our new differentiable parametric decoder that encapsulates image formation analytically based on a generative model. Our decoder takes as input a code vector with exactly defined semantic meaning that encodes detailed face pose, shape, expression, skin reflectance and scene illumination. Due to this new way of combining CNN-based with model-based face reconstruction, the CNN-based encoder learns to extract semantically meaningful parameters from a single monocular input image. For the first time, a CNN encoder and an expert-designed generative model can be trained end-to-end in an unsupervised manner, which renders training on very large (unlabeled) real world data feasible. The obtained reconstructions compare favorably to current state-of-the-art approaches in terms of quality and richness of representation.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新型的基于模型的深度卷积自动编码器，解决了从单一的野外彩色图像重构3D人脸的高度挑战性问题。为此，我们将卷积编码器网络与作为解码器的专家设计的生成模型相结合。核心创新是我们基于生成模型分析封装图像形成的新型差分参数解码器。我们的解码器输入一个具有精确定义的语义含义的编码向量，编码详细的人脸姿态，形状，表情，皮肤反射和场景照明。由于这种将基于CNN和基于模型的脸部重构相结合的新方法，基于CNN的编码器学习从单个单眼输入图像中提取语义上有意义的参数。 CNN编码器和专家设计的生成模型首次以无监督的方式端对端地进行训练，这使得对非常大的（未标记的）真实世界数据的训练是可行的。所获得的重建在质量和代表性的丰富性方面与当前最先进的方法相比是有利的。

##### URL
[http://arxiv.org/abs/1703.10580](http://arxiv.org/abs/1703.10580)

##### PDF
[http://arxiv.org/pdf/1703.10580](http://arxiv.org/pdf/1703.10580)

