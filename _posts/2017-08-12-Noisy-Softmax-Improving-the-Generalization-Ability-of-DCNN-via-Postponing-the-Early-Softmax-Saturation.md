---
layout: post
title: "Noisy Softmax: Improving the Generalization Ability of DCNN via Postponing the Early Softmax Saturation"
date: 2017-08-12 11:43:18
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Binghui Chen, Weihong Deng, Junping Du
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past few years, softmax and SGD have become a commonly used component and the default training strategy in CNN frameworks, respectively. However, when optimizing CNNs with SGD, the saturation behavior behind softmax always gives us an illusion of training well and then is omitted. In this paper, we first emphasize that the early saturation behavior of softmax will impede the exploration of SGD, which sometimes is a reason for model converging at a bad local-minima, then propose Noisy Softmax to mitigating this early saturation issue by injecting annealed noise in softmax during each iteration. This operation based on noise injection aims at postponing the early saturation and further bringing continuous gradients propagation so as to significantly encourage SGD solver to be more exploratory and help to find a better local-minima. This paper empirically verifies the superiority of the early softmax desaturation, and our method indeed improves the generalization ability of CNN model by regularization. We experimentally find that this early desaturation helps optimization in many tasks, yielding state-of-the-art or competitive results on several popular benchmark datasets.

##### Abstract (translated by Google)
在过去几年中，softmax和SGD分别成为CNN框架中常用的组件和默认的培训策略。但是，在用SGD优化CNN时，softmax背后的饱和行为总是给我们一个很好的训练的假象，然后被忽略。在本文中，我们首先强调softmax的早期饱和行为将阻碍SGD的探索，这有时是模型收敛在一个不好的局部最小值的原因，然后通过注入退火噪声来提出Noisy Softmax来缓解这个早期的饱和问题在每次迭代期间在softmax中。这种基于噪声注入的操作旨在推迟早期的饱和度，并进一步带来连续的梯度传播，从而大大鼓励SGD求解器更具探索性，并帮助找到更好的局部最小值。本文通过实证验证了softmax去饱和早期的优越性，实际上通过正则化提高了CNN模型的泛化能力。我们通过实验发现，这种早期的去饱和有助于优化许多任务，从而在几个流行的基准数据集上产生最先进或最具竞争力的结果。

##### URL
[https://arxiv.org/abs/1708.03769](https://arxiv.org/abs/1708.03769)

##### PDF
[https://arxiv.org/pdf/1708.03769](https://arxiv.org/pdf/1708.03769)

