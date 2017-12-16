---
layout: post
title: "Rethinking Feature Discrimination and Polymerization for Large-scale Recognition"
date: 2017-10-29 12:37:40
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Yu Liu, Hongyang Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Feature matters. How to train a deep network to acquire discriminative features across categories and polymerized features within classes has always been at the core of many computer vision tasks, specially for large-scale recognition systems where test identities are unseen during training and the number of classes could be at million scale. In this paper, we address this problem based on the simple intuition that the cosine distance of features in high-dimensional space should be close enough within one class and far away across categories. To this end, we proposed the congenerous cosine (COCO) algorithm to simultaneously optimize the cosine similarity among data. It inherits the softmax property to make inter-class features discriminative as well as shares the idea of class centroid in metric learning. Unlike previous work where the center is a temporal, statistical variable within one mini-batch during training, the formulated centroid is responsible for clustering inner-class features to enforce them polymerized around the network truncus. COCO is bundled with discriminative training and learned end-to-end with stable convergence. Experiments on five benchmarks have been extensively conducted to verify the effectiveness of our approach on both small-scale classification task and large-scale human recognition problem.

##### Abstract (translated by Google)
功能很重要。如何训练一个深度网络来获取跨类别和聚类特征的区分特征一直是许多计算机视觉任务的核心，尤其是对于大规模识别系统，在训练期间测试身份是不可见的，而且类别数量可能是以百万计。在本文中，我们基于简单的直觉来解决这个问题，高维空间中的特征的余弦距离应该在一个类中足够接近并且在类别之间很远。为此，我们提出了同余余弦（COCO）算法来同时优化数据间的余弦相似性。它继承了softmax属性，使类间特征具有判别性，并在度量学习中共享类中心的思想。与以前的工作中，中心是训练期间的一个小批量内的时间统计变量，制定的质心负责对内部类别特征进行聚类，以强制它们在网络周围聚合。 COCO与歧视性训练捆绑在一起，学习端到端，稳定收敛。为了验证我们的方法在小规模分类任务和大规模人类识别问题上的有效性，已经广泛地进行了五个基准的实验。

##### URL
[https://arxiv.org/abs/1710.00870](https://arxiv.org/abs/1710.00870)

##### PDF
[https://arxiv.org/pdf/1710.00870](https://arxiv.org/pdf/1710.00870)

