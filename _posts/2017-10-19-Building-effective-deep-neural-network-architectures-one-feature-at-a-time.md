---
layout: post
title: "Building effective deep neural network architectures one feature at a time"
date: 2017-10-19 21:59:52
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Martin Mundt, Tobias Weis, Kishore Konda, Visvanathan Ramesh
mathjax: true
---

* content
{:toc}

##### Abstract
Successful training of convolutional neural networks is often associated with sufficiently deep architectures composed of high amounts of features. These networks typically rely on a variety of regularization and pruning techniques to converge to less redundant states. We introduce a novel bottom-up approach to expand representations in fixed-depth architectures. These architectures start from just a single feature per layer and greedily increase width of individual layers to attain effective representational capacities needed for a specific task. While network growth can rely on a family of metrics, we propose a computationally efficient version based on feature time evolution and demonstrate its potency in determining feature importance and a networks' effective capacity. We demonstrate how automatically expanded architectures converge to similar topologies that benefit from lesser amount of parameters or improved accuracy and exhibit systematic correspondence in representational complexity with the specified task. In contrast to conventional design patterns with a typical monotonic increase in the amount of features with increased depth, we observe that CNNs perform better when there is more learnable parameters in intermediate, with falloffs to earlier and later layers.

##### Abstract (translated by Google)
卷积神经网络的成功训练通常与足够深的由大量特征构成的体系结构相关联。这些网络通常依靠各种正则化和修剪技术来收敛到较少冗余的状态。我们引入一种新颖的自下而上的方法来扩展固定深度架构中的表示。这些体系结构从每层的单个特征开始，并且贪婪地增加单个层的宽度以获得特定任务所需的有效表示能力。尽管网络增长可以依赖一系列度量标准，但是我们提出了一个基于特征时间演化的计算高效版本，并且证明了它在确定特征重要性和网络有效能力方面的效能。我们演示了自动扩展体系结构是如何收敛到类似的拓扑结构的，这些拓扑结构可以从更少的参数或更高的精度中受益，并且可以展现与指定任务相关的代表性复杂性。与传统的设计模式相比，随着深度增加，特征量的单调增加，我们观察到CNN在中间层有更多的可学习参数时性能更好，并且衰减到较早和较晚的层次。

##### URL
[https://arxiv.org/abs/1705.06778](https://arxiv.org/abs/1705.06778)

##### PDF
[https://arxiv.org/pdf/1705.06778](https://arxiv.org/pdf/1705.06778)

