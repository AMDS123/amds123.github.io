---
layout: post
title: "End-to-end Learning of Action Detection from Frame Glimpses in Videos"
date: 2017-03-13 07:33:15
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Serena Yeung, Olga Russakovsky, Greg Mori, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce a fully end-to-end approach for action detection in videos that learns to directly predict the temporal bounds of actions. Our intuition is that the process of detecting actions is naturally one of observation and refinement: observing moments in video, and refining hypotheses about when an action is occurring. Based on this insight, we formulate our model as a recurrent neural network-based agent that interacts with a video over time. The agent observes video frames and decides both where to look next and when to emit a prediction. Since backpropagation is not adequate in this non-differentiable setting, we use REINFORCE to learn the agent's decision policy. Our model achieves state-of-the-art results on the THUMOS'14 and ActivityNet datasets while observing only a fraction (2% or less) of the video frames.

##### Abstract (translated by Google)
在这项工作中，我们介绍了一个完全端到端的方法来检测视频中的动作，从而直接预测动作的时间界限。我们的直觉是，检测行为的过程自然是观察和细化的过程：观察视频中的瞬间，并且提炼关于何时发生的假设。基于这种见解，我们将我们的模型制定为基于循环的神经网络的代理，与时间上的视频进行交互。代理观察视频帧，并决定下一步到何处以及何时发出预测。由于反向传播在这个不可区分的背景下是不够的，我们使用REINFORCE来学习代理的决策策略。我们的模型在THUMOS'14和ActivityNet数据集上实现了最新的结果，同时只观察了一小部分（2％或更少）的视频帧。

##### URL
[https://arxiv.org/abs/1511.06984](https://arxiv.org/abs/1511.06984)

##### PDF
[https://arxiv.org/pdf/1511.06984](https://arxiv.org/pdf/1511.06984)

