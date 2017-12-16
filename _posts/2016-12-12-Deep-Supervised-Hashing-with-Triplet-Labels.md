---
layout: post
title: "Deep Supervised Hashing with Triplet Labels"
date: 2016-12-12 20:56:38
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Xiaofang Wang, Yi Shi, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing is one of the most popular and powerful approximate nearest neighbor search techniques for large-scale image retrieval. Most traditional hashing methods first represent images as off-the-shelf visual features and then produce hashing codes in a separate stage. However, off-the-shelf visual features may not be optimally compatible with the hash code learning procedure, which may result in sub-optimal hash codes. Recently, deep hashing methods have been proposed to simultaneously learn image features and hash codes using deep neural networks and have shown superior performance over traditional hashing methods. Most deep hashing methods are given supervised information in the form of pairwise labels or triplet labels. The current state-of-the-art deep hashing method DPSH~\cite{li2015feature}, which is based on pairwise labels, performs image feature learning and hash code learning simultaneously by maximizing the likelihood of pairwise similarities. Inspired by DPSH~\cite{li2015feature}, we propose a triplet label based deep hashing method which aims to maximize the likelihood of the given triplet labels. Experimental results show that our method outperforms all the baselines on CIFAR-10 and NUS-WIDE datasets, including the state-of-the-art method DPSH~\cite{li2015feature} and all the previous triplet label based deep hashing methods.

##### Abstract (translated by Google)
哈希是用于大规模图像检索的最流行和强大的近似最近邻搜索技术之一。大多数传统的散列方法首先将图像表示为现成的视觉特征，然后在单独的阶段产生散列码。然而，现成的视觉特征可能不是最佳地与哈希码学习过程兼容，这可能导致次最佳哈希码。近来，已经提出了使用深度神经网络同时学习图像特征和哈希码的深度哈希方法，并且已经表现出优于传统哈希方法的优越性能。大多数深度哈希方法以成对标签或三重标签的形式给出监督信息。目前最先进的基于成对标签的深度哈希方法DPSH〜\ cite {feature}通过最大化两两相似的可能性同时进行图像特征学习和哈希码学习。受到DPSH的启发，我们提出了一种基于三重标签的深度散列方法，旨在最大化给定三重标签的可能性。实验结果表明，我们的方法优于CIFAR-10和NUS-WIDE数据集的所有基线，包括最先进的方法DPSH_cite {li2015feature}以及所有基于三重标记的深度哈希方法。

##### URL
[https://arxiv.org/abs/1612.03900](https://arxiv.org/abs/1612.03900)

##### PDF
[https://arxiv.org/pdf/1612.03900](https://arxiv.org/pdf/1612.03900)

