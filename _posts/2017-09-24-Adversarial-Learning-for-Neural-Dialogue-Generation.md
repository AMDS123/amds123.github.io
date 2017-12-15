---
layout: post
title: "Adversarial Learning for Neural Dialogue Generation"
date: 2017-09-24 01:44:39
categories: arXiv_SD
tags: arXiv_SD Adversarial Reinforcement_Learning
author: Jiwei Li, Will Monroe, Tianlin Shi, Sébastien Jean, Alan Ritter, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, drawing intuition from the Turing test, we propose using adversarial training for open-domain dialogue generation: the system is trained to produce sequences that are indistinguishable from human-generated dialogue utterances. We cast the task as a reinforcement learning (RL) problem where we jointly train two systems, a generative model to produce response sequences, and a discriminator---analagous to the human evaluator in the Turing test--- to distinguish between the human-generated dialogues and the machine-generated ones. The outputs from the discriminator are then used as rewards for the generative model, pushing the system to generate dialogues that mostly resemble human dialogues. In addition to adversarial training we describe a model for adversarial {\em evaluation} that uses success in fooling an adversary as a dialogue evaluation metric, while avoiding a number of potential pitfalls. Experimental results on several metrics, including adversarial evaluation, demonstrate that the adversarially-trained system generates higher-quality responses than previous baselines.

##### Abstract (translated by Google)
在本文中，从图灵测试的直觉中，我们提出了使用开放对话生成的对抗训练：系统被训练产生与人类生成的对话话语无法区分的序列。我们把这个任务作为一个强化学习（RL）问题，我们共同训练两个系统，一个产生响应序列的生成模型和一个与图灵测试中的人类评估者类似的鉴别器 - 区分人类生成的对话和机器生成的对话。然后将鉴别器的输出用作生成模型的奖励，推动系统产生大部分类似于人类对话的对话。除了对抗训练之外，我们还描述了一种对抗性评估模型，它利用成功欺骗敌手作为对话评估指标，同时避免了一些潜在的隐患。包括对抗性评估在内的若干指标的实验结果表明，敌对方培训的系统比之前的基线产生更高质量的响应。

##### URL
[https://arxiv.org/abs/1701.06547](https://arxiv.org/abs/1701.06547)

##### PDF
[https://arxiv.org/pdf/1701.06547](https://arxiv.org/pdf/1701.06547)

