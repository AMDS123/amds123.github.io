---
layout: post
title: "BranchyNet: Fast Inference via Early Exiting from Deep Neural Networks"
date: 2017-09-06 06:30:51
categories: arXiv_CV
tags: arXiv_CV Inference Classification Prediction
author: Surat Teerapittayanon, Bradley McDanel, H.T. Kung
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are state of the art methods for many learning tasks due to their ability to extract increasingly better features at each network layer. However, the improved performance of additional layers in a deep network comes at the cost of added latency and energy usage in feedforward inference. As networks continue to get deeper and larger, these costs become more prohibitive for real-time and energy-sensitive applications. To address this issue, we present BranchyNet, a novel deep network architecture that is augmented with additional side branch classifiers. The architecture allows prediction results for a large portion of test samples to exit the network early via these branches when samples can already be inferred with high confidence. BranchyNet exploits the observation that features learned at an early layer of a network may often be sufficient for the classification of many data points. For more difficult samples, which are expected less frequently, BranchyNet will use further or all network layers to provide the best likelihood of correct prediction. We study the BranchyNet architecture using several well-known networks (LeNet, AlexNet, ResNet) and datasets (MNIST, CIFAR10) and show that it can both improve accuracy and significantly reduce the inference time of the network.

##### Abstract (translated by Google)
深度神经网络是许多学习任务的最先进的方法，因为它们能够在每个网络层提取越来越好的特征。然而，深度网络中附加层的改进性能是以前馈推断中增加的延迟和能量使用为代价的。随着网络不断变得越来越大，这些成本对于实时和能源敏感型应用而言变得越来越不可收拾。为了解决这个问题，我们提出了BranchyNet，一个新的深层网络架构，增加了额外的支路分类器。当已经可以高度置信地推断样本时，该架构允许大部分测试样本的预测结果通过这些分支提前离开网络。 BranchyNet利用了这样的观察：在网络的早期阶段学到的特征对于许多数据点的分类通常是足够的。对于更难预测的样本，BranchyNet将使用更多或所有的网络层来提供正确预测的最佳可能性。我们使用几个知名的网络（LeNet，AlexNet，ResNet）和数据集（MNIST，CIFAR10）来研究BranchyNet架构，并表明它可以提高网络的准确性并显着减少网络的推理时间。

##### URL
[https://arxiv.org/abs/1709.01686](https://arxiv.org/abs/1709.01686)

##### PDF
[https://arxiv.org/pdf/1709.01686](https://arxiv.org/pdf/1709.01686)

