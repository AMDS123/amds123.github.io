---
layout: post
title: "Coupled Ensembles of Neural Networks"
date: 2017-09-18 17:16:26
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Anuvabh Dutt, Denis Pellerin, Georges Quénot
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate in this paper the architecture of deep convolutional networks. Building on existing state of the art models, we propose a reconfiguration of the model parameters into several parallel branches at the global network level, with each branch being a standalone CNN. We show that this arrangement is an efficient way to significantly reduce the number of parameters without losing performance or to significantly improve the performance with the same level of performance. The use of branches brings an additional form of regularization. In addition to the split into parallel branches, we propose a tighter coupling of these branches by placing the "fuse (averaging) layer" before the Log-Likelihood and SoftMax layers during training. This gives another significant performance improvement, the tighter coupling favouring the learning of better representations, even at the level of the individual branches. We refer to this branched architecture as "coupled ensembles". The approach is very generic and can be applied with almost any DCNN architecture. With coupled ensembles of DenseNet-BC and parameter budget of 25M, we obtain error rates of 2.92%, 15.68% and 1.50% respectively on CIFAR-10, CIFAR-100 and SVHN tasks. For the same budget, DenseNet-BC has error rate of 3.46%, 17.18%, and 1.8% respectively. With ensembles of coupled ensembles, of DenseNet-BC networks, with 50M total parameters, we obtain error rates of 2.72%, 15.13% and 1.42% respectively on these tasks.

##### Abstract (translated by Google)
本文研究了深度卷积网络的结构。在现有技术模型的基础上，我们提出将模型参数重新配置到全球网络层面上的几个并行分支，每个分支是一个独立的CNN。我们表明，这种安排是显着减少参数数量而不损失性能的有效方式，或者在性能水平相同的情况下显着提高性能。分支机构的使用带来了另一种形式的正规化。除了分成平行分支之外，我们还建议通过在训练期间在对数似然性和SoftMax层之前放置“保险丝（平均）层”来更紧密地耦合这些分支。这给了另一个显着的性能改进，即使在各个分支层面，更紧密的耦合也有利于学习更好的表示。我们将这种分支架构称为“耦合合奏”。这种方法非常通用，几乎可以应用于任何DCNN架构。对于CIFAR-10，CIFAR-100和SVHN任务，利用DenseNet-BC的耦合集合和25M的参数预算分别获得2.92％，15.68％和1.50％的误差率。对于相同的预算，DenseNet-BC的错误率分别为3.46％，17.18％和1.8％。对于DenseNet-BC网络中的耦合集合，总参数为50M，我们分别得到了这些任务的误差率分别为2.72％，15.13％和1.42％。

##### URL
[https://arxiv.org/abs/1709.06053](https://arxiv.org/abs/1709.06053)

##### PDF
[https://arxiv.org/pdf/1709.06053](https://arxiv.org/pdf/1709.06053)

