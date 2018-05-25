---
layout: post
title: "Multi-Task Zipping via Layer-wise Neuron Sharing"
date: 2018-05-24 17:33:38
categories: arXiv_CV
tags: arXiv_CV
author: Xiaoxi He, Zimu Zhou, Lothar Thiele
mathjax: true
---

* content
{:toc}

##### Abstract
Future mobile devices are anticipated to perceive, understand and react to the world on their own by running multiple correlated deep neural networks on-device. Yet the complexity of these neural networks needs to be trimmed down both withinmodel and cross-model to fit in mobile storage and memory. Previous studies focus on squeezing the redundancy within a single neural network. In this work, we aim to reduce the redundancy across multiple models. We propose Multi-Task Zipping (MTZ), a framework to automatically merge correlated, pre-trained deep neural networks for cross-model compression. Central in MTZ is a layer-wise neuron sharing and incoming weight updating scheme that induces a minimal change in the error function. MTZ inherits information from each model and demands light retraining to re-boost the accuracy of individual tasks. Evaluations show that MTZ is able to fully merge the hidden layers of two VGG-16 networks with a 3.18% increase in the test error averaged on ImageNet and CelebA, or share 39.61% parameters between the two networks with &lt; 0.5% increase in the test errors for both tasks. The number of iterations to retrain the combined network is at least 17.8x lower than that of training a single VGG-16 network.

##### Abstract (translated by Google)
预计未来的移动设备可以通过在设备上运行多个相关的深度神经网络来自行感知，理解和反应世界。然而，这些神经网络的复杂性需要在模型和交叉模型中进行修剪，以适应移动存储和内存。以前的研究集中在压缩单个神经网络内的冗余。在这项工作中，我们旨在减少多个模型的冗余。我们提出了多任务压缩（MTZ），这是一个自动合并相关的，预先训练好的深层神经网络用于交叉模型压缩的框架。 MTZ中心是一种分层神经元共享和传入重量更新方案，可以在误差函数中引入最小的变化。 MTZ继承了每个模型的信息，并要求重新训练灯光以重新提高单个任务的准确性。评估表明，MTZ能够将两个VGG-16网络的隐藏层完全合并，在ImageNet和CelebA上平均测试误差增加3.18％，或者在两个网络之间共享39.61％参数，这两项任务的测试错误增加了0.5％。重新训练组合网络的迭代次数比训练单个VGG-16网络低至少17.8倍。

##### URL
[http://arxiv.org/abs/1805.09791](http://arxiv.org/abs/1805.09791)

##### PDF
[http://arxiv.org/pdf/1805.09791](http://arxiv.org/pdf/1805.09791)

