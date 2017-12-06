---
layout: post
title: 'Structured Deep Hashing with Convolutional Neural Networks for Fast Person Re-identification'
date: 2017-12-03 02:41:08
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Lin Wu, Yang Wang
---

* content
{:toc}

##### Abstract
Given a pedestrian image as a query, the purpose of person re-identification is to identify the correct match from a large collection of gallery images depicting the same person captured by disjoint camera views. The critical challenge is how to construct a robust yet discriminative feature representation to capture the compounded variations in pedestrian appearance. To this end, deep learning methods have been proposed to extract hierarchical features against extreme variability of appearance. However, existing methods in this category generally neglect the efficiency in the matching stage whereas the searching speed of a re-identification system is crucial in real-world applications. In this paper, we present a novel deep hashing framework with Convolutional Neural Networks (CNNs) for fast person re-identification. Technically, we simultaneously learn both CNN features and hash functions/codes to get robust yet discriminative features and similarity-preserving hash codes. Thereby, person re-identification can be resolved by efficiently computing and ranking the Hamming distances between images. A structured loss function defined over positive pairs and hard negatives is proposed to formulate a novel optimization problem so that fast convergence and more stable optimized solution can be obtained. Extensive experiments on two benchmarks CUHK03 \cite{FPNN} and Market-1501 \cite{Market1501} show that the proposed deep architecture is efficacy over state-of-the-arts.

##### Abstract (translated by Google)
给定行人图像作为查询，人物重新识别的目的是从大量的画廊图像中确定正确的匹配，描绘由不相交的摄像机视图捕获的同一个人。关键的挑战是如何构建一个强大而有区别的特征表示来捕捉行人外观的复杂变化。为此，已经提出了深度学习方法来提取针对外观的极端可变性的分层特征。但是，现有的这种方法一般忽略了匹配阶段的效率，而重新识别系统的搜索速度在现实应用中是至关重要的。在本文中，我们提出了一个新的深度哈希框架与卷积神经网络（CNNs）快速的人重新识别。从技术上讲，我们同时学习CNN特征和哈希函数/代码，以获得鲁棒性，但有区别的特征和相似性保持哈希码。因此，通过有效地计算和排列图像之间的汉明距离，可以解决人重新识别问题。提出了一个在正对和负向上定义的结构损失函数，用来形成一个新的优化问题，从而得到快速收敛和更稳定的最优解。在两个基准CUHK03 \ cite {FPNN}和Market-1501 \ cite {Market1501}上进行的大量实验表明，所提出的深层架构的效能优于现有技术。

##### URL
[http://arxiv.org/abs/1702.04179](http://arxiv.org/abs/1702.04179)

