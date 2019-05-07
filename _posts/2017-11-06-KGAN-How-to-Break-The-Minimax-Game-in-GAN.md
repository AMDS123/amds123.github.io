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


##### URL
[https://arxiv.org/abs/1711.01744](https://arxiv.org/abs/1711.01744)

##### PDF
[https://arxiv.org/pdf/1711.01744](https://arxiv.org/pdf/1711.01744)

