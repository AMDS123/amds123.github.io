---
layout: post
title: "Do GANs actually learn the distribution? An empirical study"
date: 2017-07-01 03:25:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Sanjeev Arora, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Do GANS (Generative Adversarial Nets) actually learn the target distribution? The foundational paper of (Goodfellow et al 2014) suggested they do, if they were given sufficiently large deep nets, sample size, and computation time. A recent theoretical analysis in Arora et al (to appear at ICML 2017) raised doubts whether the same holds when discriminator has finite size. It showed that the training objective can approach its optimum value even if the generated distribution has very low support ---in other words, the training objective is unable to prevent mode collapse. The current note reports experiments suggesting that such problems are not merely theoretical. It presents empirical evidence that well-known GANs approaches do learn distributions of fairly low support, and thus presumably are not learning the target distribution. The main technical contribution is a new proposed test, based upon the famous birthday paradox, for estimating the support size of the generated distribution.

##### Abstract (translated by Google)
GANS（Generative Adversarial Nets）是否真正了解目标分布？ （Goodfellow等人，2014年）的基础论文建议，如果它们被赋予了足够大的深度网络，样本量和计算时间的话。 Arora等人最近的理论分析（出现在ICML 2017上）提出了疑问，当鉴别器的大小有限时，这种分析是否成立。结果表明，即使生成的分布支持度很低，即训练目标不能防止模式崩溃，训练目标也能接近其最优值。当前的笔记报告实验表明这样的问题不仅仅是理论上的。它提供了经验证据，知名的GANs方法确实学到了相当低的支持分布，因此可能没有学习目标分布。主要的技术贡献是基于着名的生日悖论提出的一个新测试，用于估计生成的分布的支持大小。

##### URL
[https://arxiv.org/abs/1706.08224](https://arxiv.org/abs/1706.08224)

##### PDF
[https://arxiv.org/pdf/1706.08224](https://arxiv.org/pdf/1706.08224)

