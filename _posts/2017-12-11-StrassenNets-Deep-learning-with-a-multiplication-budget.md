---
layout: post
title: "StrassenNets: Deep learning with a multiplication budget"
date: 2017-12-11 18:49:07
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Michael Tschannen, Aran Khanna, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
A large fraction of the arithmetic operations required to evaluate deep neural networks (DNNs) are due to matrix multiplications, both in convolutional and fully connected layers. Matrix multiplications can be cast as $2$-layer sum-product networks (SPNs) (arithmetic circuits), disentangling multiplications and additions. We leverage this observation for end-to-end learning of low-cost (in terms of multiplications) approximations of linear operations in DNN layers. Specifically, we propose to replace matrix multiplication operations by SPNs, with widths corresponding to the budget of multiplications we want to allocate to each layer, and learning the edges of the SPNs from data. Experiments on CIFAR-10 and ImageNet show that this method applied to ResNet yields significantly higher accuracy than existing methods for a given multiplication budget, or leads to the same or higher accuracy compared to existing methods while using significantly fewer multiplications. Furthermore, our approach allows fine-grained control of the tradeoff between arithmetic complexity and accuracy of DNN models. Finally, we demonstrate that the proposed framework is able to rediscover Strassen's matrix multiplication algorithm, i.e., it can learn to multiply $2 \times 2$ matrices using only $7$ multiplications instead of $8$.

##### Abstract (translated by Google)
评估深度神经网络（DNN）所需的大部分算术运算是由于在卷积层和完全连接层中的矩阵乘法。矩阵乘法可以作为$ 2 $层和乘积网络（SPN）（算术电路），解开乘法和加法。我们利用这个观察来进行DNN层中线性运算的低成本（乘法）逼近的端到端学习。具体而言，我们建议用SPN代替矩阵乘法运算，其宽度对应于我们想要分配给每一层的乘法预算，并从数据中学习SPN的边缘。在CIFAR-10和ImageNet上的实验表明，应用于ResNet的这种方法对于给定的乘法预算产生比现有方法高得多的准确度，或者与现有方法相比或者更高精度，而使用显着更少的乘法。此外，我们的方法允许细致地控制DNN模型的算术复杂性和准确性之间的权衡。最后，我们证明了所提出的框架能够重新发现Strassen的矩阵乘法算法，即，它可以学习使用$ 7 $乘法而不是$ 8 $乘以$ 2 \ times 2 $矩阵。

##### URL
[http://arxiv.org/abs/1712.03942](http://arxiv.org/abs/1712.03942)

##### PDF
[http://arxiv.org/pdf/1712.03942](http://arxiv.org/pdf/1712.03942)

