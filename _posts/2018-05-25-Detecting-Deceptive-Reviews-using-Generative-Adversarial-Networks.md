---
layout: post
title: "Detecting Deceptive Reviews using Generative Adversarial Networks"
date: 2018-05-25 21:06:56
categories: arXiv_AI
tags: arXiv_AI Review Adversarial GAN Text_Classification Reinforcement_Learning Classification
author: Hojjat Aghakhani, Aravind Machiry, Shirin Nilizadeh, Christopher Kruegel, Giovanni Vigna
mathjax: true
---

* content
{:toc}

##### Abstract
In the past few years, consumer review sites have become the main target of deceptive opinion spam, where fictitious opinions or reviews are deliberately written to sound authentic. Most of the existing work to detect the deceptive reviews focus on building supervised classifiers based on syntactic and lexical patterns of an opinion. With the successful use of Neural Networks on various classification applications, in this paper, we propose FakeGAN a system that for the first time augments and adopts Generative Adversarial Networks (GANs) for a text classification task, in particular, detecting deceptive reviews. Unlike standard GAN models which have a single Generator and Discriminator model, FakeGAN uses two discriminator models and one generative model. The generator is modeled as a stochastic policy agent in reinforcement learning (RL), and the discriminators use Monte Carlo search algorithm to estimate and pass the intermediate action-value as the RL reward to the generator. Providing the generator model with two discriminator models avoids the mod collapse issue by learning from both distributions of truthful and deceptive reviews. Indeed, our experiments show that using two discriminators provides FakeGAN high stability, which is a known issue for GAN architectures. While FakeGAN is built upon a semi-supervised classifier, known for less accuracy, our evaluation results on a dataset of TripAdvisor hotel reviews show the same performance in terms of accuracy as of the state-of-the-art approaches that apply supervised machine learning. These results indicate that GANs can be effective for text classification tasks. Specifically, FakeGAN is effective at detecting deceptive reviews.

##### Abstract (translated by Google)
在过去的几年中，消费者评论网站已成为欺诈性意见垃圾邮件的主要目标，其中虚构的意见或评论被刻意写成真实的。检测欺骗性评论的现有工作大多集中在基于意见的句法和词汇模式构建监督分类器上。随着神经网络在各种分类应用中的成功应用，本文中我们提出FakeGAN系统首次增加并采用生成对抗网络（GAN）进行文本分类任务，特别是检测欺骗性评论。与具有单一发生器和鉴别器模型的标准GAN模型不同，FakeGAN使用两个鉴别器模型和一个生成模型。生成器被建模为强化学习（RL）中的随机策略代理，鉴别器使用蒙特卡罗搜索算法来估计中间活动值并将其作为RL回报传递给生成器。提供带有两个鉴别器模型的发生器模型，通过从真实和欺骗性评论的分布中学习，避免了模块崩溃问题。实际上，我们的实验表明，使用两个鉴别器可以为FakeGAN提供高稳定性，这对于GAN体系结构来说是已知的问题。尽管FakeGAN是建立在一个半监督分类器上的，它的精确度较低，但我们对TripAdvisor酒店评论数据集的评估结果显示，与应用监督机器学习的最新方法相比，其准确性表现相同。这些结果表明GAN可以对文本分类任务有效。具体来说，FakeGAN在检测欺骗性评论方面非常有效。

##### URL
[http://arxiv.org/abs/1805.10364](http://arxiv.org/abs/1805.10364)

##### PDF
[http://arxiv.org/pdf/1805.10364](http://arxiv.org/pdf/1805.10364)

