---
layout: post
title: "Consensus-based Sequence Training for Video Captioning"
date: 2017-12-27 09:38:52
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Caption
author: Sang Phan, Gustav Eje Henter, Yusuke Miyao, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Captioning models are typically trained using the cross-entropy loss. However, their performance is evaluated on other metrics designed to better correlate with human assessments. Recently, it has been shown that reinforcement learning (RL) can directly optimize these metrics in tasks such as captioning. However, this is computationally costly and requires specifying a baseline reward at each step to make training converge. We propose a fast approach to optimize one's objective of interest through the REINFORCE algorithm. First we show that, by replacing model samples with ground-truth sentences, RL training can be seen as a form of weighted cross-entropy loss, giving a fast, RL-based pre-training algorithm. Second, we propose to use the consensus among ground-truth captions of the same video as the baseline reward. This can be computed very efficiently. We call the complete proposal Consensus-based Sequence Training (CST). Applied to the MSRVTT video captioning benchmark, our proposals train significantly faster than comparable methods and establish a new state-of-the-art on the task, improving the CIDEr score from 47.3 to 54.2.

##### Abstract (translated by Google)
通常使用交叉熵损失来训练字幕模型。但是，他们的绩效是根据其他旨在与人类评估更好地相关的指标进行评估的。最近，已经表明强化学习（RL）可以直接优化诸如字幕之类的任务中的这些度量。然而，这在计算上是昂贵的并且需要在每个步骤指定基线奖励以使训练收敛。我们提出了一种通过REINFORCE算法优化一个人感兴趣的目标的快速方法。首先，我们表明，通过用地面实况句子替换模型样本，RL训练可以被看作是加权交叉熵损失的一种形式，提供了一种快速的，基于RL的预训练算法。其次，我们建议使用同一视频的地面实况字幕中的共识作为基线奖励。这可以非常有效地计算。我们将完整的提案称为基于共识的序列培训（CST）。应用于MSRVTT视频字幕基准测试，我们的建议训练速度明显快于同类方法，并在任务上建立了新的最新技术水平，将CIDEr评分从47.3提高到54.2。

##### URL
[https://arxiv.org/abs/1712.09532](https://arxiv.org/abs/1712.09532)

##### PDF
[https://arxiv.org/pdf/1712.09532](https://arxiv.org/pdf/1712.09532)

