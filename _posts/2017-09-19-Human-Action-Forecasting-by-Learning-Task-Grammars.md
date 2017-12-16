---
layout: post
title: "Human Action Forecasting by Learning Task Grammars"
date: 2017-09-19 13:12:36
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Recognition
author: Tengda Han, Jue Wang, Anoop Cherian, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
For effective human-robot interaction, it is important that a robotic assistant can forecast the next action a human will consider in a given task. Unfortunately, real-world tasks are often very long, complex, and repetitive; as a result forecasting is not trivial. In this paper, we propose a novel deep recurrent architecture that takes as input features from a two-stream Residual action recognition framework, and learns to estimate the progress of human activities from video sequences -- this surrogate progress estimation task implicitly learns a temporal task grammar with respect to which activities can be localized and forecasted. To learn the task grammar, we propose a stacked LSTM based multi-granularity progress estimation framework that uses a novel cumulative Euclidean loss as objective. To demonstrate the effectiveness of our proposed architecture, we showcase experiments on two challenging robotic assistive tasks, namely (i) assembling an Ikea table from its constituents, and (ii) changing the tires of a car. Our results demonstrate that learning task grammars offers highly discriminative cues improving the forecasting accuracy by more than 9% over the baseline two-stream forecasting model, while also outperforming other competitive schemes.

##### Abstract (translated by Google)
为了实现有效的人机交互，机器人助手能够预测人类在给定任务中将要考虑的下一个动作是非常重要的。不幸的是，现实世界的任务往往是非常漫长，复杂和重复的;因此预测并不是微不足道的。在本文中，我们提出了一种新颖的深层循环体系结构，它从一个双流残差动作识别框架中输入特征，并学习从视频序列中估计人类活动的进度 - 这个替代进度估计任务隐式地学习了一个时间任务关于哪些活动可以被定位和预测的语法。为了学习任务语法，我们提出了一种基于堆积LSTM的多粒度进度估计框架，该框架以新的累积欧几里得损失为目标。为了证明我们提出的建筑的有效性，我们展示了两个具有挑战性的机器人辅助任务的实验，即（i）从其组成部分组装宜家桌子，和（ii）更换汽车的轮胎。我们的研究结果表明，学习任务语法提供了高度区分的线索，比基线双流预测模型提高了超过9％的预测准确性，同时也超越了其他竞争方案。

##### URL
[https://arxiv.org/abs/1709.06391](https://arxiv.org/abs/1709.06391)

##### PDF
[https://arxiv.org/pdf/1709.06391](https://arxiv.org/pdf/1709.06391)

