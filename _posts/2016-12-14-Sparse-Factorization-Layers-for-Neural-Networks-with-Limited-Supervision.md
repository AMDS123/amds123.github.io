---
layout: post
title: "Sparse Factorization Layers for Neural Networks with Limited Supervision"
date: 2016-12-14 03:13:29
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Classification
author: Parker Koch, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
Whereas CNNs have demonstrated immense progress in many vision problems, they suffer from a dependence on monumental amounts of labeled training data. On the other hand, dictionary learning does not scale to the size of problems that CNNs can handle, despite being very effective at low-level vision tasks such as denoising and inpainting. Recently, interest has grown in adapting dictionary learning methods for supervised tasks such as classification and inverse problems. We propose two new network layers that are based on dictionary learning: a sparse factorization layer and a convolutional sparse factorization layer, analogous to fully-connected and convolutional layers, respectively. Using our derivations, these layers can be dropped in to existing CNNs, trained together in an end-to-end fashion with back-propagation, and leverage semisupervision in ways classical CNNs cannot. We experimentally compare networks with these two new layers against a baseline CNN. Our results demonstrate that networks with either of the sparse factorization layers are able to outperform classical CNNs when supervised data are few. They also show performance improvements in certain tasks when compared to the CNN with no sparse factorization layers with the same exact number of parameters.

##### Abstract (translated by Google)
尽管CNN在许多视力问题上已经取得了巨大的进步，但是它们依赖于大量标记的训练数据。另一方面，字典学习不能扩展到CNN可以处理的问题的大小，尽管对于低级视觉任务（如去噪和修补）非常有效。最近，对监督任务（如分类和逆问题）的词典学习方法进行适应性的兴趣也在增长。我们提出了两个基于字典学习的新网络层：一个稀疏分解层和一个卷积稀疏分解层，分别类似于全连接层和卷积层。使用我们的推导，这些层可以被放入到现有的CNN中，通过反向传播以端到端的方式一起训练，并且以经典CNN所不能的方式利用半监督。我们通过实验将这两个新层的网络与基线CNN进行比较。我们的研究结果表明，当监督数据很少时，具有稀疏分解层的网络能够胜过传统的CNN。与CNN相比，它们在某些任务中也表现出性能改进，没有稀疏分解层，参数数量相同。

##### URL
[https://arxiv.org/abs/1612.04468](https://arxiv.org/abs/1612.04468)

##### PDF
[https://arxiv.org/pdf/1612.04468](https://arxiv.org/pdf/1612.04468)

