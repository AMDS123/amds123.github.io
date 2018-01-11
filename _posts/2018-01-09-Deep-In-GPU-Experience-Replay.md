---
layout: post
title: "Deep In-GPU Experience Replay"
date: 2018-01-09 20:52:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ben Parr
mathjax: true
---

* content
{:toc}

##### Abstract
Experience replay allows a reinforcement learning agent to train on samples from a large amount of the most recent experiences. A simple in-RAM experience replay stores these most recent experiences in a list in RAM, and then copies sampled batches to the GPU for training. I moved this list to the GPU, thus creating an in-GPU experience replay, and a training step that no longer has inputs copied from the CPU. I trained an agent to play Super Smash Bros. Melee, using internal game memory values as inputs and outputting controller button presses. A single state in Melee contains 27 floats, so the full experience replay fits on a single GPU. For a batch size of 128, the in-GPU experience replay trained twice as fast as the in-RAM experience replay. As far as I know, this is the first in-GPU implementation of experience replay. Finally, I note a few ideas for fitting the experience replay inside the GPU when the environment state requires more memory.

##### Abstract (translated by Google)
经验回放允许强化学习代理从大量最近的经验中训练样本。一个简单的RAM内存体验重播将这些最新的体验存储在RAM中的列表中，然后将采样的批量复制到GPU进行培训。我将这个列表移动到了GPU中，从而创建了一个GPU中的体验重播，以及一个不再有从CPU复制的输入的训练步骤。我训练一个代理玩超级粉碎兄弟近战，使用内部游戏内存值作为输入和输出控制器按钮按下。近战中的单个状态包含27个浮点，所以完整的体验重放适合单个GPU。对于128的批量处理，内置GPU体验重播的训练速度是内存中体验重播的两倍。据我所知，这是第一次在体验重播的GPU内实现。最后，当环境状态需要更多的内存时，我注意到一些适合GPU内部体验重播的想法。

##### URL
[https://arxiv.org/abs/1801.03138](https://arxiv.org/abs/1801.03138)

##### PDF
[https://arxiv.org/pdf/1801.03138](https://arxiv.org/pdf/1801.03138)

