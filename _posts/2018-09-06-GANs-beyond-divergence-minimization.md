---
layout: post
title: "GANs beyond divergence minimization"
date: 2018-09-06 18:00:26
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Alexia Jolicoeur-Martineau
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) can be interpreted as an adversarial game between two players, a discriminator D and a generator G, in which D learns to classify real from fake data and G learns to generate realistic data by "fooling" D into thinking that fake data is actually real data. Currently, a dominating view is that G actually learns by minimizing a divergence given that the general objective function is a divergence when D is optimal. However, this view has been challenged due to inconsistencies between theory and practice. In this paper, we discuss of the properties associated with most loss functions for G (e.g., saturating/non-saturating f-GAN, LSGAN, WGAN, etc.). We show that these loss functions are not divergences and do not have the same equilibrium as expected of divergences. This suggests that G does not need to minimize the same objective function as D maximize, nor maximize the objective of D after swapping real data with fake data (non-saturating GAN) but can instead use a wide range of possible loss functions to learn to generate realistic data. We define GANs through two separate and independent D maximization and G minimization steps. We generalize the generator step to four new classes of loss functions, most of which are actual divergences (while traditional G loss functions are not). We test a wide variety of loss functions from these four classes on a synthetic dataset and on CIFAR-10. We observe that most loss functions converge well and provide comparable data generation quality to non-saturating GAN, LSGAN, and WGAN-GP generator loss functions, whether we use divergences or non-divergences. These results suggest that GANs do not conform well to the divergence minimization theory and form a much broader range of models than previously assumed.

##### Abstract (translated by Google)
生成对抗网络（GAN）可以被解释为两个玩家之间的对抗性游戏，一个鉴别器D和一个生成器G，其中D学会从假数据中对真实进行分类，并且G学会通过“欺骗”D来思考生成真实数据虚假数据实际上是真实数据。目前，主导观点是G实际上通过最小化分歧来学习，因为当D是最优时，一般目标函数是分歧。然而，由于理论与实践之间的不一致，这种观点受到了挑战。在本文中，我们讨论了与G的大多数损耗函数相关的性质（例如，饱和/非饱和f-GAN，LSGAN，WGAN等）。我们证明这些损失函数不是分歧，并且不具有与预期的分歧相同的均衡。这表明G不需要最小化与D最大化相同的目标函数，也不需要在使用伪数据（非饱和GAN）交换真实数据之后最大化D的目标，而是可以使用各种可能的损失函数来学习生成现实数据。我们通过两个独立且独立的D最大化和G最小化步骤来定义GAN。我们将生成器步骤概括为四类新的损失函数，其中大多数是实际的偏差（而传统的G损失函数则不是）。我们在合成数据集和CIFAR-10上测试了这四类中的各种损失函数。我们观察到大多数损耗函数收敛良好，并且为非饱和GAN，LSGAN和WGAN-GP发生器损失函数提供可比较的数据生成质量，无论我们是使用分歧还是非分散。这些结果表明，GAN不能很好地符合分歧最小化理论，并形成比以前假设的范围更广泛的模型。

##### URL
[http://arxiv.org/abs/1809.02145](http://arxiv.org/abs/1809.02145)

##### PDF
[http://arxiv.org/pdf/1809.02145](http://arxiv.org/pdf/1809.02145)

