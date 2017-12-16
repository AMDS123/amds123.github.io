---
layout: post
title: "Deep Adaptive Feature Embedding with Local Sample Distributions for Person Re-identification"
date: 2017-09-07 02:37:44
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Embedding Relation
author: Lin Wu, Yang Wang, Junbin Gao, Xue Li
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) aims to match pedestrians observed by disjoint camera views. It attracts increasing attention in computer vision due to its importance to surveillance system. To combat the major challenge of cross-view visual variations, deep embedding approaches are proposed by learning a compact feature space from images such that the Euclidean distances correspond to their cross-view similarity metric. However, the global Euclidean distance cannot faithfully characterize the ideal similarity in a complex visual feature space because features of pedestrian images exhibit unknown distributions due to large variations in poses, illumination and occlusion. Moreover, intra-personal training samples within a local range are robust to guide deep embedding against uncontrolled variations, which however, cannot be captured by a global Euclidean distance. In this paper, we study the problem of person re-id by proposing a novel sampling to mine suitable \textit{positives} (i.e. intra-class) within a local range to improve the deep embedding in the context of large intra-class variations. Our method is capable of learning a deep similarity metric adaptive to local sample structure by minimizing each sample's local distances while propagating through the relationship between samples to attain the whole intra-class minimization. To this end, a novel objective function is proposed to jointly optimize similarity metric learning, local positive mining and robust deep embedding. This yields local discriminations by selecting local-ranged positive samples, and the learned features are robust to dramatic intra-class variations. Experiments on benchmarks show state-of-the-art results achieved by our method.

##### Abstract (translated by Google)
人员重新识别（re-id）旨在匹配不相交摄像机视图观察到的行人。由于其对监控系统的重要性，它在计算机视觉领域受到越来越多的关注。为了克服交叉视觉变化的主要挑战，通过从图像学习紧凑特征空间来提出深度嵌入方法，使得欧几里得距离与它们的交叉视图相似性度量相对应。然而，全局欧氏距离不能真实地表征复杂视觉特征空间中的理想相似性，因为由于姿态，光照和遮挡的变化较大，行人图像的特征表现出未知的分布。此外，本地范围内的个人内部训练样本是强壮的，以指导深度嵌入与不受控制的变化，然而这不能被全局欧几里得距离捕获。在本文中，我们通过提出一种新的抽样方法来研究人员重复问题，以挖掘局部范围内合适的正文}（即类内），从而改善大类内部变化的深层嵌入。我们的方法能够通过最小化每个样本的局部距离，同时通过样本之间的关系传播来获得适合于局部样本结构的深度相似性度量，以实现整个类内最小化。为此，提出了一种新的目标函数来联合优化相似度度量学习，局部正向挖掘和鲁棒深度嵌入。这通过选择局部范围的正样本来产生局部的区分，并且学习到的特征对剧烈的班内变化是稳健的。基准测试显示我们的方法达到了最先进的结果。

##### URL
[https://arxiv.org/abs/1706.03160](https://arxiv.org/abs/1706.03160)

##### PDF
[https://arxiv.org/pdf/1706.03160](https://arxiv.org/pdf/1706.03160)

