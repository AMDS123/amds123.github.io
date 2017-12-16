---
layout: post
title: "Improving training of deep neural networks via Singular Value Bounding"
date: 2017-03-18 07:27:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Optimization Classification Deep_Learning Detection
author: Kui Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods achieve great success recently on many computer vision problems, with image classification and object detection as the prominent examples. In spite of these practical successes, optimization of deep networks remains an active topic in deep learning research. In this work, we focus on investigation of the network solution properties that can potentially lead to good performance. Our research is inspired by theoretical and empirical results that use orthogonal matrices to initialize networks, but we are interested in investigating how orthogonal weight matrices perform when network training converges. To this end, we propose to constrain the solutions of weight matrices in the orthogonal feasible set during the whole process of network training, and achieve this by a simple yet effective method called Singular Value Bounding (SVB). In SVB, all singular values of each weight matrix are simply bounded in a narrow band around the value of 1. Based on the same motivation, we also propose Bounded Batch Normalization (BBN), which improves Batch Normalization by removing its potential risk of ill-conditioned layer transform. We present both theoretical and empirical results to justify our proposed methods. Experiments on benchmark image classification datasets show the efficacy of our proposed SVB and BBN. In particular, we achieve the state-of-the-art results of 3.06% error rate on CIFAR10 and 16.90% on CIFAR100, using off-the-shelf network architectures (Wide ResNets). Our preliminary results on ImageNet also show the promise in large-scale learning.

##### Abstract (translated by Google)
深度学习方法最近在许多计算机视觉问题上取得了巨大的成功，以图像分类和对象检测为例。尽管有这些实际的成功，深度网络的优化仍然是深度学习研究中的一个活跃的话题。在这项工作中，我们专注于研究可能导致良好性能的网络解决方案属性。我们的研究受到使用正交矩阵来初始化网络的理论和实证结果的启发，但是我们有兴趣研究在网络训练收敛时正交加权矩阵如何执行。为此，我们提出在网络训练的整个过程中约束正交可行集中权矩阵的解，并用简单而有效的奇异值边界（SVB）方法实现。在SVB中，每个权重矩阵的所有奇异值都被简单地限定在围绕1的值的窄带上。基于相同的动机，我们还提出了有界批量归一化（BBN），其通过消除其潜在的危险条件层转换。我们提出了理论和实证结果来证明我们提出的方法。基准图像分类数据集上的实验显示了我们提出的SVB和BBN的功效。特别是，我们使用现成的网络架构（Wide ResNets），在CIFAR10上实现了3.06％的错误率，在CIFAR100上实现了16.90％的最新结果。我们在ImageNet上的初步成果也显示了大规模学习的承诺。

##### URL
[https://arxiv.org/abs/1611.06013](https://arxiv.org/abs/1611.06013)

##### PDF
[https://arxiv.org/pdf/1611.06013](https://arxiv.org/pdf/1611.06013)

