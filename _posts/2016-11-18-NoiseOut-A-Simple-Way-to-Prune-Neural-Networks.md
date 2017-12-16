---
layout: post
title: "NoiseOut: A Simple Way to Prune Neural Networks"
date: 2016-11-18 19:55:29
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Mohammad Babaeizadeh, Paris Smaragdis, Roy H. Campbell
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are usually over-parameterized with significant redundancy in the number of required neurons which results in unnecessary computation and memory usage at inference time. One common approach to address this issue is to prune these big networks by removing extra neurons and parameters while maintaining the accuracy. In this paper, we propose NoiseOut, a fully automated pruning algorithm based on the correlation between activations of neurons in the hidden layers. We prove that adding additional output neurons with entirely random targets results into a higher correlation between neurons which makes pruning by NoiseOut even more efficient. Finally, we test our method on various networks and datasets. These experiments exhibit high pruning rates while maintaining the accuracy of the original network.

##### Abstract (translated by Google)
神经网络通常是过度参数化的，所需神经元的数量显着冗余，导致在推断时间内不必要的计算和内存使用。解决这个问题的一种常见方法是通过在保持精确度的同时去除额外的神经元和参数来修剪这些大的网络。在本文中，我们提出了NoiseOut，一种基于隐藏层中神经元激活之间相关性的全自动修剪算法。我们证明，增加额外的输出神经元与完全随机的目标导致更高的神经元之间的相关性，使得由NoiseOut修剪更有效。最后，我们在各种网络和数据集上测试我们的方法。这些实验表现出高修剪率，同时保持原始网络的准确性。

##### URL
[https://arxiv.org/abs/1611.06211](https://arxiv.org/abs/1611.06211)

##### PDF
[https://arxiv.org/pdf/1611.06211](https://arxiv.org/pdf/1611.06211)

