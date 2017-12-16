---
layout: post
title: "Deep Semantic Classification for 3D LiDAR Data"
date: 2017-06-26 13:16:57
categories: arXiv_CV
tags: arXiv_CV Classification
author: Ayush Dewan, Gabriel L. Oliveira, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Robots are expected to operate autonomously in dynamic environments. Understanding the underlying dynamic characteristics of objects is a key enabler for achieving this goal. In this paper, we propose a method for pointwise semantic classification of 3D LiDAR data into three classes: non-movable, movable and dynamic. We concentrate on understanding these specific semantics because they characterize important information required for an autonomous system. Non-movable points in the scene belong to unchanging segments of the environment, whereas the remaining classes corresponds to the changing parts of the scene. The difference between the movable and dynamic class is their motion state. The dynamic points can be perceived as moving, whereas movable objects can move, but are perceived as static. To learn the distinction between movable and non-movable points in the environment, we introduce an approach based on deep neural network and for detecting the dynamic points, we estimate pointwise motion. We propose a Bayes filter framework for combining the learned semantic cues with the motion cues to infer the required semantic classification. In extensive experiments, we compare our approach with other methods on a standard benchmark dataset and report competitive results in comparison to the existing state-of-the-art. Furthermore, we show an improvement in the classification of points by combining the semantic cues retrieved from the neural network with the motion cues.

##### Abstract (translated by Google)
预计机器人将在动态环境中自主运行。了解对象的底层动态特性是实现这一目标的关键因素。在本文中，我们提出了一种将三维LiDAR数据逐点语义分类的方法，分为不可移动，可移动和动态三类。我们专注于理解这些特定的语义，因为它们表征了自治系统所需的重要信息。场景中的不可移动点属于环境中不变的部分，而剩余的类对应于场景的变化部分。动态和动态之间的区别是它们的运动状态。动态点可以被认为是移动的，而可移动的对象可以移动，但是被认为是静态的。为了学习环境中可移动点和不可移动点之间的区别，我们引入基于深度神经网络的方法，并且为了检测动态点，我们估计逐点运动。我们提出了一个贝叶斯过滤框架结合学习语义线索与运动线索推断所需的语义分类。在广泛的实验中，我们将我们的方法与标准基准数据集上的其他方法进行比较，并与现有技术相比较，报告竞争结果。此外，我们通过将从神经网络检索到的语义提示与运动提示相结合来显示对点的分类的改进。

##### URL
[https://arxiv.org/abs/1706.08355](https://arxiv.org/abs/1706.08355)

##### PDF
[https://arxiv.org/pdf/1706.08355](https://arxiv.org/pdf/1706.08355)

