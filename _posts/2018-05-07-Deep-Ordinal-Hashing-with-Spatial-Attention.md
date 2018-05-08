---
layout: post
title: "Deep Ordinal Hashing with Spatial Attention"
date: 2018-05-07 11:59:55
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention CNN Relation
author: Lu Jin, Xiangbo Shu, Kai Li, Zechao Li, Guo-Jun Qi, Jinhui Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing has attracted increasing research attentions in recent years due to its high efficiency of computation and storage in image retrieval. Recent works have demonstrated the superiority of simultaneous feature representations and hash functions learning with deep neural networks. However, most existing deep hashing methods directly learn the hash functions by encoding the global semantic information, while ignoring the local spatial information of images. The loss of local spatial structure makes the performance bottleneck of hash functions, therefore limiting its application for accurate similarity retrieval. In this work, we propose a novel Deep Ordinal Hashing (DOH) method, which learns ordinal representations by leveraging the ranking structure of feature space from both local and global views. In particular, to effectively build the ranking structure, we propose to learn the rank correlation space by exploiting the local spatial information from Fully Convolutional Network (FCN) and the global semantic information from the Convolutional Neural Network (CNN) simultaneously. More specifically, an effective spatial attention model is designed to capture the local spatial information by selectively learning well-specified locations closely related to target objects. In such hashing framework,the local spatial and global semantic nature of images are captured in an end-to-end ranking-to-hashing manner. Experimental results conducted on three widely-used datasets demonstrate that the proposed DOH method significantly outperforms the state-of-the-art hashing methods.

##### Abstract (translated by Google)
由于哈希算法在图像检索中具有很高的计算和存储效率，近年来已经引起越来越多的研究关注。最近的研究已经证明了用深度神经网络学习同时特征表示和散列函数的优越性。然而，大多数现有的深度哈希方法通过编码全局语义信息直接学习哈希函数，而忽略图像的局部空间信息。局部空间结构的损失使得哈希函数的性能瓶颈，因此限制了它在精确相似度检索中的应用。在这项工作中，我们提出了一种新的深度序数散列（DOH）方法，它通过利用来自本地和全局视图的特征空间的排序结构来学习序数表示。具体而言，为了有效建立排序结构，我们提出通过利用全卷积网络（FCN）的局部空间信息和卷积神经网络（CNN）的全局语义信息同时学习等级相关空间。更具体地说，有效的空间关注模型被设计为通过选择性地学习与目标物体紧密相关的指定好的位置来捕捉局部空间信息。在这样的哈希框架中，图像的局部空间和全局语义特性以端到端的排序到哈希方式被捕获。在三个广泛使用的数据集上进行的实验结果表明，所提出的DOH方法明显优于最先进的哈希方法。

##### URL
[http://arxiv.org/abs/1805.02459](http://arxiv.org/abs/1805.02459)

##### PDF
[http://arxiv.org/pdf/1805.02459](http://arxiv.org/pdf/1805.02459)

