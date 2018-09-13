---
layout: post
title: "Hyperspectral Image Classification in the Presence of Noisy Labels"
date: 2018-09-12 01:20:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Classification
author: Junjun Jiang, Jiayi Ma, Zheng Wang, Chen Chen, Xianming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Label information plays an important role in supervised hyperspectral image classification problem. However, current classification methods all ignore an important and inevitable problem---labels may be corrupted and collecting clean labels for training samples is difficult, and often impractical. Therefore, how to learn from the database with noisy labels is a problem of great practical importance. In this paper, we study the influence of label noise on hyperspectral image classification, and develop a random label propagation algorithm (RLPA) to cleanse the label noise. The key idea of RLPA is to exploit knowledge (e.g., the superpixel based spectral-spatial constraints) from the observed hyperspectral images and apply it to the process of label propagation. Specifically, RLPA first constructs a spectral-spatial probability transfer matrix (SSPTM) that simultaneously considers the spectral similarity and superpixel based spatial information. It then randomly chooses some training samples as "clean" samples and sets the rest as unlabeled samples, and propagates the label information from the "clean" samples to the rest unlabeled samples with the SSPTM. By repeating the random assignment (of "clean" labeled samples and unlabeled samples) and propagation, we can obtain multiple labels for each training sample. Therefore, the final propagated label can be calculated by a majority vote algorithm. Experimental studies show that RLPA can reduce the level of noisy label and demonstrates the advantages of our proposed method over four major classifiers with a significant margin---the gains in terms of the average OA, AA, Kappa are impressive, e.g., 9.18%, 9.58%, and 0.1043. The Matlab source code is available at https://github.com/junjun-jiang/RLPA

##### Abstract (translated by Google)
标签信息在监督的高光谱图像分类问题中起着重要作用。然而，目前的分类方法都忽略了一个重要且不可避免的问题 - 标签可能被破坏并且收集训练样本的干净标签是困难的，并且通常是不切实际的。因此，如何从带有噪声标签的数据库中学习是一个具有重要实际意义的问题。在本文中，我们研究了标签噪声对高光谱图像分类的影响，并开发了一种随机标签传播算法（RLPA）来清除标签噪声。 RLPA的关键思想是从观察到的高光谱图像中利用知识（例如，基于超像素的光谱空间约束）并将其应用于标签传播过程。具体地，RLPA首先构建光谱空间概率传递矩阵（SSPTM），其同时考虑光谱相似性和基于超像素的空间信息。然后，它随机选择一些训练样本作为“干净”样本，并将其余样本设置为未标记样本，并使用SSPTM将标签信息从“干净”样本传播到其余未标记样本。通过重复（“清洁”标记样本和未标记样本）和传播的随机分配，我们可以为每个训练样本获得多个标签。因此，最终传播的标签可以通过多数投票算法来计算。实验研究表明，RLPA可以降低噪声标签的水平，并证明了我们提出的方法优于四个主要分类器的优势 - 显着的余量 - 平均OA，AA，Kappa的增益令人印象深刻，例如，9.18％ ，9.58％和0.1043。 Matlab源代码可在https://github.com/junjun-jiang/RLPA获得

##### URL
[http://arxiv.org/abs/1809.04212](http://arxiv.org/abs/1809.04212)

##### PDF
[http://arxiv.org/pdf/1809.04212](http://arxiv.org/pdf/1809.04212)

