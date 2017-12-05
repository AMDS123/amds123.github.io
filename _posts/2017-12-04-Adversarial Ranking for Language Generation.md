---
layout: post
title:  'Adversarial Ranking for Language Generation'
date:   2017-12-05 18:45:01
categories: CL
tags: CL
author: Kevin Lin, Dianqi Li, Xiaodong He, Zhengyou Zhang, Ming-Ting Sun
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) have great successes on synthesizing data. However, the existing GANs restrict the discriminator to be a binary classifier, and thus limit their learning capacity for tasks that need to synthesize output with rich structures such as natural language descriptions. In this paper, we propose a novel generative adversarial network, RankGAN, for generating high-quality language descriptions. Rather than training the discriminator to learn and assign absolute binary predicate for individual data sample, the proposed RankGAN is able to analyze and rank a collection of human-written and machine-written sentences by giving a reference group. By viewing a set of data samples collectively and evaluating their quality through relative ranking scores, the discriminator is able to make better assessment which in turn helps to learn a better generator. The proposed RankGAN is optimized through the policy gradient technique. Experimental results on multiple public datasets clearly demonstrate the effectiveness of the proposed approach.

##### Abstract (translated by Google)
生成对抗网络（GAN）在合成数据方面取得了巨大的成功。然而，现有的GAN将鉴别器限制为二元分类器，从而限制了其需要合成输出的任务的学习能力，如自然语言描述等丰富的结构。在本文中，我们提出了一个新的生成敌对网络，RankGAN，用于生成高质量的语言描述。提出的RankGAN不是通过训练鉴别器来学习和分配单个数据样本的绝对二元谓词，而是通过给出一个参考组来分析和排列一组人类写作和机器写作的句子。通过集中查看一组数据样本并通过相对排名分数来评估其质量，鉴别器能够做出更好的评估，从而有助于学习更好的发生器。所提出的RankGAN通过策略梯度技术进行了优化。在多个公共数据集上的实验结果清楚地证明了所提出方法的有效性。

