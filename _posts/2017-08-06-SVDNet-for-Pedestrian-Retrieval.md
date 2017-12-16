---
layout: post
title: "SVDNet for Pedestrian Retrieval"
date: 2017-08-06 05:37:09
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Represenation_Learning Relation
author: Yifan Sun, Liang Zheng, Weijian Deng, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the SVDNet for retrieval problems, with focus on the application of person re-identification (re-ID). We view each weight vector within a fully connected (FC) layer in a convolutional neuron network (CNN) as a projection basis. It is observed that the weight vectors are usually highly correlated. This problem leads to correlations among entries of the FC descriptor, and compromises the retrieval performance based on the Euclidean distance. To address the problem, this paper proposes to optimize the deep representation learning process with Singular Vector Decomposition (SVD). Specifically, with the restraint and relaxation iteration (RRI) training scheme, we are able to iteratively integrate the orthogonality constraint in CNN training, yielding the so-called SVDNet. We conduct experiments on the Market-1501, CUHK03, and Duke datasets, and show that RRI effectively reduces the correlation among the projection vectors, produces more discriminative FC descriptors, and significantly improves the re-ID accuracy. On the Market-1501 dataset, for instance, rank-1 accuracy is improved from 55.3% to 80.5% for CaffeNet, and from 73.8% to 82.3% for ResNet-50.

##### Abstract (translated by Google)
本文提出了用于检索问题的SVDNet，重点是人的重新识别（re-ID）的应用。我们将卷积神经元网络（CNN）中完全连接（FC）层的每个权向量作为投影的基础。据观察，权重向量通常高度相关。这个问题导致了FC描述符的条目之间的相关性，并且基于欧几里得距离折衷了检索性能。针对这个问题，本文提出了利用奇异向量分解（SVD）优化深度表示学习过程。具体来说，利用约束和松弛迭代（RRI）训练方案，我们能够在CNN训练中迭代地整合正交约束，产生所谓的SVDNet。我们在Market-1501，CUHK03和Duke数据集上进行了实验，结果表明RRI有效地降低了投影向量之间的相关性，产生更多的判别性的FC描述符，并显着提高了重新识别的准确性。例如，在Market-1501数据集中，CaffeNet的rank-1准确率从55.3％提高到80.5％，ResNet-50从73.8％提高到82.3％。

##### URL
[https://arxiv.org/abs/1703.05693](https://arxiv.org/abs/1703.05693)

##### PDF
[https://arxiv.org/pdf/1703.05693](https://arxiv.org/pdf/1703.05693)

