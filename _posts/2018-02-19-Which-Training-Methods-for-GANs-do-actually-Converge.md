---
layout: post
title: "Which Training Methods for GANs do actually Converge?"
date: 2018-02-19 10:40:54
categories: arXiv_CV
tags: arXiv_CV Regularization GAN
author: Lars Mescheder, Andreas Geiger, Sebastian Nowozin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown local convergence of GAN training for absolutely continuous data and generator distributions. In this paper, we show that the requirement of absolute continuity is necessary: we describe a simple yet prototypical counterexample showing that in the more realistic case of distributions that are not absolutely continuous, unregularized GAN training is not always convergent. Furthermore, we discuss regularization strategies that were recently proposed to stabilize GAN training. Our analysis shows that GAN training with instance noise or zero-centered gradient penalties converges. On the other hand, we show that Wasserstein-GANs and WGAN-GP with a finite number of discriminator updates per generator update do not always converge to the equilibrium point. We discuss these results, leading us to a new explanation for the stability problems of GAN training. Based on our analysis, we extend our convergence results to more general GANs and prove local convergence for simplified gradient penalties even if the generator and data distribution lie on lower dimensional manifolds. We find these penalties to work well in practice and use them to learn a generative image model of all 1000 Imagenet classes in a single GAN with little hyperparameter tuning.

##### Abstract (translated by Google)
最近的研究表明，GAN训练对绝对连续的数据和发生器分布的局部收敛。在本文中，我们表明绝对连续性的要求是必要的：我们描述了一个简单而原型的反例，表明在非绝对连续的更现实的分布情况下，非规范化的GAN训练并不总是收敛的。此外，我们讨论最近提出的用于稳定GAN训练的正则化策略。我们的分析表明，具有实例噪声或零中心梯度损失的GAN训练收敛。另一方面，我们证明每个发生器更新有限个鉴别器更新的Wasserstein-GANs和WGAN-GP并不总是收敛于平衡点。我们讨论这些结果，使我们对GAN训练的稳定性问题有了新的解释。根据我们的分析，我们将收敛结果扩展到更一般的GAN，即使发生器和数据分布位于低维流形上，也证明了简化梯度惩罚的局部收敛性。我们发现这些惩罚在实践中运行良好，并使用它们在单个GAN中学习所有1000个Imagenet类的生成图像模型，而只需少量超参数调整。

##### URL
[https://arxiv.org/abs/1801.04406](https://arxiv.org/abs/1801.04406)

##### PDF
[https://arxiv.org/pdf/1801.04406](https://arxiv.org/pdf/1801.04406)

