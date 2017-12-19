---
layout: post
title: "Semantic Image Segmentation via Deep Parsing Network"
date: 2015-09-24 14:15:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Relation
author: Ziwei Liu, Xiaoxiao Li, Ping Luo, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses semantic image segmentation by incorporating rich information into Markov Random Field (MRF), including high-order relations and mixture of label contexts. Unlike previous works that optimized MRFs using iterative algorithm, we solve MRF by proposing a Convolutional Neural Network (CNN), namely Deep Parsing Network (DPN), which enables deterministic end-to-end computation in a single forward pass. Specifically, DPN extends a contemporary CNN architecture to model unary terms and additional layers are carefully devised to approximate the mean field algorithm (MF) for pairwise terms. It has several appealing properties. First, different from the recent works that combined CNN and MRF, where many iterations of MF were required for each training image during back-propagation, DPN is able to achieve high performance by approximating one iteration of MF. Second, DPN represents various types of pairwise terms, making many existing works as its special cases. Third, DPN makes MF easier to be parallelized and speeded up in Graphical Processing Unit (GPU). DPN is thoroughly evaluated on the PASCAL VOC 2012 dataset, where a single DPN model yields a new state-of-the-art segmentation accuracy.

##### Abstract (translated by Google)
本文针对语义图像分割问题，将丰富的信息融入马尔可夫随机场（Markov Random Field，MRF），包括高阶关系和标注上下文的混合。与以前使用迭代算法优化MRF的工作不同，我们通过提出卷积神经网络（CNN）即深度解析网络（DPN）来解决MRF问题，该算法能够在单个正向通道中进行确定性的端到端计算。具体而言，DPN扩展了现代CNN体系结构以模拟一元项，并且仔细设计了附加层以近似平均域算法（MF）以配对项。它有几个吸引人的属性。首先，与最近的结合CNN和MRF的工作不同，在反向传播期间，每个训练图像需要许多MF的迭代，DPN通过近似MF的一次迭代能够实现高性能。其次，DPN代表了各种各样的配对术语，使许多现有的作品成为其特例。第三，DPN使得图形处理单元（GPU）中的MF更容易并行化和加速。 DPN在PASCAL VOC 2012数据集上进行了全面评估，其中一个DPN模型产生了新的最先进的分段准确性。

##### URL
[https://arxiv.org/abs/1509.02634](https://arxiv.org/abs/1509.02634)

##### PDF
[https://arxiv.org/pdf/1509.02634](https://arxiv.org/pdf/1509.02634)

