---
layout: post
title: "Loss Max-Pooling for Semantic Image Segmentation"
date: 2017-04-10 17:44:33
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Samuel Rota Bulò, Gerhard Neuhold, Peter Kontschieder
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel loss max-pooling concept for handling imbalanced training data distributions, applicable as alternative loss layer in the context of deep neural networks for semantic image segmentation. Most real-world semantic segmentation datasets exhibit long tail distributions with few object categories comprising the majority of data and consequently biasing the classifiers towards them. Our method adaptively re-weights the contributions of each pixel based on their observed losses, targeting under-performing classification results as often encountered for under-represented object classes. Our approach goes beyond conventional cost-sensitive learning attempts through adaptive considerations that allow us to indirectly address both, inter- and intra-class imbalances. We provide a theoretical justification of our approach, complementary to experimental analyses on benchmark datasets. In our experiments on the Cityscapes and Pascal VOC 2012 segmentation datasets we find consistently improved results, demonstrating the efficacy of our approach.

##### Abstract (translated by Google)
我们引入了一种新的丢失最大池概念来处理不平衡的训练数据分布，适用于在深度神经网络语义图像分割背景下的替代损失层。大多数现实世界的语义分割数据集展现出长尾分布，其中包含大部分数据的对象类别很少，因此将分类器偏向它们。我们的方法根据观察到的损失自适应地重新加权每个像素的贡献，针对表现欠佳的对象类经常遇到的表现不佳的分类结果。我们的方法超越了传统的成本敏感的学习尝试，通过适应性考虑，使我们能够间接地解决阶级间和阶级内部的不平衡问题。我们为我们的方法提供了一个理论上的理由，是对基准数据集的实验分析的补充。在Cityscapes和Pascal VOC 2012分段数据集的实验中，我们发现结果持续改善，证明了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1704.02966](https://arxiv.org/abs/1704.02966)

##### PDF
[https://arxiv.org/pdf/1704.02966](https://arxiv.org/pdf/1704.02966)

