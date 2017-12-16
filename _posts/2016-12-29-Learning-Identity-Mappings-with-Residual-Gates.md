---
layout: post
title: "Learning Identity Mappings with Residual Gates"
date: 2016-12-29 01:36:47
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Pedro H. P. Savarese, Leonardo O. Mazza, Daniel R. Figueiredo
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new layer design by adding a linear gating mechanism to shortcut connections. By using a scalar parameter to control each gate, we provide a way to learn identity mappings by optimizing only one parameter. We build upon the motivation behind Residual Networks, where a layer is reformulated in order to make learning identity mappings less problematic to the optimizer. The augmentation introduces only one extra parameter per layer, and provides easier optimization by making degeneration into identity mappings simpler. We propose a new model, the Gated Residual Network, which is the result when augmenting Residual Networks. Experimental results show that augmenting layers provides better optimization, increased performance, and more layer independence. We evaluate our method on MNIST using fully-connected networks, showing empirical indications that our augmentation facilitates the optimization of deep models, and that it provides high tolerance to full layer removal: the model retains over 90% of its performance even after half of its layers have been randomly removed. We also evaluate our model on CIFAR-10 and CIFAR-100 using Wide Gated ResNets, achieving 3.65% and 18.27% error, respectively.

##### Abstract (translated by Google)
我们通过向快捷连接添加线性门控机制来提出新的图层设计。通过使用标量参数来控制每个门，我们提供了一种通过仅优化一个参数来学习身份映射的方法。我们建立在剩余网络背后的动机，在这个动机背景下，为了使学习身份映射对优化器的问题不那么严重。该增强每层仅引入一个额外的参数，并且通过使简化的身份映射简化而提供更容易的优化。我们提出了一个新的模型，门限剩余网络，这是增加剩余网络的结果。实验结果表明，增强层提供了更好的优化，性能提高和更多的层独立性。我们使用完全连接的网络评估了MNIST的方法，显示了我们的增强有利于深层模型的优化，并且它提供了对全层去除的高度容忍度：该模型甚至在它的一半之后保留其超过90％的性能层已被随机删除。我们还使用Wide Gated ResNet评估了CIFAR-10和CIFAR-100的模型，分别达到了3.65％和18.27％的误差。

##### URL
[https://arxiv.org/abs/1611.01260](https://arxiv.org/abs/1611.01260)

##### PDF
[https://arxiv.org/pdf/1611.01260](https://arxiv.org/pdf/1611.01260)

