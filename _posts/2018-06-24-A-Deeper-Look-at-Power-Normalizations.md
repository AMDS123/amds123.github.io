---
layout: post
title: "A Deeper Look at Power Normalizations"
date: 2018-06-24 17:38:15
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Piotr Koniusz, Hongguang Zhang, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Power Normalizations (PN) are very useful non-linear operators in the context of Bag-of-Words data representations as they tackle problems such as feature imbalance. In this paper, we reconsider these operators in the deep learning setup by introducing a novel layer that implements PN for non-linear pooling of feature maps. Specifically, by using a kernel formulation, our layer combines the feature vectors and their respective spatial locations in the feature maps produced by the last convolutional layer of CNN. Linearization of such a kernel results in a positive definite matrix capturing the second-order statistics of the feature vectors, to which PN operators are applied. We study two types of PN functions, namely (i) MaxExp and (ii) Gamma, addressing their role and meaning in the context of nonlinear pooling. We also provide a probabilistic interpretation of these operators and derive their surrogates with well-behaved gradients for end-to-end CNN learning. We apply our theory to practice by implementing the PN layer on a ResNet-50 model and showcase experiments on four benchmarks for fine-grained recognition, scene recognition, and material classification. Our results demonstrate state-of-the-art performance across all these tasks.

##### Abstract (translated by Google)
功率归一化（PN）在Bag-of-Words数据表示的背景下是非常有用的非线性算子，因为它们解决诸如特征不平衡等问题。在本文中，我们通过引入一个新颖的图层来重新考虑这些运算符在深度学习环境中，该图层实现了用于特征映射非线性汇聚的PN。具体而言，通过使用核函数公式，我们的图层将特征向量和它们各自的空间位置组合在由CNN的最后一个卷积层生成的特征映射中。这样一个核的线性化导致一个正定矩阵捕获特征向量的二阶统计量，PN运算符被应用于这些二阶统计量。我们研究两种类型的PN函数，即（i）MaxExp和（ii）Gamma，在非线性池中解决它们的作用和含义。我们还提供了对这些运营商的概率解释，并推导出他们的端对端CNN学习具有良好梯度的替代品。我们通过在ResNet-50模型上实现PN层将我们的理论应用于实践，并展示了四个基准的细粒度识别，场景识别和材料分类的实验。我们的结果证明了所有这些任务的最新性能。

##### URL
[http://arxiv.org/abs/1806.09183](http://arxiv.org/abs/1806.09183)

##### PDF
[http://arxiv.org/pdf/1806.09183](http://arxiv.org/pdf/1806.09183)

