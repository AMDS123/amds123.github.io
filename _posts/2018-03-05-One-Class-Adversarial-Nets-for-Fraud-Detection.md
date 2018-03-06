---
layout: post
title: "One-Class Adversarial Nets for Fraud Detection"
date: 2018-03-05 17:40:24
categories: arXiv_AI
tags: arXiv_AI Review Adversarial Knowledge GAN RNN Classification Detection
author: Panpan Zheng, Shuhan Yuan, Xintao Wu, Jun Li, Aidong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Many online applications, such as online social networks or knowledge bases, are often attacked by malicious users who commit different types of actions such as vandalism on Wikipedia or fraudulent reviews on eBay. Currently, most of the fraud detection approaches require a training dataset that contains records of both benign and malicious users. However, in practice, there are often no or very few records of malicious users. In this paper, we develop one-class adversarial nets (OCAN) for fraud detection using training data with only benign users. OCAN first uses LSTM-Autoencoder to learn the representations of benign users from their sequences of online activities. It then detects malicious users by training a discriminator with a complementary GAN model that is different from the regular GAN model. Experimental results show that our OCAN outperforms the state-of-the-art one-class classification models and achieves comparable performance with the latest multi-source LSTM model that requires both benign and malicious users in the training phase.

##### Abstract (translated by Google)
许多在线应用程序（例如在线社交网络或知识库）常常遭到恶意用户的攻击，他们犯下不同类型的行为，如维基百科上的破坏行为或eBay上的欺诈性评论。目前，大多数欺诈检测方法都需要包含良性用户和恶意用户记录的训练数据集。但是，实际上，恶意用户通常没有或很少有记录。在本文中，我们利用只有良性用户的训练数据开发了一类用于欺诈检测的对抗网络（OCAN）。 OCAN首先使用LSTM-Autoencoder从他们的在线活动序列中学习良性用户的表示。然后，它通过训练具有与常规GAN模型不同的互补GAN模型的鉴别器来检测恶意用户。实验结果表明，我们的OCAN性能优于最先进的单类分类模型，并且与最新的多源LSTM模型相比具有可比性能，该模型需要训练阶段的良性用户和恶意用户。

##### URL
[http://arxiv.org/abs/1803.01798](http://arxiv.org/abs/1803.01798)

##### PDF
[http://arxiv.org/pdf/1803.01798](http://arxiv.org/pdf/1803.01798)

