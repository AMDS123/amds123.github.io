---
layout: post
title: "Binary Constrained Deep Hashing Network for Image Retrieval without Manual Annotation"
date: 2018-08-02 00:07:21
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge Attention
author: Thanh-Toan Do, Khoa Le, Trung Pham, Tuan Hoang, Huu Le, Ngai-Man Cheung, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Learning compact binary codes for image retrieval problem using deep neural networks has attracted increasing attention recently. However, training deep hashing networks is challenging due to the binary constraints on the hash codes, the similarity preserving property, and the requirement for a vast amount of labelled images. To the best of our knowledge, none of the existing methods has tackled all of these challenges completely in a unified framework. In this work, we propose a novel end-to-end deep hashing approach, which is trained to produce binary codes directly from image pixels without the need of manual annotation. In particular, we propose a novel pairwise binary constrained loss function, which simultaneously encodes the distances between pairs of hash codes, and the binary quantization error. In order to train the network with the proposed loss function, we also propose an efficient parameter learning algorithm. In addition, to provide similar/dissimilar training images to train the network, we exploit 3D models reconstructed from unlabelled images for automatic generation of enormous similar/dissimilar pairs. Extensive experiments on three image retrieval benchmark datasets demonstrate the superior performance of the proposed method over the state-of-the-art hashing methods on the image retrieval problem.

##### Abstract (translated by Google)
使用深度神经网络学习用于图像检索问题的紧凑二进制码最近引起了越来越多的关然而，由于哈希码的二元约束，相似性保持特性以及对大量标记图像的需求，训练深度哈希网络具有挑战性。据我们所知，现有方法都没有完全在统一框架内解决所有这些挑战。在这项工作中，我们提出了一种新颖的端到端深度哈希方法，该方法经过训练，可以直接从图像像素生成二进制代码，而无需手动注释。特别地，我们提出了一种新颖的成对二进制约束损失函数，其同时编码散列码对之间的距离和二进制量化误差。为了利用所提出的损失函数训练网络，我们还提出了一种有效的参数学习算法。此外，为了提供相似/不相似的训练图像来训练网络，我们利用从未标记图像重建的3D模型来自动生成巨大的相似/不相似的对。对三个图像检索基准数据集的广泛实验证明了所提出的方法相对于图像检索问题的最先进的哈希方法的优越性能。

##### URL
[http://arxiv.org/abs/1802.07437](http://arxiv.org/abs/1802.07437)

##### PDF
[http://arxiv.org/pdf/1802.07437](http://arxiv.org/pdf/1802.07437)

