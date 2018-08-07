---
layout: post
title: "Self-critical Sequence Training for Image Captioning"
date: 2017-11-16 02:38:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Optimization Inference
author: Steven J. Rennie, Etienne Marcheret, Youssef Mroueh, Jarret Ross, Vaibhava Goel
mathjax: true
---

* content
{:toc}

##### Abstract
Recently it has been shown that policy-gradient methods for reinforcement learning can be utilized to train deep end-to-end systems directly on non-differentiable metrics for the task at hand. In this paper we consider the problem of optimizing image captioning systems using reinforcement learning, and show that by carefully optimizing our systems using the test metrics of the MSCOCO task, significant gains in performance can be realized. Our systems are built using a new optimization approach that we call self-critical sequence training (SCST). SCST is a form of the popular REINFORCE algorithm that, rather than estimating a "baseline" to normalize the rewards and reduce variance, utilizes the output of its own test-time inference algorithm to normalize the rewards it experiences. Using this approach, estimating the reward signal (as actor-critic methods must do) and estimating normalization (as REINFORCE algorithms typically do) is avoided, while at the same time harmonizing the model with respect to its test-time inference procedure. Empirically we find that directly optimizing the CIDEr metric with SCST and greedy decoding at test-time is highly effective. Our results on the MSCOCO evaluation sever establish a new state-of-the-art on the task, improving the best result in terms of CIDEr from 104.9 to 114.7.

##### Abstract (translated by Google)
最近已经表明，可以利用用于强化学习的策略梯度方法来直接在用于手头任务的不可微分度量上训练深度端到端系统。在本文中，我们考虑使用强化学习优化图像字幕系统的问题，并表明通过使用MSCOCO任务的测试指标仔细优化我们的系统，可以实现显着的性能提升。我们的系统使用一种新的优化方法构建，我们称之为自我关键序列训练（SCST）。 SCST是流行的REINFORCE算法的一种形式，它不是估计用于规范奖励和减少方差的“基线”，而是利用其自己的测试时间推理算法的输出来规范化它所经历的奖励。使用这种方法，可以避免估计奖励信号（作为演员批评方法必须这样做）和估计归一化（如REINFORCE算法通常那样），同时使模型与其测试时间推理过程协调一致。根据经验，我们发现使用SCST直接优化CIDEr指标并在测试时进行贪婪解码非常有效。我们在MSCOCO评估服务器上的结果为该任务建立了一个新的最新技术水平，从而将CIDEr的最佳结果从104.9提高到114.7。

##### URL
[https://arxiv.org/abs/1612.00563](https://arxiv.org/abs/1612.00563)

##### PDF
[https://arxiv.org/pdf/1612.00563](https://arxiv.org/pdf/1612.00563)

