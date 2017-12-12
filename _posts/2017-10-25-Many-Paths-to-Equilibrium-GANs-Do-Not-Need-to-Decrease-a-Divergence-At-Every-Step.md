---
layout: post
title: "Many Paths to Equilibrium: GANs Do Not Need to Decrease a Divergence At Every Step"
date: 2017-10-25 09:02:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: William Fedus, Mihaela Rosca, Balaji Lakshminarayanan, Andrew M. Dai, Shakir Mohamed, Ian Goodfellow
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are a family of generative models that do not minimize a single training criterion. Unlike other generative models, the data distribution is learned via a game between a generator (the generative model) and a discriminator (a teacher providing training signal) that each minimize their own cost. GANs are designed to reach a Nash equilibrium at which each player cannot reduce their cost without changing the other players' parameters. One useful approach for the theory of GANs is to show that a divergence between the training distribution and the model distribution obtains its minimum value at equilibrium. Several recent research directions have been motivated by the idea that this divergence is the primary guide for the learning process and that every step of learning should decrease the divergence. We show that this view is overly restrictive. During GAN training, the discriminator provides learning signal in situations where the gradients of the divergences between distributions would not be useful. We provide empirical counterexamples to the view of GAN training as divergence minimization. Specifically, we demonstrate that GANs are able to learn distributions in situations where the divergence minimization point of view predicts they would fail. We also show that gradient penalties motivated from the divergence minimization perspective are equally helpful when applied in other contexts in which the divergence minimization perspective does not predict they would be helpful. This contributes to a growing body of evidence that GAN training may be more usefully viewed as approaching Nash equilibria via trajectories that do not necessarily minimize a specific divergence at each step.

##### Abstract (translated by Google)
生成对抗网络（GAN）是一组生成模型，不会使单个训练标准最小化。与其他生成模型不同，通过发生器（生成模型）和鉴别器（提供训练信号的老师）之间的游戏来学习数据分布，每个鉴定器使自己的成本最小化。 GAN被设计成达到纳什均衡，在这种均衡下，每个参与者不能在不改变其他参与者的参数的情况下降低其成本。 GANs理论的一个有用的方法是表明训练分布和模型分布之间的差异在平衡时得到它的最小值。最近的一些研究方向受到了这样一个观点的启发，即这种分歧是学习过程的主要指导，每一个学习阶段都应该减少分歧。我们表明这个观点过于严格。在GAN训练期间，鉴别器在分布之间的差异梯度不可用的情况下提供学习信号。我们提供了GAN训练的经验反例作为分歧最小化。具体而言，我们证明了GANs能够在分歧最小化观点预测他们将失败的情况下学习分布。我们还表明，从散度最小化角度出发的梯度惩罚同样适用于其他背景下，其中散度最小化的观点并不预测他们会有所帮助。这有助于越来越多的证据表明，GAN训练可能更有用地被看作是通过轨迹来逼近纳什均衡，而轨迹不一定最小化每一步的特定分歧。

##### URL
[https://arxiv.org/abs/1710.08446](https://arxiv.org/abs/1710.08446)

##### PDF
[https://arxiv.org/pdf/1710.08446](https://arxiv.org/pdf/1710.08446)

