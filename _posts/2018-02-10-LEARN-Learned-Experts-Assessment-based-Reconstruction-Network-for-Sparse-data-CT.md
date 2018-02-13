---
layout: post
title: "LEARN: Learned Experts' Assessment-based Reconstruction Network for Sparse-data CT"
date: 2018-02-10 06:33:27
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Knowledge Deep_Learning
author: Hu Chen, Yi Zhang, Yunjin Chen, Junfeng Zhang, Weihua Zhang, Huaiqiaing Sun, Yang Lv, Peixi Liao, Jiliu Zhou, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive sensing (CS) has proved effective for tomographic reconstruction from sparsely collected data or under-sampled measurements, which are practically important for few-view CT, tomosynthesis, interior tomography, and so on. To perform sparse-data CT, the iterative reconstruction commonly use regularizers in the CS framework. Currently, how to choose the parameters adaptively for regularization is a major open problem. In this paper, inspired by the idea of machine learning especially deep learning, we unfold a state-of-the-art "fields of experts" based iterative reconstruction scheme up to a number of iterations for data-driven training, construct a Learned Experts' Assessment-based Reconstruction Network ("LEARN") for sparse-data CT, and demonstrate the feasibility and merits of our LEARN network. The experimental results with our proposed LEARN network produces a competitive performance with the well-known Mayo Clinic Low-Dose Challenge Dataset relative to several state-of-the-art methods, in terms of artifact reduction, feature preservation, and computational speed. This is consistent to our insight that because all the regularization terms and parameters used in the iterative reconstruction are now learned from the training data, our LEARN network utilizes application-oriented knowledge more effectively and recovers underlying images more favorably than competing algorithms. Also, the number of layers in the LEARN network is only 12, reducing the computational complexity of typical iterative algorithms by orders of magnitude.

##### Abstract (translated by Google)
压缩感测（CS）已被证实对稀疏采集的数据或欠采样测量的层析成像重建有效，这对于少数CT CT，层析X射线照相合成，内部层析成像等实际上非常重要。为了执行稀疏数据CT，迭代重建通常在CS框架中使用正则化器。目前，如何自适应选择正则化参数是一个重大的问题。在本文中，受机器学习尤其是深度学习的启发，我们展示了一系列基于迭代重建方案的最先进的“专家领域”，并进行了多次数据驱动训练的迭代，构建了一个学习专家“基于评估的重构网络（”LEARN“），用于稀疏数据CT，并展示我们LEARN网络的可行性和优点。我们提出的LEARN网络的实验结果与众所周知的Mayo Clinic低剂量挑战数据集相比，在伪影减少，特征保存和计算速度方面与几种最先进的方法相比具有竞争性。这与我们的见解一致，因为现在从训练数据中学习迭代重建中使用的所有正则化术语和参数，因此我们的LEARN网络比竞争算法更有效地利用面向应用的知识并更有利地恢复底层图像。此外，LEARN网络中的层数仅为12，将典型迭代算法的计算复杂度降低了数量级。

##### URL
[http://arxiv.org/abs/1707.09636](http://arxiv.org/abs/1707.09636)

##### PDF
[http://arxiv.org/pdf/1707.09636](http://arxiv.org/pdf/1707.09636)

