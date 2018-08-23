---
layout: post
title: "Deep Adaptive Temporal Pooling for Activity Recognition"
date: 2018-08-22 08:29:38
categories: arXiv_AI
tags: arXiv_AI Attention Classification Recognition
author: Sibo Song, Ngai-Man Cheung, Vijay Chandrasekhar, Bappaditya Mandal
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have recently achieved competitive accuracy for human activity recognition. However, there is room for improvement, especially in modeling long-term temporal importance and determining the activity relevance of different temporal segments in a video. To address this problem, we propose a learnable and differentiable module: Deep Adaptive Temporal Pooling (DATP). DATP applies a self-attention mechanism to adaptively pool the classification scores of different video segments. Specifically, using frame-level features, DATP regresses importance of different temporal segments and generates weights for them. Remarkably, DATP is trained using only the video-level label. There is no need of additional supervision except video-level activity class label. We conduct extensive experiments to investigate various input features and different weight models. Experimental results show that DATP can learn to assign large weights to key video segments. More importantly, DATP can improve training of frame-level feature extractor. This is because relevant temporal segments are assigned large weights during back-propagation. Overall, we achieve state-of-the-art performance on UCF101, HMDB51 and Kinetics datasets.

##### Abstract (translated by Google)
深度神经网络最近实现了人类活动识别的竞争准确性。然而，存在改进的空间，尤其是在建模长期时间重要性和确定视频中不同时间片段的活动相关性方面。为了解决这个问题，我们提出了一个可学习和可区分的模块：深度自适应时间池（DATP）。 DATP应用自我关注机制来自适应地汇集不同视频片段的分类分数。具体而言，使用帧级特征，DATP回归不同时间段的重要性并为它们生成权重。值得注意的是，DATP仅使用视频级标签进行培训。除视频级活动类标签外，无需额外监督。我们进行了大量实验来研究各种输入特征和不同的权重模型。实验结果表明，DATP可以学习为关键视频片段分配大权重。更重要的是，DATP可以改进帧级特征提取器的训练。这是因为在反向传播期间向相关时间段分配了大权重。总的来说，我们在UCF101，HMDB51和Kinetics数据集上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1808.07272](http://arxiv.org/abs/1808.07272)

##### PDF
[http://arxiv.org/pdf/1808.07272](http://arxiv.org/pdf/1808.07272)

