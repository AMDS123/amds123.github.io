---
layout: post
title: "PN-Net: Conjoined Triple Deep Network for Learning Local Image Descriptors"
date: 2016-01-19 18:29:09
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Vassileios Balntas, Edward Johns, Lilian Tang, Krystian Mikolajczyk
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new approach for learning local descriptors for matching image patches. It has recently been demonstrated that descriptors based on convolutional neural networks (CNN) can significantly improve the matching performance. Unfortunately their computational complexity is prohibitive for any practical application. We address this problem and propose a CNN based descriptor with improved matching performance, significantly reduced training and execution time, as well as low dimensionality. We propose to train the network with triplets of patches that include a positive and negative pairs. To that end we introduce a new loss function that exploits the relations within the triplets. We compare our approach to recently introduced MatchNet and DeepCompare and demonstrate the advantages of our descriptor in terms of performance, memory footprint and speed i.e. when run in GPU, the extraction time of our 128 dimensional feature is comparable to the fastest available binary descriptors such as BRIEF and ORB.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来学习匹配图像块的局部描述符。最近已经证明，基于卷积神经网络（CNN）的描述符可以显着提高匹配性能。不幸的是，它们的计算复杂度对于任何实际的应用都是不可接受的我们解决这个问题，并提出了一个改进的匹配性能的CNN描述符，显着减少训练和执行时间，以及低维度。我们建议使用包含正负对的补丁三元组来训练网络。为此，我们引入一个新的损失函数，利用三元组内的关系。我们将我们的方法与最近引入的MatchNet和DeepCompare进行了比较，并展示了我们的描述符在性能，内存占用和速度方面的优势，即在GPU中运行时，我们的128维特征的提取时间可与最快的可用二进制描述符简述和ORB。

##### URL
[https://arxiv.org/abs/1601.05030](https://arxiv.org/abs/1601.05030)

##### PDF
[https://arxiv.org/pdf/1601.05030](https://arxiv.org/pdf/1601.05030)

