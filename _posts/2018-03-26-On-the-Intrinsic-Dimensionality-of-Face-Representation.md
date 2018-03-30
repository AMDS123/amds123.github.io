---
layout: post
title: "On the Intrinsic Dimensionality of Face Representation"
date: 2018-03-26 15:38:27
categories: arXiv_CV
tags: arXiv_CV Face Embedding
author: Sixue Gong, Vishnu Naresh Boddeti, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
The two underlying factors that determine the efficacy of face representations are, the embedding function to represent a face image and the dimensionality of the representation, e.g. the number of features. While the design of the embedding function has been well studied, relatively little is known about the compactness of such representations. For instance, what is the minimal number of degrees of freedom or intrinsic dimensionality of a given face representation? Can we find a mapping from the ambient representation to this minimal intrinsic space that retains it's full utility? This paper addresses both of these questions. Given a face representation, (1) we leverage intrinsic geodesic distances induced by a neighborhood graph to empirically estimate it's intrinsic dimensionality, (2) develop a neural network based non-linear mapping that transforms the ambient representation to the minimal intrinsic space of that dimensionality, and (3) validate the veracity of the mapping through face matching in the intrinsic space. Experiments on benchmark face datasets (LFW, IJB-A, IJB-B, PCSO and CASIA) indicate that, (1) the intrinsic dimensionality of deep neural network representation is significantly lower than the dimensionality of the ambient features. For instance, Facenet's 128-d representation has an intrinsic dimensionality in the range of 9-12, and (2) the neural network based mapping is able to provide face representations of significantly lower dimensionality while being as discriminative (TAR @ 0.1% FAR of 84.67%, 90.40% at 10 and 20 dimensions, respectively vs 95.50% at 128 ambient dimension on the LFW dataset) as the corresponding ambient representation.

##### Abstract (translated by Google)
决定脸部表示效果的两个基本因素是，表示脸部图像的嵌入函数和表示的维度，例如，功能的数量。尽管已经很好地研究了嵌入函数的设计，但对这种表示的紧凑性知之甚少。例如，给定人脸表征的自由度或固有维度的最小数量是多少？我们能否找到从环境表示到这个最小内在空间的映射，并保留它的全部效用？本文讨论了这两个问题。 （1）我们利用由邻域图引发的固有测地距离来经验性地估计其内在维度，（2）开发基于神经网络的非线性映射，其将环境表示转换为该维度的最小内在空间（3）通过内在空间中的人脸匹配来验证映射的准确性。对基准人脸数据集（LFW，IJB-A，IJB-B，PCSO和CASIA）的实验表明，（1）深度神经网络表征的内在维度明显低于环境特征的维度。例如，Facenet的128-d表示具有范围在9-12的固有维度，并且（2）基于神经网络的映射能够提供显着较低的维度的面部表示，同时作为区分性（TAR @ 0.1％FAR作为相应的环境表示，在10维和20维分别为84.67％，90.40％，在128维的环境维度上为95.50％）。

##### URL
[https://arxiv.org/abs/1803.09672](https://arxiv.org/abs/1803.09672)

##### PDF
[https://arxiv.org/pdf/1803.09672](https://arxiv.org/pdf/1803.09672)

