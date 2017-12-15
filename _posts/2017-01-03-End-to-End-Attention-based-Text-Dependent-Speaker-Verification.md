---
layout: post
title: "End-to-End Attention based Text-Dependent Speaker Verification"
date: 2017-01-03 01:15:53
categories: arXiv_SD
tags: arXiv_SD Attention
author: Shi-Xiong Zhang, Zhuo Chen, Yong Zhao, Jinyu Li, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
A new type of End-to-End system for text-dependent speaker verification is presented in this paper. Previously, using the phonetically discriminative/speaker discriminative DNNs as feature extractors for speaker verification has shown promising results. The extracted frame-level (DNN bottleneck, posterior or d-vector) features are equally weighted and aggregated to compute an utterance-level speaker representation (d-vector or i-vector). In this work we use speaker discriminative CNNs to extract the noise-robust frame-level features. These features are smartly combined to form an utterance-level speaker vector through an attention mechanism. The proposed attention model takes the speaker discriminative information and the phonetic information to learn the weights. The whole system, including the CNN and attention model, is joint optimized using an end-to-end criterion. The training algorithm imitates exactly the evaluation process --- directly mapping a test utterance and a few target speaker utterances into a single verification score. The algorithm can automatically select the most similar impostor for each target speaker to train the network. We demonstrated the effectiveness of the proposed end-to-end system on Windows $10$ "Hey Cortana" speaker verification task.

##### Abstract (translated by Google)
本文提出了一种新型的文本相关说话人认证端到端系统。以前，使用语音识别/说话人识别DNNs作为说话人验证的特征提取器已经显示出有希望的结果。提取的帧级（DNN瓶颈，后向或d向量）特征被相等地加权并且被合计以计算话语级别的说话者表示（d向量或i向量）。在这项工作中，我们使用说话人鉴别CNN来提取噪声稳健的帧级特征。这些特征巧妙地结合在一起，通过注意机制形成话语级别的说话人矢量。所提出的注意模型将说话人识别信息和语音信息用于学习权重。整个系统，包括CNN和注意模型，都是使用端到端的标准进行联合优化的。训练算法完全模仿评估过程 - 将测试话语和少数目标说话者话语直接映射成单个验证评分。该算法可以为每个目标说话人自动选择最相似的冒名顶替者来训练网络。我们在Windows $ 10 $“Hey Cortana”演讲者验证任务中演示了建议的端到端系统的有效性。

##### URL
[https://arxiv.org/abs/1701.00562](https://arxiv.org/abs/1701.00562)

##### PDF
[https://arxiv.org/pdf/1701.00562](https://arxiv.org/pdf/1701.00562)

