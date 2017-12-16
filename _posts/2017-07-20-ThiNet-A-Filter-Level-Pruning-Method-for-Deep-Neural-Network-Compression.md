---
layout: post
title: "ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression"
date: 2017-07-20 02:16:16
categories: arXiv_CV
tags: arXiv_CV Optimization Inference Deep_Learning
author: Jian-Hao Luo, Jianxin Wu, Weiyao Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient and unified framework, namely ThiNet, to simultaneously accelerate and compress CNN models in both training and inference stages. We focus on the filter level pruning, i.e., the whole filter would be discarded if it is less important. Our method does not change the original network structure, thus it can be perfectly supported by any off-the-shelf deep learning libraries. We formally establish filter pruning as an optimization problem, and reveal that we need to prune filters based on statistics information computed from its next layer, not the current layer, which differentiates ThiNet from existing methods. Experimental results demonstrate the effectiveness of this strategy, which has advanced the state-of-the-art. We also show the performance of ThiNet on ILSVRC-12 benchmark. ThiNet achieves 3.31$\times$ FLOPs reduction and 16.63$\times$ compression on VGG-16, with only 0.52$\%$ top-5 accuracy drop. Similar experiments with ResNet-50 reveal that even for a compact network, ThiNet can also reduce more than half of the parameters and FLOPs, at the cost of roughly 1$\%$ top-5 accuracy drop. Moreover, the original VGG-16 model can be further pruned into a very small model with only 5.05MB model size, preserving AlexNet level accuracy but showing much stronger generalization ability.

##### Abstract (translated by Google)
我们提出了一个高效和统一的框架，即ThiNet，在训练和推理阶段同时加速和压缩CNN模型。我们关注滤波器级别的修剪，即如果整个滤波器不那么重要，它将被丢弃。我们的方法不会改变原有的网络结构，因此可以完全支持任何现成的深度学习库。我们正式建立过滤器修剪作为一个优化问题，并且揭示了我们需要根据从下一层计算出的统计信息修剪过滤器，而不是当前层，它将ThiNet与现有方法区分开来。实验结果证明了这种策略的有效性，它已经推进了最先进的技术。我们还展示了ThiNet在ILSVRC-12基准测试中的表现。 ThiNet在VGG-16上实现了3.31 $ \ times $ FLOPs的减少和16.63 $ \ times $的压缩，只有0.52 $ \％$前五的准确度下降。与ResNet-50类似的实验表明，即使对于一个紧凑的网络，ThiNet也可以减少超过一半的参数和FLOP，代价是大约1％的精度下降。此外，原有的VGG-16机型可以进一步修剪成只有5.05MB的小型机型，保持了AlexNet的精度，但是泛化能力更强。

##### URL
[https://arxiv.org/abs/1707.06342](https://arxiv.org/abs/1707.06342)

##### PDF
[https://arxiv.org/pdf/1707.06342](https://arxiv.org/pdf/1707.06342)

