---
layout: post
title: "Semi-supervised learning of deep metrics for stereo reconstruction"
date: 2016-12-03 16:09:32
categories: arXiv_CV
tags: arXiv_CV Prediction Gradient_Descent
author: Stepan Tulyakov, Anton Ivanov, Francois Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
Deep-learning metrics have recently demonstrated extremely good performance to match image patches for stereo reconstruction. However, training such metrics requires large amount of labeled stereo images, which can be difficult or costly to collect for certain applications. The main contribution of our work is a new semi-supervised method for learning deep metrics from unlabeled stereo images, given coarse information about the scenes and the optical system. Our method alternatively optimizes the metric with a standard stochastic gradient descent, and applies stereo constraints to regularize its prediction. Experiments on reference data-sets show that, for a given network architecture, training with this new method without ground-truth produces a metric with performance as good as state-of-the-art baselines trained with the said ground-truth. This work has three practical implications. Firstly, it helps to overcome limitations of training sets, in particular noisy ground truth. Secondly it allows to use much more training data during learning. Thirdly, it allows to tune deep metric for a particular stereo system, even if ground truth is not available.

##### Abstract (translated by Google)
深度学习指标最近表现出非常好的性能来匹配用于立体声重建的图像补丁。然而，训练这样的度量需要大量标记的立体图像，这对于某些应用来说可能是困难的或昂贵的。我们工作的主要贡献是一个新的半监督方法，用于从无标签的立体图像学习深度度量，给出关于场景和光学系统的粗糙信息。我们的方法用标准的随机梯度下降交替优化度量，并应用立体约束来规范其预测。参考数据集上的实验表明，对于给定的网络架构，使用这种没有地面事实的新方法进行训练产生的性能与用所述地面事实训练的最新的基线一样好。这项工作有三个实际的影响。首先，它有助于克服训练集的局限性，尤其是嘈杂的基本事实。其次它允许在学习期间使用更多的训练数据。第三，它允许调整特定立体声系统的深度度量，即使地面实况不可用。

##### URL
[https://arxiv.org/abs/1612.00979](https://arxiv.org/abs/1612.00979)

##### PDF
[https://arxiv.org/pdf/1612.00979](https://arxiv.org/pdf/1612.00979)

