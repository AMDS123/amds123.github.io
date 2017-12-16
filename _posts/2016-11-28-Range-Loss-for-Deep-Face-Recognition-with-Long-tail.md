---
layout: post
title: "Range Loss for Deep Face Recognition with Long-tail"
date: 2016-11-28 03:41:46
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Recognition Face_Recognition
author: Xiao Zhang, Zhiyuan Fang, Yandong Wen, Zhifeng Li, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have achieved great improvement on face recognition in recent years because of its extraordinary ability in learning discriminative features of people with different identities. To train such a well-designed deep network, tremendous amounts of data is indispensable. Long tail distribution specifically refers to the fact that a small number of generic entities appear frequently while other objects far less existing. Considering the existence of long tail distribution of the real world data, large but uniform distributed data are usually hard to retrieve. Empirical experiences and analysis show that classes with more samples will pose greater impact on the feature learning process and inversely cripple the whole models feature extracting ability on tail part data. Contrary to most of the existing works that alleviate this problem by simply cutting the tailed data for uniform distributions across the classes, this paper proposes a new loss function called range loss to effectively utilize the whole long tailed data in training process. More specifically, range loss is designed to reduce overall intra-personal variations while enlarging inter-personal differences within one mini-batch simultaneously when facing even extremely unbalanced data. The optimization objective of range loss is the $k$ greatest range's harmonic mean values in one class and the shortest inter-class distance within one batch. Extensive experiments on two famous and challenging face recognition benchmarks (Labeled Faces in the Wild (LFW) and YouTube Faces (YTF) not only demonstrate the effectiveness of the proposed approach in overcoming the long tail effect but also show the good generalization ability of the proposed approach.

##### Abstract (translated by Google)
卷积神经网络在近年来在人脸识别方面取得了很大的进步，因为它具有学习不同身份人群识别特征的非凡能力。为了培养如此精心设计的深层网络，大量的数据是不可或缺的。长尾分布具体指的是这样一个事实，即少数通用实体频繁出现，而其他对象则远不如现在。考虑到现实世界数据的长尾分布的存在，大而均匀的分布式数据通常难以检索。实验的经验和分析表明，样本数量多的样本会对特征学习过程产生较大的影响，反而削弱了尾部数据的整体模型特征提取能力。与大多数现有的减少这个问题的工作相比，通过简单地将尾部数据剪切成均匀分布的类，本文提出了一种新的损失函数，称为距离损失，有效地利用了整个长尾数据的训练过程。更具体地说，范围损失旨在减少整体的个人内部变化，同时在面对极其不平衡的数据时同时扩大一个小批量内的个人间差异。范围损失的优化目标是一个类别中$ k $最大范围的谐波平均值和一个批次内最短的类间距离。在两个着名的具有挑战性的人脸识别基准（野外标记的脸部（LFW）和YouTube脸部（YTF））上的广泛实验不仅证明了所提出的方法克服长尾效应的有效性，做法。

##### URL
[https://arxiv.org/abs/1611.08976](https://arxiv.org/abs/1611.08976)

##### PDF
[https://arxiv.org/pdf/1611.08976](https://arxiv.org/pdf/1611.08976)

