---
layout: post
title: "Exploring Linear Relationship in Feature Map Subspace for ConvNets Compression"
date: 2018-03-15 13:20:16
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Dong Wang, Lei Zhou, Xueni Zhang, Xiao Bai, Jun Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
While the research on convolutional neural networks (CNNs) is progressing quickly, the real-world deployment of these models is often limited by computing resources and memory constraints. In this paper, we address this issue by proposing a novel filter pruning method to compress and accelerate CNNs. Our work is based on the linear relationship identified in different feature map subspaces via visualization of feature maps. Such linear relationship implies that the information in CNNs is redundant. Our method eliminates the redundancy in convolutional filters by applying subspace clustering to feature maps. In this way, most of the representative information in the network can be retained in each cluster. Therefore, our method provides an effective solution to filter pruning for which most existing methods directly remove filters based on simple heuristics. The proposed method is independent of the network structure, thus it can be adopted by any off-the-shelf deep learning libraries. Experiments on different networks and tasks show that our method outperforms existing techniques before fine-tuning, and achieves the state-of-the-art results after fine-tuning.

##### Abstract (translated by Google)
虽然卷积神经网络（CNN）的研究进展很快，但这些模型的实际部署往往受计算资源和内存限制的限制。在本文中，我们通过提出一种新颖的滤波器修剪方法来压缩和加速CNN来解决这个问题。我们的工作基于通过可视化特征映射在不同特征映射子空间中标识的线性关系。这种线性关系意味着CNN中的信息是多余的。我们的方法通过将子空间聚类应用于特征映射来消除卷积滤波器中的冗余。这样，网络中的大多数代表性信息都可以保留在每个群集中。因此，我们的方法提供了一个有效的解决方案来筛选修剪，大多数现有方法都是基于简单的启发式直接删除过滤器。所提出的方法独立于网络结构，因此它可以被任何现成的深度学习库采用。在不同的网络和任务上进行的实验表明，我们的方法在微调之前胜过现有的技术，并在微调之后达到最新的结果。

##### URL
[https://arxiv.org/abs/1803.05729](https://arxiv.org/abs/1803.05729)

##### PDF
[https://arxiv.org/pdf/1803.05729](https://arxiv.org/pdf/1803.05729)

