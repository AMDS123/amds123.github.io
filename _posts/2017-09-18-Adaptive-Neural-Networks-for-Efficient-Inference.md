---
layout: post
title: "Adaptive Neural Networks for Efficient Inference"
date: 2017-09-18 18:14:49
categories: arXiv_CV
tags: arXiv_CV Inference Classification Recognition
author: Tolga Bolukbasi, Joseph Wang, Ofer Dekel, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to adaptively utilize deep neural networks in order to reduce the evaluation time on new examples without loss of accuracy. Rather than attempting to redesign or approximate existing networks, we propose two schemes that adaptively utilize networks. We first pose an adaptive network evaluation scheme, where we learn a system to adaptively choose the components of a deep network to be evaluated for each example. By allowing examples correctly classified using early layers of the system to exit, we avoid the computational time associated with full evaluation of the network. We extend this to learn a network selection system that adaptively selects the network to be evaluated for each example. We show that computational time can be dramatically reduced by exploiting the fact that many examples can be correctly classified using relatively efficient networks and that complex, computationally costly networks are only necessary for a small fraction of examples. We pose a global objective for learning an adaptive early exit or network selection policy and solve it by reducing the policy learning problem to a layer-by-layer weighted binary classification problem. Empirically, these approaches yield dramatic reductions in computational cost, with up to a 2.8x speedup on state-of-the-art networks from the ImageNet image recognition challenge with minimal (<1%) loss of top5 accuracy.

##### Abstract (translated by Google)
我们提出了一种自适应地利用深度神经网络的方法，以减少新的例子的评估时间而不损失精度。我们提出了两种自适应地利用网络的方案，而不是试图重新设计或近似现有的网络。我们首先提出了一个自适应的网络评估方案，在这里我们学习了一个系统来自适应地选择一个深度网络的组件来评估每个例子。通过允许使用系统早期层次正确分类的例子，我们避免了与网络全面评估相关的计算时间。我们扩展这个学习网络选择系统，自适应地选择网络进行评估每个例子。我们表明，通过利用这样一个事实，计算时间可以大大减少，许多例子可以使用相对高效的网络进行正确分类，复杂的，计算成本高昂的网络只需要一小部分例子。我们提出了一个全球性目标，即学习一个适应性的早期退出或网络选择策略，并通过将策略学习问题降低到逐层加权二进制分类问题来解决这个问题。从经验上讲，这些方法大大降低了计算成本，从ImageNet图像识别挑战到最先进的网络，速度提高了2.8倍，最高精度损失最少（<1％）。

##### URL
[https://arxiv.org/abs/1702.07811](https://arxiv.org/abs/1702.07811)

##### PDF
[https://arxiv.org/pdf/1702.07811](https://arxiv.org/pdf/1702.07811)

