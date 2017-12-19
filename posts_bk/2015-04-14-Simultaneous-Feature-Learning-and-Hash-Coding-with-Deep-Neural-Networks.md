---
layout: post
title: "Simultaneous Feature Learning and Hash Coding with Deep Neural Networks"
date: 2015-04-14 03:14:24
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Hanjiang Lai, Yan Pan, Ye Liu, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity-preserving hashing is a widely-used method for nearest neighbour search in large-scale image retrieval tasks. For most existing hashing methods, an image is first encoded as a vector of hand-engineering visual features, followed by another separate projection or quantization step that generates binary codes. However, such visual feature vectors may not be optimally compatible with the coding process, thus producing sub-optimal hashing codes. In this paper, we propose a deep architecture for supervised hashing, in which images are mapped into binary codes via carefully designed deep neural networks. The pipeline of the proposed deep architecture consists of three building blocks: 1) a sub-network with a stack of convolution layers to produce the effective intermediate image features; 2) a divide-and-encode module to divide the intermediate image features into multiple branches, each encoded into one hash bit; and 3) a triplet ranking loss designed to characterize that one image is more similar to the second image than to the third one. Extensive evaluations on several benchmark image datasets show that the proposed simultaneous feature learning and hash coding pipeline brings substantial improvements over other state-of-the-art supervised or unsupervised hashing methods.

##### Abstract (translated by Google)
相似性保持散列是大规模图像检索任务中最常用的最近邻搜索方法。对于大多数现有的哈希方法，首先将图像编码为手工工程视觉特征的矢量，接着是另一个单独的投影或量化步骤，其生成二进制码。然而，这样的视觉特征向量可能不是与编码过程最佳兼容的，因此产生次最佳散列码。在本文中，我们提出了一种监督散列的深层架构，通过精心设计的深度神经网络将图像映射成二进制代码。所提出的深层架构的流水线由三个构件组成：1）具有一叠卷积层的子网络，以产生有效的中间图像特征; 2）分解和编码模块，将中间图像特征分成多个分支，每个分支编码成一个散列位;和3）三重排名损失，旨在表征一个图像更接近于第二个图像比第三个。对多个基准图像数据集的广泛评估表明，所提出的同时特征学习和散列编码流水线相对于其他现有技术的监督或无监督散列方法带来实质改进。

##### URL
[https://arxiv.org/abs/1504.03410](https://arxiv.org/abs/1504.03410)

##### PDF
[https://arxiv.org/pdf/1504.03410](https://arxiv.org/pdf/1504.03410)

