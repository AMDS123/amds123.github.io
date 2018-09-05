---
layout: post
title: "Visual Transfer between Atari Games using Competitive Reinforcement Learning"
date: 2018-09-02 21:34:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning
author: Akshita Mittel, Sowmya Munukutla, Himanshi Yadav
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores the use of deep reinforcement learning agents to transfer knowledge from one environment to another. More specifically, the method takes advantage of asynchronous advantage actor critic (A3C) architecture to generalize a target game using an agent trained on a source game in Atari. Instead of fine-tuning a pre-trained model for the target game, we propose a learning approach to update the model using multiple agents trained in parallel with different representations of the target game. Visual mapping between video sequences of transfer pairs is used to derive new representations of the target game; training on these visual representations of the target game improves model updates in terms of performance, data efficiency and stability. In order to demonstrate the functionality of the architecture, Atari games Pong-v0 and Breakout-v0 are being used from the OpenAI gym environment; as the source and target environment.

##### Abstract (translated by Google)
本文探讨了使用深层强化学习代理将知识从一种环境转移到另一种环境。更具体地，该方法利用异步优势演员评论（A3C）架构来使用在Atari中的源游戏上训练的代理来概括目标游戏。我们提出了一种学习方法，使用与目标游戏的不同表示并行训练的多个代理来更新模型，而不是微调目标游戏的预训练模型。传输对的视频序列之间的视觉映射用于导出目标游戏的新表示;对目标游戏的这些可视化表示的培训改进了性能，数据效率和稳定性方面的模型更新。为了展示架构的功能，Atari游戏Pong-v0和Breakout-v0正在OpenAI健身房环境中使用;作为源和目标环境。

##### URL
[http://arxiv.org/abs/1809.00397](http://arxiv.org/abs/1809.00397)

##### PDF
[http://arxiv.org/pdf/1809.00397](http://arxiv.org/pdf/1809.00397)

