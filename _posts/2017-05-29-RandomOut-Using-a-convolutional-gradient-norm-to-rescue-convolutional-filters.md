---
layout: post
title: "RandomOut: Using a convolutional gradient norm to rescue convolutional filters"
date: 2017-05-29 04:49:22
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Joseph Paul Cohen, Henry Z. Lo, Wei Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Filters in convolutional neural networks are sensitive to their initialization. The random numbers used to initialize filters are a bias and determine if you will "win" and converge to a satisfactory local minimum so we call this The Filter Lottery. We observe that the 28x28 Inception-V3 model without Batch Normalization fails to train 26% of the time when varying the random seed alone. This is a problem that affects the trial and error process of designing a network. Because random seeds have a large impact it makes it hard to evaluate a network design without trying many different random starting weights. This work aims to reduce the bias imposed by the initial weights so a network converges more consistently. We propose to evaluate and replace specific convolutional filters that have little impact on the prediction. We use the gradient norm to evaluate the impact of a filter on error, and re-initialize filters when the gradient norm of its weights falls below a specific threshold. This consistently improves accuracy on the 28x28 Inception-V3 with a median increase of +3.3%. In effect our method RandomOut increases the number of filters explored without increasing the size of the network. We observe that the RandomOut method has more consistent generalization performance, having a standard deviation of 1.3% instead of 2% when varying random seeds, and does so faster and with fewer parameters.

##### Abstract (translated by Google)
卷积神经网络中的滤波器对其初始化非常敏感。用来初始化滤波器的随机数是一个偏差，并决定您是否会“赢”，并收敛到一个令人满意的局部最小值，所以我们称之为过滤彩票。我们观察到，没有批量标准化的28x28 Inception-V3模型在单独改变随机种子时不能训练26％的时间。这是一个影响设计网络试错过程的问题。因为随机种子有很大的影响，所以很难评估网络设计而不尝试许多不同的随机起始权重。这项工作的目的是减少初始权重施加的偏差，使网络更加一致地收敛。我们建议评估和替换对预测影响不大的特定卷积滤波器。我们使用梯度范数来评估滤波器对误差的影响，并且在其权重的梯度范数低于特定阈值时重新初始化滤波器。这一贯地提高了28x28 Inception-V3的准确性，中位数增长了3.3％。实际上，我们的方法RandomOut增加了探索的过滤器的数量，而不增加网络的大小。我们观察到RandomOut方法具有更一致的泛化性能，在随机种子变化时标准差为1.3％，而不是2％，速度更快，参数更少。

##### URL
[https://arxiv.org/abs/1602.05931](https://arxiv.org/abs/1602.05931)

##### PDF
[https://arxiv.org/pdf/1602.05931](https://arxiv.org/pdf/1602.05931)

