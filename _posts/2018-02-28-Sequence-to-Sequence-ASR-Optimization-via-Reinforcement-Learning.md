---
layout: post
title: "Sequence-to-Sequence ASR Optimization via Reinforcement Learning"
date: 2018-02-28 13:44:38
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Reinforcement_Learning Optimization Inference Prediction Recognition
author: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of sequence-to-sequence approaches in automatic speech recognition (ASR) systems, the models still suffer from several problems, mainly due to the mismatch between the training and inference conditions. In the sequence-to-sequence architecture, the model is trained to predict the grapheme of the current time-step given the input of speech signal and the ground-truth grapheme history of the previous time-steps. However, it remains unclear how well the model approximates real-world speech during inference. Thus, generating the whole transcription from scratch based on previous predictions is complicated and errors can propagate over time. Furthermore, the model is optimized to maximize the likelihood of training data instead of error rate evaluation metrics that actually quantify recognition quality. This paper presents an alternative strategy for training sequence-to-sequence ASR models by adopting the idea of reinforcement learning (RL). Unlike the standard training scheme with maximum likelihood estimation, our proposed approach utilizes the policy gradient algorithm. We can (1) sample the whole transcription based on the model's prediction in the training process and (2) directly optimize the model with negative Levenshtein distance as the reward. Experimental results demonstrate that we significantly improved the performance compared to a model trained only with maximum likelihood estimation.

##### Abstract (translated by Google)
尽管自动语音识别（ASR）系统中序列到序列方法的成功，但模型仍然存在几个问题，主要是由于训练和推理条件之间的不匹配。在顺序到顺序架构中，模型被训练来预测当前时间步的字形，给定语音信号的输入和前一时间步的地面实况字形历史。然而，目前还不清楚该模型在推断过程中接近真实世界的语音。因此，基于先前的预测从头开始生成整个转录是复杂的并且错误可以随着时间传播。此外，该模型被优化以最大化训练数据的可能性而不是实际量化识别质量的差错率评估度量。本文通过采用强化学习（RL）的思想，提出了一种用于训练序列 - 序列ASR模型的替代策略。与具有最大似然估计的标准训练方案不同，我们提出的方法利用策略梯度算法。我们可以（1）在训练过程中根据模型的预测对整个转录进行采样，（2）直接优化具有负Levenshtein距离作为奖励的模型。实验结果表明，与仅使用最大似然估计训练的模型相比，我们显着提高了性能。

##### URL
[http://arxiv.org/abs/1710.10774](http://arxiv.org/abs/1710.10774)

##### PDF
[http://arxiv.org/pdf/1710.10774](http://arxiv.org/pdf/1710.10774)

