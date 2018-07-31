---
layout: post
title: "Crossbar-aware neural network pruning"
date: 2018-07-25 21:08:35
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Gradient_Descent
author: Ling Liang, Lei Deng, Yueling Zeng, Xing Hu, Yu Ji, Xin Ma, Guoqi Li, Yuan Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Crossbar architecture based devices have been widely adopted in neural network accelerators by taking advantage of the high efficiency on vector-matrix multiplication (VMM) operations. However, in the case of convolutional neural networks (CNNs), the efficiency is compromised dramatically due to the large amounts of data reuse. Although some mapping methods have been designed to achieve a balance between the execution throughput and resource overhead, the resource consumption cost is still huge while maintaining the throughput. 
 Network pruning is a promising and widely studied leverage to shrink the model size. Whereas, previous work didn`t consider the crossbar architecture and the corresponding mapping method, which cannot be directly utilized by crossbar-based neural network accelerators. Tightly combining the crossbar structure and its mapping, this paper proposes a crossbar-aware pruning framework based on a formulated L0-norm constrained optimization problem. Specifically, we design an L0-norm constrained gradient descent (LGD) with relaxant probabilistic projection (RPP) to solve this problem. Two grains of sparsity are successfully achieved: i) intuitive crossbar-grain sparsity and ii) column-grain sparsity with output recombination, based on which we further propose an input feature maps (FMs) reorder method to improve the model accuracy. We evaluate our crossbar-aware pruning framework on median-scale CIFAR10 dataset and large-scale ImageNet dataset with VGG and ResNet models. Our method is able to reduce the crossbar overhead by 44%-72% with little accuracy degradation. This work greatly saves the resource and the related energy cost, which provides a new co-design solution for mapping CNNs onto various crossbar devices with significantly higher efficiency.

##### Abstract (translated by Google)
基于交叉矩阵架构的设备已经通过利用矢量矩阵乘法（VMM）操作的高效率在神经网络加速器中被广泛采用。然而，在卷积神经网络（CNN）的情况下，由于大量数据重用，效率显着受损。虽然已经设计了一些映射方法来实现执行吞吐量和资源开销之间的平衡，但是在保持吞吐量的同时资源消耗成本仍然很大。
 网络修剪是一种有前途且广泛研究的缩小模型尺寸的杠杆。然而，之前的工作没有考虑交叉开关架构和相应的映射方法，这些方法不能直接用于基于交叉开关的神经网络加速器。将交叉开关结构及其映射紧密结合，本文提出了一种基于L0范数约束优化问题的交叉感知修剪框架。具体来说，我们设计了具有松弛概率投影（RPP）的L0范数约束梯度下降（LGD）来解决这个问题。成功实现了两粒稀疏度：i）直观的横杆粒度稀疏性和ii）具有输出重组的柱粒度稀疏性，基于此我们进一步提出了输入特征图（FM）重新排序方法以提高模型精度。我们使用VGG和ResNet模型评估中等规模CIFAR10数据集和大规模ImageNet数据集的交叉感知修剪框架。我们的方法能够将横梁开销降低44％-72％，而精度降低很少。这项工作极大地节省了资源和​​相关的能源成本，这提供了一种新的协同设计解决方案，用于将CNN映射到各种横杆设备上，效率显着提高。

##### URL
[http://arxiv.org/abs/1807.10816](http://arxiv.org/abs/1807.10816)

##### PDF
[http://arxiv.org/pdf/1807.10816](http://arxiv.org/pdf/1807.10816)

