---
layout: post
title: "Embedding Deep Metric for Person Re-identication A Study Against Large Variations"
date: 2016-11-01 06:03:48
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding CNN Relation
author: Hailin Shi, Yang Yang, Xiangyu Zhu, Shengcai Liao, Zhen Lei, Weishi Zheng, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification is challenging due to the large variations of pose, illumination, occlusion and camera view. Owing to these variations, the pedestrian data is distributed as highly-curved manifolds in the feature space, despite the current convolutional neural networks (CNN)'s capability of feature extraction. However, the distribution is unknown, so it is difficult to use the geodesic distance when comparing two samples. In practice, the current deep embedding methods use the Euclidean distance for the training and test. On the other hand, the manifold learning methods suggest to use the Euclidean distance in the local range, combining with the graphical relationship between samples, for approximating the geodesic distance. From this point of view, selecting suitable positive i.e. intra-class) training samples within a local range is critical for training the CNN embedding, especially when the data has large intra-class variations. In this paper, we propose a novel moderate positive sample mining method to train robust CNN for person re-identification, dealing with the problem of large variation. In addition, we improve the learning by a metric weight constraint, so that the learned metric has a better generalization ability. Experiments show that these two strategies are effective in learning robust deep metrics for person re-identification, and accordingly our deep model significantly outperforms the state-of-the-art methods on several benchmarks of person re-identification. Therefore, the study presented in this paper may be useful in inspiring new designs of deep models for person re-identification.

##### Abstract (translated by Google)
由于姿态，照明，遮挡和摄像机视图的大的变化，人重新识别是具有挑战性的。由于这些变化，尽管目前的卷积神经网络（CNN）的特征提取能力，行人数据在特征空间中分布为高度弯曲的流形。然而，分布是未知的，所以在比较两个样本时难以使用测地距离。在实践中，目前的深度嵌入方法使用欧氏距离进行训练和测试。另一方面，流形学习方法建议使用局部范围内的欧几里德距离，结合样本间的图形关系来近似测地距离。从这个角度来看，在本地范围内选择合适的正的，即类别内的训练样本对于训练CNN嵌入是关键的，特别是当数据具有较大的类内变化时。在本文中，我们提出了一种新的中等正样本挖掘方法来训练鲁棒CNN的人重新识别，处理大变化的问题。此外，我们通过一个度量权重约束来改进学习，使得学习的度量具有更好的泛化能力。实验表明，这两种策略在学习人类再识别的深度指标方面是有效的，相应地，我们的深度模型在人类再识别的几个基准上明显优于最先进的方法。因此，本文提出的研究可能有助于激发人体再识别深层模型的新设计。

##### URL
[https://arxiv.org/abs/1611.00137](https://arxiv.org/abs/1611.00137)

##### PDF
[https://arxiv.org/pdf/1611.00137](https://arxiv.org/pdf/1611.00137)

