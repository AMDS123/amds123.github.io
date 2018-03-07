---
layout: post
title: "Comparison of Deep Learning Approaches for Multi-Label Chest X-Ray Classification"
date: 2018-03-06 18:04:25
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Deep_Learning Relation
author: Ivo M. Baltruschat, Hannes Nickisch, Michael Grass, Tobias Knopp, Axel Saalbach
mathjax: true
---

* content
{:toc}

##### Abstract
The increased availability of X-ray image archives (e.g. the ChestX-ray14 dataset from the NIH Clinical Center) has triggered a growing interest in deep learning techniques. To provide better insight into the different approaches, and their applications to chest X-ray classification, we investigate a powerful network architecture in detail: the ResNet-50. Building on prior work in this domain, we consider transfer learning with and without fine-tuning as well as the training of a dedicated X-ray network from scratch. To leverage the high spatial resolutions of X-ray data, we also include an extended ResNet-50 architecture, and a network integrating non-image data (patient age, gender and acquisition type) in the classification process. In a systematic evaluation, using 5-fold re-sampling and a multi-label loss function, we evaluate the performance of the different approaches for pathology classification by ROC statistics and analyze differences between the classifiers using rank correlation. We observe a considerable spread in the achieved performance and conclude that the X-ray-specific ResNet-50, integrating non-image data yields the best overall results.

##### Abstract (translated by Google)
X射线图像档案（例如来自NIH临床中心的ChestX-ray14数据集）的可用性增加引发了对深度学习技术越来越感兴趣。为了更好地了解不同的方法及其在胸部X射线分类中的应用，我们详细研究了强大的网络架构：ResNet-50。在此领域的先前工作的基础上，我们考虑有无微调的转换学习以及从头开始的专用X射线网络培训。为了充分利用X射线数据的高空间分辨率，我们还包括一个扩展的ResNet-50架构，以及在分类过程中集成非图像数据（患者年龄，性别和采集类型）的网络。在系统性评估中，我们使用5倍重采样和多标签损失函数，评估ROC统计的不同病理分类方法的性能，并使用秩相关分析分类器之间的差异。我们观察到已取得的性能有相当大的差距，并得出结论：X射线专用的ResNet-50集成了非图像数据，可获得最佳的整体结果。

##### URL
[http://arxiv.org/abs/1803.02315](http://arxiv.org/abs/1803.02315)

##### PDF
[http://arxiv.org/pdf/1803.02315](http://arxiv.org/pdf/1803.02315)

