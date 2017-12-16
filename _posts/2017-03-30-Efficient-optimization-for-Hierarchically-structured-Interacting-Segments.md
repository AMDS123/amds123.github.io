---
layout: post
title: "Efficient optimization for Hierarchically-structured Interacting Segments"
date: 2017-03-30 15:32:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Hossam Isack, Olga Veksler, Ipek Oguz, Milan Sonka, Yuri Boykov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an effective optimization algorithm for a general hierarchical segmentation model with geometric interactions between segments. Any given tree can specify a partial order over object labels defining a hierarchy. It is well-established that segment interactions, such as inclusion/exclusion and margin constraints, make the model significantly more discriminant. However, existing optimization methods do not allow full use of such models. Generic -expansion results in weak local minima, while common binary multi-layered formulations lead to non-submodularity, complex high-order potentials, or polar domain unwrapping and shape biases. In practice, applying these methods to arbitrary trees does not work except for simple cases. Our main contribution is an optimization method for the Hierarchically-structured Interacting Segments (HINTS) model with arbitrary trees. Our Path-Moves algorithm is based on multi-label MRF formulation and can be seen as a combination of well-known a-expansion and Ishikawa techniques. We show state-of-the-art biomedical segmentation for many diverse examples of complex trees.

##### Abstract (translated by Google)
我们提出了一个有效的优化算法的一般分层分割模型与段之间的几何相互作用。任何给定的树都可以通过定义层次结构的对象标签指定部分顺序。已经确定的是，诸如包含/排除和保证金约束之类的细分相互作用使得模型显着更具有判别力。但是，现有的优化方法不能充分利用这些模型。泛函展开导致弱局部最小值，而普通的二元多层结构导致非子模数，复数高阶势，极域解缠和形状偏差。在实践中，将这些方法应用到任意树上除了简单的情况外都是行不通的。我们的主要贡献是具有任意树的分层结构交互段（HINTS）模型的优化方法。我们的Path-Moves算法基于多标签MRF公式，可以看作是众所周知的a-扩展和Ishikawa技术的组合。我们展示了复杂树木的许多不同例子的最先进的生物医学分割。

##### URL
[https://arxiv.org/abs/1703.10530](https://arxiv.org/abs/1703.10530)

##### PDF
[https://arxiv.org/pdf/1703.10530](https://arxiv.org/pdf/1703.10530)

