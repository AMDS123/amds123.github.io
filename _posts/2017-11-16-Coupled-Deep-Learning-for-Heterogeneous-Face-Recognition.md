---
layout: post
title: "Coupled Deep Learning for Heterogeneous Face Recognition"
date: 2017-11-16 08:48:23
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Recognition Face_Recognition
author: Xiang Wu, Lingxiao Song, Ran He, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Heterogeneous face matching is a challenge issue in face recognition due to large domain difference as well as insufficient pairwise images in different modalities during training. This paper proposes a coupled deep learning (CDL) approach for the heterogeneous face matching. CDL seeks a shared feature space in which the heterogeneous face matching problem can be approximately treated as a homogeneous face matching problem. The objective function of CDL mainly includes two parts. The first part contains a trace norm and a block-diagonal prior as relevance constraints, which not only make unpaired images from multiple modalities be clustered and correlated, but also regularize the parameters to alleviate overfitting. An approximate variational formulation is introduced to deal with the difficulties of optimizing low-rank constraint directly. The second part contains a cross modal ranking among triplet domain specific images to maximize the margin for different identities and increase data for a small amount of training samples. Besides, an alternating minimization method is employed to iteratively update the parameters of CDL. Experimental results show that CDL achieves better performance on the challenging CASIA NIR-VIS 2.0 face recognition database, the IIIT-D Sketch database, the CUHK Face Sketch (CUFS), and the CUHK Face Sketch FERET (CUFSF), which significantly outperforms state-of-the-art heterogeneous face recognition methods.

##### Abstract (translated by Google)
异构人脸匹配是人脸识别中的一个难题，由于领域差异大以及训练过程中不同模态下的成对图像不足，本文提出了一种用于异构人脸匹配的耦合深度学习（CDL）方法。 CDL寻求一个共享的特征空间，其中异构的人脸匹配问题可以被近似地视为一个同质的人脸匹配问题。 CDL的目标功能主要包括两部分。第一部分包含一个跟踪范数和一个块对角线以前的相关性约束，这不仅使得多模态的不成对图像被聚类和关联，而且调整参数来缓解过拟合。引入一个近似的变分公式来处理直接优化低秩约束的困难。第二部分包含三重域特定图像的交叉模态排序，以最大化不同身份的边缘，并增加少量训练样本的数据。此外，采用交替最小化方法迭代更新CDL的参数。实验结果表明，CDL在具有挑战性的CASIA NIR-VIS 2.0人脸识别数据库，IIIT-D素描数据库，CUHK面部素描（CUFS）和CUHK面部素描FERET（CUFSF）最先进的异构人脸识别方法。

##### URL
[https://arxiv.org/abs/1704.02450](https://arxiv.org/abs/1704.02450)

##### PDF
[https://arxiv.org/pdf/1704.02450](https://arxiv.org/pdf/1704.02450)

