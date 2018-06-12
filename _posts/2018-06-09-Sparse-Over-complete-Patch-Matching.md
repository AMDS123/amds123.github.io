---
layout: post
title: "Sparse Over-complete Patch Matching"
date: 2018-06-09 23:18:11
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Relation
author: Akila Pemasiri, Kien Nguyen, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
Image patch matching, which is the process of identifying corresponding patches across images, has been used as a subroutine for many computer vision and image processing tasks. State -of-the-art patch matching techniques take image patches as input to a convolutional neural network to extract the patch features and evaluate their similarity. Our aim in this paper is to improve on the state of the art patch matching techniques by observing the fact that a sparse-overcomplete representation of an image posses statistical properties of natural visual scenes which can be exploited for patch matching. We propose a new paradigm which encodes image patch details by encoding the patch and subsequently using this sparse representation as input to a neural network to compare the patches. As sparse coding is based on a generative model of natural image patches, it can represent the patch in terms of the fundamental visual components from which it has been composed of, leading to similar sparse codes for patches which are built from similar components. Once the sparse coded features are extracted, we employ a fully-connected neural network, which captures the non-linear relationships between features, for comparison. We have evaluated our approach using the Liberty and Notredame subsets of the popular UBC patch dataset and set a new benchmark outperforming all state-of-the-art patch matching techniques for these datasets.

##### Abstract (translated by Google)
图像补丁匹配是识别图像中相应补丁的过程，已被用作许多计算机视觉和图像处理任务的子程序。先进的贴片匹配技术将图像块作为卷积神经网络的输入，以提取贴片特征并评估它们的相似性。我们在本文中的目标是通过观察图像的稀疏过度表示具有可用于补丁匹配的自然视觉场景的统计特性这一事实来改进现有技术的补丁匹配技术。我们提出了一种新的范例，通过对补丁进行编码来对图像补丁细节进行编码，然后使用这种稀疏表示作为神经网络的输入来比较补丁。由于稀疏编码基于自然图像补丁的生成模型，因此它可以用从其构成的基本可视化组件来表示补丁，从而导致类似的稀疏编码，用于由类似组件构建的补丁。一旦提取了稀疏编码特征，我们就采用一个全连接的神经网络来捕获特征之间的非线性关系，以便进行比较。我们使用流行的UBC补丁数据集的Liberty和Notredame子集评估了我们的方法，并为这些数据集设置了一个超越所有最新补丁匹配技术的新基准。

##### URL
[http://arxiv.org/abs/1806.03556](http://arxiv.org/abs/1806.03556)

##### PDF
[http://arxiv.org/pdf/1806.03556](http://arxiv.org/pdf/1806.03556)

