---
layout: post
title: "A Compact Kernel Approximation for 3D Action Recognition"
date: 2017-10-04 11:05:35
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Jacopo Cavazza, Pietro Morerio, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
3D action recognition was shown to benefit from a covariance representation of the input data (joint 3D positions). A kernel machine feed with such feature is an effective paradigm for 3D action recognition, yielding state-of-the-art results. Yet, the whole framework is affected by the well-known scalability issue. In fact, in general, the kernel function has to be evaluated for all pairs of instances inducing a Gram matrix whose complexity is quadratic in the number of samples. In this work we reduce such complexity to be linear by proposing a novel and explicit feature map to approximate the kernel function. This allows to train a linear classifier with an explicit feature encoding, which implicitly implements a Log-Euclidean machine in a scalable fashion. Not only we prove that the proposed approximation is unbiased, but also we work out an explicit strong bound for its variance, attesting a theoretical superiority of our approach with respect to existing ones. Experimentally, we verify that our representation provides a compact encoding and outperforms other approximation schemes on a number of publicly available benchmark datasets for 3D action recognition.

##### Abstract (translated by Google)
3D动作识别显示从输入数据的协方差表示（联合3D位置）受益。具有这种特征的内核机器馈送是3D动作识别的有效范例，产生最新的结果。但是，整个框架受到众所周知的可伸缩性问题的影响。实际上，一般情况下，必须对所有引用一个Gram矩阵的实例对核函数进行评估，该矩阵的复杂度是样本数量的二次方。在这项工作中，我们通过提出一个新的显式特征映射来近似核函数，将这种复杂性降低到线性。这允许训练具有显式特征编码的线性分类器，其以可缩放的方式隐含地实现了Log-Euclidean机器。我们不仅证明了所提出的近似是无偏的，而且还证明了其方差的明确的强约束，证明了我们的方法在现有方法上的理论优越性。在实验上，我们验证了我们的表示提供了一个紧凑的编码，并且在3D动作识别的许多公开可用的基准数据集上胜过了其他的近似方案。

##### URL
[https://arxiv.org/abs/1709.01695](https://arxiv.org/abs/1709.01695)

##### PDF
[https://arxiv.org/pdf/1709.01695](https://arxiv.org/pdf/1709.01695)

