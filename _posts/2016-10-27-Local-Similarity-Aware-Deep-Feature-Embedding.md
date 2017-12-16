---
layout: post
title: "Local Similarity-Aware Deep Feature Embedding"
date: 2016-10-27 17:51:18
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN Transfer_Learning
author: Chen Huang, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep embedding methods in vision tasks are capable of learning a compact Euclidean space from images, where Euclidean distances correspond to a similarity metric. To make learning more effective and efficient, hard sample mining is usually employed, with samples identified through computing the Euclidean feature distance. However, the global Euclidean distance cannot faithfully characterize the true feature similarity in a complex visual feature space, where the intraclass distance in a high-density region may be larger than the interclass distance in low-density regions. In this paper, we introduce a Position-Dependent Deep Metric (PDDM) unit, which is capable of learning a similarity metric adaptive to local feature structure. The metric can be used to select genuinely hard samples in a local neighborhood to guide the deep embedding learning in an online and robust manner. The new layer is appealing in that it is pluggable to any convolutional networks and is trained end-to-end. Our local similarity-aware feature embedding not only demonstrates faster convergence and boosted performance on two complex image retrieval datasets, its large margin nature also leads to superior generalization results under the large and open set scenarios of transfer learning and zero-shot learning on ImageNet 2010 and ImageNet-10K datasets.

##### Abstract (translated by Google)
视觉任务中的现有深度嵌入方法能够从图像学习紧凑的欧几里得空间，其中欧几里得距离对应于相似性度量。为了使学习更加有效和高效，通常采用硬采样挖掘，通过计算欧几里得特征距离来识别样本。然而，全局欧氏距离不能真实地刻画复杂视觉特征空间中的真实特征相似性，其中高密度区域内的类内距离可能大于低密度区域内的类间距离。在本文中，我们引入了一个位置相关深度量（PDDM）单元，它能够学习一个适合局部特征结构的相似性度量。该度量可以用来选择本地邻域中的真实硬样本，以在线和稳健的方式指导深度嵌入学习。这个新层面具有吸引力，因为它可以连接到任何卷积网络，并且是端到端的训练。我们的局部相似感知特征嵌入不仅在两个复杂的图像检索数据集上展现了更快的收敛性和更好的性能，而且它的大幅度的性质也导致了在ImageNet 2010上的转移学习和零点学习的大而开放的场景下更好的泛化结果和ImageNet-10K数据集。

##### URL
[https://arxiv.org/abs/1610.08904](https://arxiv.org/abs/1610.08904)

##### PDF
[https://arxiv.org/pdf/1610.08904](https://arxiv.org/pdf/1610.08904)

