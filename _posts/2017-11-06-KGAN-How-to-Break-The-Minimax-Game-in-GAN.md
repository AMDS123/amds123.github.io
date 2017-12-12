---
layout: post
title: "KGAN: How to Break The Minimax Game in GAN"
date: 2017-11-06 06:33:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Trung Le, Tu Dinh Nguyen, Dinh Phung
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) were intuitively and attractively explained under the perspective of game theory, wherein two involving parties are a discriminator and a generator. In this game, the task of the discriminator is to discriminate the real and generated (i.e., fake) data, whilst the task of the generator is to generate the fake data that maximally confuses the discriminator. In this paper, we propose a new viewpoint for GANs, which is termed as the minimizing general loss viewpoint. This viewpoint shows a connection between the general loss of a classification problem regarding a convex loss function and a f-divergence between the true and fake data distributions. Mathematically, we proposed a setting for the classification problem of the true and fake data, wherein we can prove that the general loss of this classification problem is exactly the negative f-divergence for a certain convex function f. This allows us to interpret the problem of learning the generator for dismissing the f-divergence between the true and fake data distributions as that of maximizing the general loss which is equivalent to the min-max problem in GAN if the Logistic loss is used in the classification problem. However, this viewpoint strengthens GANs in two ways. First, it allows us to employ any convex loss function for the discriminator. Second, it suggests that rather than limiting ourselves in NN-based discriminators, we can alternatively utilize other powerful families. Bearing this viewpoint, we then propose using the kernel-based family for discriminators. This family has two appealing features: i) a powerful capacity in classifying non-linear nature data and ii) being convex in the feature space. Using the convexity of this family, we can further develop Fenchel duality to equivalently transform the max-min problem to the max-max dual problem.

##### Abstract (translated by Google)
生成对抗网络（GANs）在博弈论的视角下被直观和有吸引力地解释，其中涉及到的两方是鉴别者和发生者。在这个游戏中，鉴别器的任务是鉴别真实的和生成的（即伪造的）数据，而生成器的任务是生成最大程度上混淆鉴别器的假数据。在本文中，我们为GAN提出了一个新的观点，被称为最小化一般损失观点。这个观点显示了关于凸损失函数的分类问题的一般损失与真假数据分布之间的f-分歧之间的关系。在数学上，我们提出了对真假数据分类问题的一个设置，其中我们可以证明这个分类问题的一般损失恰好是某个凸函数f的负f-散度。这使得我们可以解释学习发生器的问题，以消除真假数据分布之间的f-分歧，即如果在GAN中使用Logistic损失，则最大化与GAN中的最小 - 最大问题相当的总损失分类问题。但是，这个观点在两个方面加强了GANs。首先，它允许我们使用鉴别器的任何凸损失函数。其次，它表明，我们可以选择使用其他强大的家庭，而不是限制自己在神经网络的鉴别。基于这个观点，我们提出使用基于内核的鉴别器族。该族具有两个吸引人的特征：i）对非线性自然数据进行分类的强大能力和ii）在特征空间中凸的特征。利用这个家族的凸性，我们可以进一步发展Fenchel对偶，等价地将最大最小问题转化为最大最大对偶问题。

##### URL
[https://arxiv.org/abs/1711.01744](https://arxiv.org/abs/1711.01744)

##### PDF
[https://arxiv.org/pdf/1711.01744](https://arxiv.org/pdf/1711.01744)

