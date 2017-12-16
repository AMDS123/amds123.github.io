---
layout: post
title: "Close Yet Distinctive Domain Adaptation"
date: 2017-04-13 08:30:21
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification
author: Lingkun Luo, Xiaofang Wang, Shiqiang Hu, Chao Wang, Yuxing Tang, Liming Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation is transfer learning which aims to generalize a learning model across training and testing data with different distributions. Most previous research tackle this problem in seeking a shared feature representation between source and target domains while reducing the mismatch of their data distributions. In this paper, we propose a close yet discriminative domain adaptation method, namely CDDA, which generates a latent feature representation with two interesting properties. First, the discrepancy between the source and target domain, measured in terms of both marginal and conditional probability distribution via Maximum Mean Discrepancy is minimized so as to attract two domains close to each other. More importantly, we also design a repulsive force term, which maximizes the distances between each label dependent sub-domain to all others so as to drag different class dependent sub-domains far away from each other and thereby increase the discriminative power of the adapted domain. Moreover, given the fact that the underlying data manifold could have complex geometric structure, we further propose the constraints of label smoothness and geometric structure consistency for label propagation. Extensive experiments are conducted on 36 cross-domain image classification tasks over four public datasets. The comprehensive results show that the proposed method consistently outperforms the state-of-the-art methods with significant margins.

##### Abstract (translated by Google)
领域适应是转移学习，旨在将训练和测试数据的学习模型推广到不同的分布。大多数以前的研究都是在寻找源域和目标域之间的共享特征表示的同时，减少数据分布的不匹配，从而解决这个问题。在本文中，我们提出了一个紧密而有区别的领域适应方法，即CDDA，它产生了一个具有两个有趣特性的潜在特征表示。首先，通过最大均值偏差（Mean Mean Discrepancy）以边际和条件概率分布的形式测量的源域和目标域之间的差异被最小化，以便吸引两个彼此靠近的域。更重要的是，我们还设计了一个排斥力项，它使每个标签从属子域到所有其他子域之间的距离达到最大，从而将不同的依赖于类别的子域彼此拉开，从而增加了自适应域的判别能力。而且，由于底层数据流形可能具有复杂的几何结构，因此我们进一步提出了标签传播中标签平滑度和几何结构一致性的约束条件。对四个公共数据集上的36个跨域图像分类任务进行了大量的实验。综合结果表明，所提出的方法始终优于最先进的方法，并具有显着的利润率。

##### URL
[https://arxiv.org/abs/1704.04235](https://arxiv.org/abs/1704.04235)

##### PDF
[https://arxiv.org/pdf/1704.04235](https://arxiv.org/pdf/1704.04235)

