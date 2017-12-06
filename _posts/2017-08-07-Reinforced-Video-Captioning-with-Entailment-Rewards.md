---
layout: post
title: "Reinforced Video Captioning with Entailment Rewards"
date: 2017-08-07 20:50:24
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Caption
author: Ramakanth Pasunuru, Mohit Bansal
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models have shown promising improvements on the temporal task of video captioning, but they optimize word-level cross-entropy loss during training. First, using policy gradient and mixed-loss methods for reinforcement learning, we directly optimize sentence-level task-based metrics (as rewards), achieving significant improvements over the baseline, based on both automatic metrics and human evaluation on multiple datasets. Next, we propose a novel entailment-enhanced reward (CIDEnt) that corrects phrase-matching based metrics (such as CIDEr) to only allow for logically-implied partial matches and avoid contradictions, achieving further significant improvements over the CIDEr-reward model. Overall, our CIDEnt-reward model achieves the new state-of-the-art on the MSR-VTT dataset.

##### Abstract (translated by Google)
序列到序列模型已经显示了在视频字幕的时间任务上的有希望的改进，但是它们优化了训练期间的字级交叉熵损失。首先，使用策略梯度和混合损失方法进行强化学习，直接优化基于任务的基于度量的度量（作为奖励），基于多个数据集上的自动度量和人为评估，实现基线的显着改善。接下来，我们提出了一种新颖的包含增强的奖励（CIDEnt），用于纠正基于短语匹配的度量（例如CIDEr），以仅允许逻辑暗示的部分匹配并避免矛盾，实现了比CIDEr奖励模型更大的改进。总的来说，我们的CIDEnt-reward模型实现了MSR-VTT数据集的最新技术。

##### URL
[https://arxiv.org/abs/1708.02300](https://arxiv.org/abs/1708.02300)

