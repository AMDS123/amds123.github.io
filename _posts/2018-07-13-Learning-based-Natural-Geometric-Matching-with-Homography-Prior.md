---
layout: post
title: "Learning-based Natural Geometric Matching with Homography Prior"
date: 2018-07-13 15:01:02
categories: arXiv_CV
tags: arXiv_CV Relation
author: Yifang Xu, Tianli Liao, Jing Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Geometric matching is a key step in computer vision tasks. Previous learning-based methods for geometric matching concentrate more on improving alignment quality, while we argue the importance of naturalness issue simultaneously. To deal with this, firstly, Pearson correlation is applied to handle large intra-class variations of features in feature matching stage. Then, we parametrize homography transformation with 9 parameters in full connected layer of our network, to better characterize large viewpoint variations compared with affine transformation. Furthermore, a novel loss function with Gaussian weights guarantees the model accuracy and efficiency in training procedure. Finally, we provide two choices for different purposes in geometric matching. When compositing homography with affine transformation, the alignment accuracy improves and all lines are preserved, which results in a more natural transformed image. When compositing homography with non-rigid thin-plate-spline transformation, the alignment accuracy further improves. Experimental results on Proposal Flow dataset show that our method outperforms state-of-the-art methods, both in terms of alignment accuracy and naturalness.

##### Abstract (translated by Google)
几何匹配是计算机视觉任务中的关键步骤。以前基于学习的几何匹配方法更多地集中于提高对齐质量，而我们同时认为自然问题的重要性。为了解决这个问题，首先，应用Pearson相关来处理特征匹配阶段中特征的大型内部变化。然后，我们在网络的全连通层中使用9个参数对单应性变换进行参数化，以更好地表征与仿射变换相比的大视点变化。此外，具有高斯权重的新型损失函数保证了训练过程中的模型准确性和效率。最后，我们在几何匹配中提供了两种不同用途的选择。当使用仿射变换合成单应性时，对准精度提高并且所有线都被保留，这导致更自然的变换图像。当使用非刚性薄板样条变换合成单应性时，对准精度进一步提高。 Proposal Flow数据集的实验结果表明，我们的方法在对齐精度和自然度方面均优于最先进的方法。

##### URL
[http://arxiv.org/abs/1807.05119](http://arxiv.org/abs/1807.05119)

##### PDF
[http://arxiv.org/pdf/1807.05119](http://arxiv.org/pdf/1807.05119)

