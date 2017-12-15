---
layout: post
title: "A Distributed Deep Representation Learning Model for Big Image Data Classification"
date: 2016-07-02 12:33:12
categories: arXiv_CV
tags: arXiv_CV Image_Classification Represenation_Learning Classification Deep_Learning
author: Le Dong, Na Lv, Qianni Zhang, Shanshan Xie, Ling He, Mengdie Mao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes an effective and efficient image classification framework nominated distributed deep representation learning model (DDRL). The aim is to strike the balance between the computational intensive deep learning approaches (tuned parameters) which are intended for distributed computing, and the approaches that focused on the designed parameters but often limited by sequential computing and cannot scale up. In the evaluation of our approach, it is shown that DDRL is able to achieve state-of-art classification accuracy efficiently on both medium and large datasets. The result implies that our approach is more efficient than the conventional deep learning approaches, and can be applied to big data that is too complex for parameter designing focused approaches. More specifically, DDRL contains two main components, i.e., feature extraction and selection. A hierarchical distributed deep representation learning algorithm is designed to extract image statistics and a nonlinear mapping algorithm is used to map the inherent statistics into abstract features. Both algorithms are carefully designed to avoid millions of parameters tuning. This leads to a more compact solution for image classification of big data. We note that the proposed approach is designed to be friendly with parallel computing. It is generic and easy to be deployed to different distributed computing resources. In the experiments, the largescale image datasets are classified with a DDRM implementation on Hadoop MapReduce, which shows high scalability and resilience.

##### Abstract (translated by Google)
本文描述了一个有效和高效的图像分类框架提名分布深度表示学习模型（DDRL）。其目的是在用于分布式计算的计算密集型深度学习方法（调整参数）与着眼于设计参数但常常受限于顺序计算并且不能扩展的方法之间取得平衡。在对我们的方法进行评估时，DDRL能够在大中型数据集上高效地获得最先进的分类准确性。结果意味着我们的方法比传统的深度学习方法更有效率，并且可以应用于对于参数设计重点方法来说太复杂的大数据。更具体地说，DDRL包含两个主要部分，即特征提取和选择。设计了一种分层分布深度表示学习算法来提取图像统计量，并采用非线性映射算法将内在统计量映射为抽象特征。这两种算法都经过精心设计，以避免数百万个参数的调整这导致了大数据图像分类的更紧凑的解决方案。我们注意到，所提出的方法被设计为与并行计算友好。它是通用的，易于部署到不同的分布式计算资源。在实验中，大规模的图像数据集在Hadoop MapReduce上进行了DDRM实现，具有很高的可伸缩性和弹性。

##### URL
[https://arxiv.org/abs/1607.00501](https://arxiv.org/abs/1607.00501)

##### PDF
[https://arxiv.org/pdf/1607.00501](https://arxiv.org/pdf/1607.00501)

