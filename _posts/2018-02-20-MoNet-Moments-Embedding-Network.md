---
layout: post
title: "MoNet: Moments Embedding Network"
date: 2018-02-20 19:54:58
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification
author: Mengran Gou, Fei Xiong, Octavia Camps, Mario Sznaier
mathjax: true
---

* content
{:toc}

##### Abstract
Bilinear pooling has been recently proposed as a feature encoding layer, which can be used after the convolutional layers of a deep network, to improve performance in multiple vision tasks. Instead of conventional global average pooling or fully connected layer, bilinear pooling gathers 2nd order information in a translation invariant fashion. However, a serious drawback of this family of pooling layers is their dimensionality explosion. Approximate pooling methods with compact property have been explored towards resolving this weakness. Additionally, recent results have shown that significant performance gains can be achieved by using matrix normalization to regularize unstable higher order information. However, combining compact pooling with matrix normalization has not been explored until now. 
 In this paper, we unify the bilinear pooling layer and the global Gaussian embedding layer through the empirical moment matrix. In addition, with a proposed novel sub-matrix square-root layer, one can normalize the output of the convolution layer directly and mitigate the dimensionality problem with off-the-shelf compact pooling methods. Our experiments on three widely used fine-grained classification datasets illustrate that our proposed architecture MoNet can achieve similar or better performance than G2DeNet . When combined with compact pooling technique, it obtains comparable performance with the encoded feature of 96% less dimensions.

##### Abstract (translated by Google)
双线性池最近被提出作为一种特征编码层，它可以在深度网络的卷积层之后使用，以提高多视觉任务的性能。双线性汇集不是以传统的全局平均汇集或完全连接的层，而是以平移不变方式收集二阶信息。然而，这个汇聚层家族的一个严重缺点是它们的维数爆炸。为了解决这个弱点，已经探索了具有紧凑性的近似池化方法。此外，最近的结果表明，通过使用矩阵归一化来调整不稳定的高阶信息，可以实现显着的性能增益。但是，直到现在还没有探索将紧凑池与矩阵规范化结合起来。
 在本文中，我们通过经验矩矩阵来统一双线性汇聚层和全局高斯嵌入层。另外，利用提出的新颖的子矩阵平方根层，可以直接规范卷积层的输出，并通过现成的紧凑池方法来缓解维数问题。我们在三个广泛使用的细粒度分类数据集上的实验表明，我们提出的架构MoNet可以实现与G2DeNet相似或更好的性能。当与紧凑池技术相结合时，它可以获得与96％以下尺寸编码特征相当的性能。

##### URL
[http://arxiv.org/abs/1802.07303](http://arxiv.org/abs/1802.07303)

##### PDF
[http://arxiv.org/pdf/1802.07303](http://arxiv.org/pdf/1802.07303)

