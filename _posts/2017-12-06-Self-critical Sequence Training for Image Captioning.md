---
layout: post
title: 'Self-critical Sequence Training for Image Captioning'
date: 2017-12-06 08:02:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption
author: Steven J. Rennie, Etienne Marcheret, Youssef Mroueh, Jarret Ross, Vaibhava Goel
---

* content
{:toc}

##### Abstract
Recently it has been shown that policy-gradient methods for reinforcement learning can be utilized to train deep end-to-end systems directly on non-differentiable metrics for the task at hand. In this paper we consider the problem of optimizing image captioning systems using reinforcement learning, and show that by carefully optimizing our systems using the test metrics of the MSCOCO task, significant gains in performance can be realized. Our systems are built using a new optimization approach that we call self-critical sequence training (SCST). SCST is a form of the popular REINFORCE algorithm that, rather than estimating a "baseline" to normalize the rewards and reduce variance, utilizes the output of its own test-time inference algorithm to normalize the rewards it experiences. Using this approach, estimating the reward signal (as actor-critic methods must do) and estimating normalization (as REINFORCE algorithms typically do) is avoided, while at the same time harmonizing the model with respect to its test-time inference procedure. Empirically we find that directly optimizing the CIDEr metric with SCST and greedy decoding at test-time is highly effective. Our results on the MSCOCO evaluation sever establish a new state-of-the-art on the task, improving the best result in terms of CIDEr from 104.9 to 114.7.

##### Abstract (translated by Google)
最近已经表明，可以利用用于强化学习的策略梯度方法来直接训练深度端对端系统用于不可区分的度量以用于手头的任务。在本文中，我们考虑使用强化学习优化图像字幕系统的问题，并且表明通过使用MSCOCO任务的测试度量精心优化我们的系统，可以实现显着的性能增益。我们的系统是使用我们称之为自我批评序列训练（SCST）的新优化方法构建的。 SCST是流行的REINFORCE算法的一种形式，它不是通过估计奖励和减少方差的“基线”，而是利用自己的测试时间推理算法的输出来标准化它所经历的奖励。使用这种方法，可以避免估计奖励信号（作为actor-critic方法必须这样做）和估计规范化（正如REINFORCE算法通常所做的那样），同时协调模型与其测试时间推理过程。通过实证我们发现，在测试时直接优化CIDEr指标和SCST以及贪婪解码是非常有效的。我们在MSCOCO评估服务器上的成果确立了一项新的最新技术，将CIDE的最佳结果从104.9提高到了114.7。

##### URL
[https://arxiv.org/abs/1612.00563](https://arxiv.org/abs/1612.00563)

