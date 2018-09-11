---
layout: post
title: "Adversarial Spheres"
date: 2018-09-10 17:08:27
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Justin Gilmer, Luke Metz, Fartash Faghri, Samuel S. Schoenholz, Maithra Raghu, Martin Wattenberg, Ian Goodfellow
mathjax: true
---

* content
{:toc}

##### Abstract
State of the art computer vision models have been shown to be vulnerable to small adversarial perturbations of the input. In other words, most images in the data distribution are both correctly classified by the model and are very close to a visually similar misclassified image. Despite substantial research interest, the cause of the phenomenon is still poorly understood and remains unsolved. We hypothesize that this counter intuitive behavior is a naturally occurring result of the high dimensional geometry of the data manifold. As a first step towards exploring this hypothesis, we study a simple synthetic dataset of classifying between two concentric high dimensional spheres. For this dataset we show a fundamental tradeoff between the amount of test error and the average distance to nearest error. In particular, we prove that any model which misclassifies a small constant fraction of a sphere will be vulnerable to adversarial perturbations of size $O(1/\sqrt{d})$. Surprisingly, when we train several different architectures on this dataset, all of their error sets naturally approach this theoretical bound. As a result of the theory, the vulnerability of neural networks to small adversarial perturbations is a logical consequence of the amount of test error observed. We hope that our theoretical analysis of this very simple case will point the way forward to explore how the geometry of complex real-world data sets leads to adversarial examples.

##### Abstract (translated by Google)
已经表明，现有技术的计算机视觉模型易受输入的小的对抗性扰动的影响。换句话说，数据分布中的大多数图像都被模型正确分类，并且非常接近视觉上类似的错误分类图像。尽管存在大量研究兴趣，但仍然对该现象的原因了解甚少并且仍未解决。我们假设这种反直觉行为是数据流形的高维几何的自然发生的结果。作为探索这一假设的第一步，我们研究了一个简单的合成数据集，在两个同心高维球体之间进行分类。对于此数据集，我们显示了测试误差量与最接近误差的平均距离之间的基本权衡。特别是，我们证明任何错误分类球体的小常数部分的模型都容易受到大小为$ O（1 / \ sqrt {d}）$的对抗性扰动的影响。令人惊讶的是，当我们在这个数据集上训练几种不同的架构时，它们的所有错误集自然地接近这个理论界限。作为该理论的结果，神经网络对小的对抗性扰动的脆弱性是观察到的测试误差量的逻辑结果。我们希望我们对这个非常简单的案例的理论分析将指出探索复杂的现实世界数据集的几何如何导致对抗性例子的前进方向。

##### URL
[http://arxiv.org/abs/1801.02774](http://arxiv.org/abs/1801.02774)

##### PDF
[http://arxiv.org/pdf/1801.02774](http://arxiv.org/pdf/1801.02774)

