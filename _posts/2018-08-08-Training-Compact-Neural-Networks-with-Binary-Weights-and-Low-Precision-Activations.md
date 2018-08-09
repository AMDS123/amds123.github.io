---
layout: post
title: "Training Compact Neural Networks with Binary Weights and Low Precision Activations"
date: 2018-08-08 05:32:23
categories: arXiv_CV
tags: arXiv_CV Classification
author: Bohan Zhuang, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to train a network with binary weights and low-bitwidth activations, designed especially for mobile devices with limited power consumption. Most previous works on quantizing CNNs uncritically assume the same architecture, though with reduced precision. However, we take the view that for best performance it is possible (and even likely) that a different architecture may be better suited to dealing with low precision weights and activations. 
 Specifically, we propose a "network expansion" strategy in which we aggregate a set of homogeneous low-precision branches to implicitly reconstruct the full-precision intermediate feature maps. Moreover, we also propose a group-wise feature approximation strategy which is very flexible and highly accurate. Experiments on ImageNet classification tasks demonstrate the superior performance of the proposed model, named Group-Net, over various popular architectures. In particular, with binary weights and activations, we outperform the previous best binary neural network in terms of accuracy as well as saving more than 5 times computational complexity on ImageNet with ResNet-18 and ResNet-50.

##### Abstract (translated by Google)
在本文中，我们建议对具有二进制权重和低位宽激活的网络进行训练，该网络专为功耗有限的移动设备而设计。大多数先前关于量化CNN的工作不加批判地采用相同的架构，但精度降低。但是，我们认为，为了获得最佳性能，可能（甚至可能）不同的架构可能更适合处理低精度权重和激活。
 具体来说，我们提出了一种“网络扩展”策略，其中我们聚合一组同质的低精度分支以隐式重建全精度中间特征映射。此外，我们还提出了一种非常灵活且高度准确的分组特征近似策略。 ImageNet分类任务的实验证明了所提出的模型（称为Group-Net）在各种流行架构上的卓越性能。特别是，通过二进制权重和激活，我们在精度方面优于以前最好的二进制神经网络，并且使用ResNet-18和ResNet-50在ImageNet上节省了超过5倍的计算复杂度。

##### URL
[http://arxiv.org/abs/1808.02631](http://arxiv.org/abs/1808.02631)

##### PDF
[http://arxiv.org/pdf/1808.02631](http://arxiv.org/pdf/1808.02631)

