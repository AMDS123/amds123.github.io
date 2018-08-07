---
layout: post
title: "Reinforced Video Captioning with Entailment Rewards"
date: 2017-08-07 20:50:24
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Caption
author: Ramakanth Pasunuru, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models have shown promising improvements on the temporal task of video captioning, but they optimize word-level cross-entropy loss during training. First, using policy gradient and mixed-loss methods for reinforcement learning, we directly optimize sentence-level task-based metrics (as rewards), achieving significant improvements over the baseline, based on both automatic metrics and human evaluation on multiple datasets. Next, we propose a novel entailment-enhanced reward (CIDEnt) that corrects phrase-matching based metrics (such as CIDEr) to only allow for logically-implied partial matches and avoid contradictions, achieving further significant improvements over the CIDEr-reward model. Overall, our CIDEnt-reward model achieves the new state-of-the-art on the MSR-VTT dataset.

##### Abstract (translated by Google)
序列到序列模型已经显示出对视频字幕的时间任务的有希望的改进，但是它们在训练期间优化了字级交叉熵损失。首先，使用政策梯度和混合损失方法进行强化学习，我们直接优化基于任务的句子级度量（作为奖励），基于自动度量和多个数据集的人工评估，在基线上实现显着改进。接下来，我们提出了一种新颖的蕴含增强奖励（CIDEnt），它可以纠正基于短语匹配的指标（例如CIDEr），只允许逻辑隐含的部分匹配并避免矛盾，实现了对CIDEr奖励模型的进一步显着改进。总的来说，我们的CIDEnt-reward模型实现了MSR-VTT数据集的最新技术。

##### URL
[https://arxiv.org/abs/1708.02300](https://arxiv.org/abs/1708.02300)

##### PDF
[https://arxiv.org/pdf/1708.02300](https://arxiv.org/pdf/1708.02300)

