---
layout: post
title: "Multi-shot Pedestrian Re-identification via Sequential Decision Making"
date: 2017-12-19 23:24:04
categories: arXiv_CV
tags: arXiv_CV Re-identification Reinforcement_Learning
author: Jianfu Zhang, Naiyan Wang, Liqing Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-shot pedestrian re-identification problem is at the core of surveillance video analysis. It matches two tracks of pedestrians from different cameras. In contrary to existing works that aggregate single frames features by time series model such as recurrent neural network, in this paper, we propose an interpretable reinforcement learning based approach to this problem. Particularly, we train an agent to verify a pair of images at each time. The agent could choose to output the result (same or different) or request another pair of images to see (unsure). By this way, our model implicitly learns the difficulty of image pairs, and postpone the decision when the model does not accumulate enough evidence. Moreover, by adjusting the reward for unsure action, we can easily trade off between speed and accuracy. In three open benchmarks, our method are competitive with the state-of-the-art methods while only using 3% to 6% images. These promising results demonstrate that our method is favorable in both efficiency and performance.

##### Abstract (translated by Google)
多重行人重新识别问题是监控视频分析的核心。它匹配来自不同相机的两条行人轨道。与现有的利用时间序列模型（如递归神经网络）聚合单帧特征的工作相反，本文提出了一个可解释的强化学习的方法来解决这个问题。特别是，我们每次都要训练一个代理来验证一对图像。代理可以选择输出结果（相同或不同）或请求另一对图像看（不确定）。通过这种方式，我们的模型隐含地学习了图像对的难度，并推迟了当模型没有积累足够的证据时的决定。而且，通过调整不确定行为的奖励，我们可以轻松地在速度和准确性之间进行折衷。在三个开放的基准中，我们的方法与最先进的方法相比具有竞争性，而只使用3％到6％的图像。这些有希望的结果表明，我们的方法在效率和性能上都是有利的。

##### URL
[https://arxiv.org/abs/1712.07257](https://arxiv.org/abs/1712.07257)

##### PDF
[https://arxiv.org/pdf/1712.07257](https://arxiv.org/pdf/1712.07257)

