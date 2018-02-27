---
layout: post
title: "Is Generator Conditioning Causally Related to GAN Performance?"
date: 2018-02-23 23:48:01
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Deep_Learning Relation
author: Augustus Odena, Jacob Buckman, Catherine Olsson, Tom B. Brown, Christopher Olah, Colin Raffel, Ian Goodfellow
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work (Pennington et al, 2017) suggests that controlling the entire distribution of Jacobian singular values is an important design consideration in deep learning. Motivated by this, we study the distribution of singular values of the Jacobian of the generator in Generative Adversarial Networks (GANs). We find that this Jacobian generally becomes ill-conditioned at the beginning of training. Moreover, we find that the average (with z from p(z)) conditioning of the generator is highly predictive of two other ad-hoc metrics for measuring the 'quality' of trained GANs: the Inception Score and the Frechet Inception Distance (FID). We test the hypothesis that this relationship is causal by proposing a 'regularization' technique (called Jacobian Clamping) that softly penalizes the condition number of the generator Jacobian. Jacobian Clamping improves the mean Inception Score and the mean FID for GANs trained on several datasets. It also greatly reduces inter-run variance of the aforementioned scores, addressing (at least partially) one of the main criticisms of GANs.

##### Abstract (translated by Google)
最近的工作（Pennington等，2017）表明，控制雅可比奇异值的整个分布是深度学习中一个重要的设计考虑因素。受此启发，我们研究了生成对冲网络（GAN）中发生器的雅可比行列式奇异值的分布。我们发现这个雅可比主义在培训开始时通常会变得病态。此外，我们发现生成器的平均值（其中z来自p（z））调节对测量经过训练的GAN的“质量”的两个其他特别度量具有高度的预测性：初始得分和Frechet初始距离（FID ）。我们通过提出一种“正则化”技术（称为雅可比钳位）来检验这种关系是因果关系的假设，该技术轻微地惩罚发生器雅可比行为的条件数。雅可比钳位改善了在几个数据集上训练的GANs的平均初始分数和平均FID。它还大大降低了上述分数的运行间差异，解决了（至少部分）GAN的主要批评之一。

##### URL
[https://arxiv.org/abs/1802.08768](https://arxiv.org/abs/1802.08768)

##### PDF
[https://arxiv.org/pdf/1802.08768](https://arxiv.org/pdf/1802.08768)

