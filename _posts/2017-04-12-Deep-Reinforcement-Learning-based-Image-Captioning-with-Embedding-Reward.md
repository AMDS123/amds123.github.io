---
layout: post
title: "Deep Reinforcement Learning-based Image Captioning with Embedding Reward"
date: 2017-04-12 18:55:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Embedding Prediction
author: Zhou Ren, Xiaoyu Wang, Ning Zhang, Xutao Lv, Li-Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning is a challenging problem owing to the complexity in understanding the image content and diverse ways of describing it in natural language. Recent advances in deep neural networks have substantially improved the performance of this task. Most state-of-the-art approaches follow an encoder-decoder framework, which generates captions using a sequential recurrent prediction model. However, in this paper, we introduce a novel decision-making framework for image captioning. We utilize a "policy network" and a "value network" to collaboratively generate captions. The policy network serves as a local guidance by providing the confidence of predicting the next word according to the current state. Additionally, the value network serves as a global and lookahead guidance by evaluating all possible extensions of the current state. In essence, it adjusts the goal of predicting the correct words towards the goal of generating captions similar to the ground truth captions. We train both networks using an actor-critic reinforcement learning model, with a novel reward defined by visual-semantic embedding. Extensive experiments and analyses on the Microsoft COCO dataset show that the proposed framework outperforms state-of-the-art approaches across different evaluation metrics.

##### Abstract (translated by Google)
图像字幕是一个具有挑战性的问题，因为理解图像内容的复杂性和用自然语言描述它的多种方式。深度神经网络的最新进展大大提高了这项任务的性能。大多数最先进的方法遵循编码器 - 解码器框架，其使用顺序循环预测模型生成字幕。然而，在本文中，我们引入了一个新的图像字幕决策框架。我们利用“政策网络”和“价值网络”来协作生成字幕。政策网络作为本地指导，通过提供根据当前状态预测下一个单词的信心。另外，价值网络通过评估当前状态的所有可能的扩展来充当全局和超前指导。实质上，它调整了预测正确的单词的目标，以生成类似于地面实况标题的标题。我们使用行为者 - 评论者强化学习模型来训练两个网络，并用视觉语义嵌入来定义新的奖励。对微软COCO数据集的大量实验和分析表明，所提出的框架在不同的评估指标上优于最先进的方法。

##### URL
[https://arxiv.org/abs/1704.03899](https://arxiv.org/abs/1704.03899)

##### PDF
[https://arxiv.org/pdf/1704.03899](https://arxiv.org/pdf/1704.03899)

