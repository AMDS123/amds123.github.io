---
layout: post
title: "Defending Against Adversarial Attacks by Leveraging an Entire GAN"
date: 2018-05-27 16:47:31
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Gokula Krishnan Santhanam, Paulina Grnarova
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that state-of-the-art models are highly vulnerable to adversarial perturbations of the input. We propose cowboy, an approach to detecting and defending against adversarial attacks by using both the discriminator and generator of a GAN trained on the same dataset. We show that the discriminator consistently scores the adversarial samples lower than the real samples across multiple attacks and datasets. We provide empirical evidence that adversarial samples lie outside of the data manifold learned by the GAN. Based on this, we propose a cleaning method which uses both the discriminator and generator of the GAN to project the samples back onto the data manifold. This cleaning procedure is independent of the classifier and type of attack and thus can be deployed in existing systems.

##### Abstract (translated by Google)
最近的工作表明，最先进的模型非常容易受到投入的对抗干扰。我们提出牛仔，一种通过使用在相同数据集上训练的GAN的鉴别器和生成器来检测和防御对抗攻击的方法。我们表明，鉴别器在多个攻击和数据集中持续评分低于实际样本的敌对样本。我们提供的经验证据表明，敌对样本位于GAN学习的数据流形之外。基于此，我们提出了一种清洁方法，它使用GAN的鉴别器和发生器将样本投影回数据流形。此清洁程序独立于分类器和攻击类型，因此可以部署在现有系统中。

##### URL
[https://arxiv.org/abs/1805.10652](https://arxiv.org/abs/1805.10652)

##### PDF
[https://arxiv.org/pdf/1805.10652](https://arxiv.org/pdf/1805.10652)

