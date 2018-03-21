---
layout: post
title: "Unsupervised Cross-dataset Person Re-identification by Transfer Learning of Spatial-Temporal Patterns"
date: 2018-03-20 08:33:08
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Transfer_Learning
author: Jianming Lv, Weihang Chen, Qing Li, Can Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the proposed person re-identification algorithms conduct supervised training and testing on single labeled datasets with small size, so directly deploying these trained models to a large-scale real-world camera network may lead to poor performance due to underfitting. It is challenging to incrementally optimize the models by using the abundant unlabeled data collected from the target domain. To address this challenge, we propose an unsupervised incremental learning algorithm, TFusion, which is aided by the transfer learning of the pedestrians' spatio-temporal patterns in the target domain. Specifically, the algorithm firstly transfers the visual classifier trained from small labeled source dataset to the unlabeled target dataset so as to learn the pedestrians' spatial-temporal patterns. Secondly, a Bayesian fusion model is proposed to combine the learned spatio-temporal patterns with visual features to achieve a significantly improved classifier. Finally, we propose a learning-to-rank based mutual promotion procedure to incrementally optimize the classifiers based on the unlabeled data in the target domain. Comprehensive experiments based on multiple real surveillance datasets are conducted, and the results show that our algorithm gains significant improvement compared with the state-of-art cross-dataset unsupervised person re-identification algorithms.

##### Abstract (translated by Google)
大多数提出的人重新识别算法对小尺寸的单标记数据集进行监督训练和测试，因此直接将这些训练模型部署到大规模真实世界的相机网络可能会导致由于不适合的不良性能。通过使用从目标域收集的丰富的未标记数据来逐步优化模型是具有挑战性的。为了解决这一挑战，我们提出了一种无监督增量学习算法TFusion，它通过在目标域中行人的时空模式的传递学习来提供帮助。具体来说，该算法首先将从小标记源数据集训练的视觉分类器转移到未标记的目标数据集，以便学习行人的时空模式。其次，提出了贝叶斯融合模型，将学习的时空模式与视觉特征相结合，实现了显着改善的分类器。最后，我们提出一种基于学习到秩序的相互促进过程，以基于目标域中的未标记数据递增地优化分类器。进行了基于多个实际监测数据集的综合实验，结果表明，与现有技术的跨数据集无监督人重新识别算法相比，我们的算法显着改善。

##### URL
[http://arxiv.org/abs/1803.07293](http://arxiv.org/abs/1803.07293)

##### PDF
[http://arxiv.org/pdf/1803.07293](http://arxiv.org/pdf/1803.07293)

