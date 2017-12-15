---
layout: post
title: "Dreaming More Data: Class-dependent Distributions over Diffeomorphisms for Learned Data Augmentation"
date: 2016-06-30 06:12:38
categories: arXiv_CV
tags: arXiv_CV
author: Søren Hauberg, Oren Freifeld, Anders Boesen Lindbo Larsen, John W. Fisher III, Lars Kai Hansen
mathjax: true
---

* content
{:toc}

##### Abstract
Data augmentation is a key element in training high-dimensional models. In this approach, one synthesizes new observations by applying pre-specified transformations to the original training data; e.g.~new images are formed by rotating old ones. Current augmentation schemes, however, rely on manual specification of the applied transformations, making data augmentation an implicit form of feature engineering. With an eye towards true end-to-end learning, we suggest learning the applied transformations on a per-class basis. Particularly, we align image pairs within each class under the assumption that the spatial transformation between images belongs to a large class of diffeomorphisms. We then learn a class-specific probabilistic generative models of the transformations in a Riemannian submanifold of the Lie group of diffeomorphisms. We demonstrate significant performance improvements in training deep neural nets over manually-specified augmentation schemes. Our code and augmented datasets are available online.

##### Abstract (translated by Google)
数据增强是培训高维模型的关键要素。在这种方法中，通过对原始训练数据应用预先指定的变换来合成新的观察值;例如〜新图像是通过旋转旧图像而形成的。然而，当前的增强方案依赖于对所应用变换的手动指定，使得数据增强成为特征工程的隐含形式。注意真正的端到端的学习，我们建议学习应用的转换在每个班的基础上。特别是在图像之间的空间变换属于一大类微分同胚的假设下，我们对每一类内的图像对进行对齐。然后，我们学习李群微分同胚的黎曼流形中的一类特定的概率生成模型。我们展示了在手动指定的增强方案上训练深度神经网络方面显着的性能改进。我们的代码和增强的数据集可以在线获得。

##### URL
[https://arxiv.org/abs/1510.02795](https://arxiv.org/abs/1510.02795)

##### PDF
[https://arxiv.org/pdf/1510.02795](https://arxiv.org/pdf/1510.02795)

