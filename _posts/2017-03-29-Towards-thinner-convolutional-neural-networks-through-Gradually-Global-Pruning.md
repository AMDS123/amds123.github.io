---
layout: post
title: "Towards thinner convolutional neural networks through Gradually Global Pruning"
date: 2017-03-29 07:31:46
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhengtao Wang, Ce Zhu, Zhiqiang Xia, Qi Guo, Yipeng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep network pruning is an effective method to reduce the storage and computation cost of deep neural networks when applying them to resource-limited devices. Among many pruning granularities, neuron level pruning will remove redundant neurons and filters in the model and result in thinner networks. In this paper, we propose a gradually global pruning scheme for neuron level pruning. In each pruning step, a small percent of neurons were selected and dropped across all layers in the model. We also propose a simple method to eliminate the biases in evaluating the importance of neurons to make the scheme feasible. Compared with layer-wise pruning scheme, our scheme avoid the difficulty in determining the redundancy in each layer and is more effective for deep networks. Our scheme would automatically find a thinner sub-network in original network under a given performance.

##### Abstract (translated by Google)
深度网络修剪是将深度神经网络应用于资源有限的设备时，降低深度神经网络的存储和计算成本的有效方法。在许多修剪粒度中，神经元级修剪将删除模型中的冗余神经元和滤波器，并导致网络更薄。在本文中，我们提出了一个渐进式的全局修剪方案来修剪神经元。在每个修剪步骤中，选择一小部分神经元并将其放入模型中的所有层。我们还提出了一个简单的方法来消除评估神经元的重要性使计划可行的偏见。与分层修剪方案相比，我们的方案避免了在每一层中确定冗余的困难，并且对深度网络更有效。在给定的性能下，我们的方案会自动在原始网络中找到更细的子网络。

##### URL
[https://arxiv.org/abs/1703.09916](https://arxiv.org/abs/1703.09916)

##### PDF
[https://arxiv.org/pdf/1703.09916](https://arxiv.org/pdf/1703.09916)

