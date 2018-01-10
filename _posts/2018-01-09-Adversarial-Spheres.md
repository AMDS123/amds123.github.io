---
layout: post
title: "Adversarial Spheres"
date: 2018-01-09 03:24:53
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
现有技术的计算机视觉模型已被证明容易受到输入的小型对抗性干扰。换句话说，数据分布中的大多数图像都被模型正确分类，并且非常接近视觉上类似的错误分类图像。尽管有大量的研究兴趣，但这一现象的原因仍然不甚了解，尚未解决。我们推测这种反直觉行为是数据流形的高维几何的自然发生的结果。作为探索这一假设的第一步，我们研究了一个简单的两个同心高维球体之间分类的合成数据集。对于这个数据集，我们展示了测试误差量和最近误差的平均距离之间的基本折衷。特别是，我们证明任何对球体的一个小恒定分数进行错误分类的模型将容易受到大小为$ O（1 / \ sqrt {d}）$的敌对扰动的影响。令人惊讶的是，当我们在这个数据集上训练几个不同的体系结构时，他们所有的错误集自然会接近这个理论界限。作为该理论的结果，神经网络对小对抗性扰动的脆弱性是观察到的测试误差量的合理结果。我们希望我们对这个非常简单的案例的理论分析将指出前进的方向，探索复杂的现实世界的数据集的几何如何导致敌对的例子。

##### URL
[http://arxiv.org/abs/1801.02774](http://arxiv.org/abs/1801.02774)

##### PDF
[http://arxiv.org/pdf/1801.02774](http://arxiv.org/pdf/1801.02774)

