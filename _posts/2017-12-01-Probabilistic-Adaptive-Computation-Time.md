---
layout: post
title: "Probabilistic Adaptive Computation Time"
date: 2017-12-01 16:09:26
categories: arXiv_CV
tags: arXiv_CV Optimization Inference RNN Deep_Learning
author: Michael Figurnov, Artem Sobolev, Dmitry Vetrov
mathjax: true
---

* content
{:toc}

##### Abstract
We present a probabilistic model with discrete latent variables that control the computation time in deep learning models such as ResNets and LSTMs. A prior on the latent variables expresses the preference for faster computation. The amount of computation for an input is determined via amortized maximum a posteriori (MAP) inference. MAP inference is performed using a novel stochastic variational optimization method. The recently proposed Adaptive Computation Time mechanism can be seen as an ad-hoc relaxation of this model. We demonstrate training using the general-purpose Concrete relaxation of discrete variables. Evaluation on ResNet shows that our method matches the speed-accuracy trade-off of Adaptive Computation Time, while allowing for evaluation with a simple deterministic procedure that has a lower memory footprint.

##### Abstract (translated by Google)
我们提出了一个带有离散潜变量的概率模型，它控制了ResNets和LSTM等深度学习模型中的计算时间。对潜在变量的先验表示对更快计算的偏好。输入的计算量是通过分期最大后验（MAP）推断来确定的。 MAP推断使用一种新的随机变分优化方法来执行。最近提出的自适应计算时间机制可以被看作是这种模型的临时放松。我们演示使用离散变量的通用混凝土松弛的训练。在ResNet上的评估表明，我们的方法匹配自适应计算时间的速度 - 精度折衷，同时允许使用具有较低内存占用的简单确定性过程进行评估。

##### URL
[https://arxiv.org/abs/1712.00386](https://arxiv.org/abs/1712.00386)

##### PDF
[https://arxiv.org/pdf/1712.00386](https://arxiv.org/pdf/1712.00386)

