---
layout: post
title: "Privacy-Preserving Deep Learning for any Activation Function"
date: 2018-09-10 12:36:05
categories: arXiv_AI
tags: arXiv_AI Deep_Learning Gradient_Descent
author: Le Trieu Phong, Tran Thi Phuong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the scenario that multiple data owners wish to apply a machine learning method over the combined dataset of all owners to obtain the best possible learning output but do not want to share the local datasets owing to privacy concerns. We design systems for the scenario that the stochastic gradient descent (SGD) algorithm is used as the machine learning method because SGD (or its variants) is at the heart of recent deep learning techniques over neural networks. Our systems differ from existing systems in the following features: {\bf (1)} any activation function can be used, meaning that no privacy-preserving-friendly approximation is required; {\bf (2)} gradients computed by SGD are not shared but the weight parameters are shared instead; and {\bf (3)} robustness against colluding parties even in the extreme case that only one honest party exists. We prove that our systems, while privacy-preserving, achieve the same learning accuracy as SGD and hence retain the merit of deep learning with respect to accuracy. Finally, we conduct several experiments using benchmark datasets, and show that our systems outperform previous system in terms of learning accuracies.

##### Abstract (translated by Google)
本文考虑了多个数据所有者希望在所有所有者的组合数据集上应用机器学习方法以获得最佳学习输出但不希望由于隐私问题而共享本地数据集的情景。我们为随机梯度下降（SGD）算法用作机器学习方法的场景设计系统，因为SGD（或其变体）是最近在神经网络上的深度学习技术的核心。我们的系统与以下特征中的现有系统不同：{\ bf（1）}可以使用任何激活函数，这意味着不需要保护隐私的近似值;由SGD计算的{\ bf（2）}梯度不是共享的，而是共享权重参数;并且{\ bf（3）}即使在只存在一个诚实政党的极端情况下，也反对串通政党。我们证明我们的系统在保护隐私的同时，实现了与SGD相同的学习准确性，因此在精度方面保留了深度学习的优点。最后，我们使用基准数据集进行了几次实验，并表明我们的系统在学习准确性方面优于以前的系统。

##### URL
[http://arxiv.org/abs/1809.03272](http://arxiv.org/abs/1809.03272)

##### PDF
[http://arxiv.org/pdf/1809.03272](http://arxiv.org/pdf/1809.03272)

