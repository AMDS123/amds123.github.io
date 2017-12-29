---
layout: post
title: "Consensus-based Sequence Training for Video Captioning"
date: 2017-12-27 09:38:52
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Caption
author: Sang Phan, Gustav Eje Henter, Yusuke Miyao, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Captioning models are typically trained using the cross-entropy loss. However, their performance is evaluated on other metrics designed to better correlate with human assessments. Recently, it has been shown that reinforcement learning (RL) can directly optimize these metrics in tasks such as captioning. However, this is computationally costly and requires specifying a baseline reward at each step to make training converge. We propose a fast approach to optimize one's objective of interest through the REINFORCE algorithm. First we show that, by replacing model samples with ground-truth sentences, RL training can be seen as a form of weighted cross-entropy loss, giving a fast, RL-based pre-training algorithm. Second, we propose to use the consensus among ground-truth captions of the same video as the baseline reward. This can be computed very efficiently. We call the complete proposal Consensus-based Sequence Training (CST). Applied to the MSRVTT video captioning benchmark, our proposals train significantly faster than comparable methods and establish a new state-of-the-art on the task, improving the CIDEr score from 47.3 to 54.2.

##### Abstract (translated by Google)
字幕模型通常使用交叉熵损失进行训练。然而，他们的表现是评估其他指标，旨在更好地与人体评估相关联。最近，已经表明，强化学习（RL）可以直接优化这些度量标题的任务。然而，这在计算上是昂贵的，并且需要在每个步骤中指定基线奖励以使训练收敛。我们提出了一种快速的方法来通过REINFORCE算法来优化一个人的兴趣目标。首先我们证明，通过将模型样本替换为地面真值语句，RL训练可以被看作是加权交叉熵损失的一种形式，给出了一个快速的，基于RL的预训练算法。其次，我们建议使用同一视频的地面实况标题中的共识作为基线奖励。这可以非常有效地计算。我们称完整提案基于共识的序列培训（CST）。应用到MSRVTT视频字幕基准测试中，我们的方案比同类方法训练速度快得多，建立了一个新的技术水平，将CIDEr得分从47.3提高到了54.2。

##### URL
[http://arxiv.org/abs/1712.09532](http://arxiv.org/abs/1712.09532)

##### PDF
[http://arxiv.org/pdf/1712.09532](http://arxiv.org/pdf/1712.09532)

