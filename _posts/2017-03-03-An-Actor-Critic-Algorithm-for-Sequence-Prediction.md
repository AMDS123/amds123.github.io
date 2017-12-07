---
layout: post
title: "An Actor-Critic Algorithm for Sequence Prediction"
date: 2017-03-03 15:43:52
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Caption Prediction
author: Dzmitry Bahdanau, Philemon Brakel, Kelvin Xu, Anirudh Goyal, Ryan Lowe, Joelle Pineau, Aaron Courville, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to training neural networks to generate sequences using actor-critic methods from reinforcement learning (RL). Current log-likelihood training methods are limited by the discrepancy between their training and testing modes, as models must generate tokens conditioned on their previous guesses rather than the ground-truth tokens. We address this problem by introducing a \textit{critic} network that is trained to predict the value of an output token, given the policy of an \textit{actor} network. This results in a training procedure that is much closer to the test phase, and allows us to directly optimize for a task-specific score such as BLEU. Crucially, since we leverage these techniques in the supervised learning setting rather than the traditional RL setting, we condition the critic network on the ground-truth output. We show that our method leads to improved performance on both a synthetic task, and for German-English machine translation. Our analysis paves the way for such methods to be applied in natural language generation tasks, such as machine translation, caption generation, and dialogue modelling.

##### Abstract (translated by Google)
我们提出了一种方法来训练神经网络使用强化学习（RL）的演员 - 评论者方法生成序列。当前的对数似然训练方法受其训练和测试模式之间的差异的限制，因为模型必须产生以先前的猜测为条件的令牌，而不是基于事实的令牌。我们通过引入\ textit {crit}网络来解决这个问题，该网络经过训练，可以根据\ textit {actor}网络的策略预测输出令牌的价值。这导致了一个更接近测试阶段的训练过程，并且允许我们直接优化诸如BLEU之类的任务特定分数。至关重要的是，由于我们在监督学习环境而不是传统的RL环境中利用这些技术，因此我们将评论者网络视为地面真相输出。我们表明，我们的方法导致合成任务和德英机器翻译的性能提高。我们的分析为这些方法应用于自然语言生成任务（如机器翻译，字幕生成和对话建模）铺平了道路。

##### URL
[https://arxiv.org/abs/1607.07086](https://arxiv.org/abs/1607.07086)

##### PDF
[https://arxiv.org/pdf/1607.07086](https://arxiv.org/pdf/1607.07086)

