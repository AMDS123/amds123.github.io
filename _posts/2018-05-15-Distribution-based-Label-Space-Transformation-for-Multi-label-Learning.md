---
layout: post
title: "Distribution-based Label Space Transformation for Multi-label Learning"
date: 2018-05-15 10:29:01
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Relation
author: Zongting Lyu, Yan Yan, Fei Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label learning problems have manifested themselves in various machine learning applications. The key to successful multi-label learning algorithms lies in the exploration of inter-label correlations, which usually incur great computational cost. Another notable factor in multi-label learning is that the label vectors are usually extremely sparse, especially when the candidate label vocabulary is very large and only a few instances are assigned to each category. Recently, a label space transformation (LST) framework has been proposed targeting these challenges. However, current methods based on LST usually suffer from information loss in the label space dimension reduction process and fail to address the sparsity problem effectively. In this paper, we propose a distribution-based label space transformation (DLST) model. By defining the distribution based on the similarity of label vectors, a more comprehensive label structure can be captured. Then, by minimizing KL-divergence of two distributions, the information of the original label space can be approximately preserved in the latent space. Consequently, multi-label classifier trained using the dense latent codes yields better performance. The leverage of distribution enables DLST to fill out additional information about the label correlations. This endows DLST the capability to handle label set sparsity and training data sparsity in multi-label learning problems. With the optimal latent code, a kernel logistic regression function is learned for the mapping from feature space to the latent space. Then ML-KNN is employed to recover the original label vector from the transformed latent code. Extensive experiments on several benchmark datasets demonstrate that DLST not only achieves high classification performance but also is computationally more efficient.

##### Abstract (translated by Google)
多标签学习问题已经在各种机器学习应用中表现出来。成功的多标签学习算法的关键在于探索标签间相关性，这通常会带来很高的计算成本。多标签学习中另一个值得注意的因素是标签向量通常非常稀疏，特别是当候选标签词汇量非常大并且只有少数实例分配给每个类别时。最近，针对这些挑战提出了标签空间转换（LST）框架。然而，目前基于LST的方法通常会在标签空间维度降低过程中遭受信息损失，并且无法有效解决稀疏性问题。在本文中，我们提出了一个基于分布的标签空间转换（DLST）模型。通过基于标签向量的相似性定义分布，可以捕获更全面的标签结构。然后，通过最小化两个分布的KL散度，可以将原始标签空间的信息大致保存在潜在空间中。因此，使用密集的潜在代码训练的多标签分类器可以获得更好的性能。分布的杠杆作用使DLST能够填写关于标签相关性的附加信息。这赋予DLST处理多标签学习问题中标签集稀疏性和训练数据稀疏性的能力。利用最优潜在代码，从特征空间到潜在空间的映射学习到内核逻辑回归函数。然后采用ML-KNN从转换后的潜在代码中恢复原始标签向量。对几个基准数据集进行的大量实验表明，DLST不仅实现了高分类性能，而且在计算上更高效。

##### URL
[http://arxiv.org/abs/1805.05687](http://arxiv.org/abs/1805.05687)

##### PDF
[http://arxiv.org/pdf/1805.05687](http://arxiv.org/pdf/1805.05687)

