---
layout: post
title: "Sarcasm Analysis using Conversation Context"
date: 2018-08-22 19:21:04
categories: arXiv_CL
tags: arXiv_CL Attention RNN Detection
author: Debanjan Ghosh, Alexander R. Fabbri, Smaranda Muresan
mathjax: true
---

* content
{:toc}

##### Abstract
Computational models for sarcasm detection have often relied on the content of utterances in isolation. However, the speaker's sarcastic intent is not always apparent without additional context. Focusing on social media discussions, we investigate three issues: (1) does modeling conversation context help in sarcasm detection; (2) can we identify what part of conversation context triggered the sarcastic reply; and (3) given a sarcastic post that contains multiple sentences, can we identify the specific sentence that is sarcastic. To address the first issue, we investigate several types of Long Short-Term Memory (LSTM) networks that can model both the conversation context and the current turn. We show that LSTM networks with sentence-level attention on context and current turn, as well as the conditional LSTM network (Rocktaschel et al. 2016), outperform the LSTM model that reads only the current turn. As conversation context, we consider the prior turn, the succeeding turn or both. Our computational models are tested on two types of social media platforms: Twitter and discussion forums. We discuss several differences between these datasets ranging from their size to the nature of the gold-label annotations. To address the last two issues, we present a qualitative analysis of attention weights produced by the LSTM models (with attention) and discuss the results compared with human performance on the task.

##### Abstract (translated by Google)
用于讽刺检测的计算模型通常依赖于孤立的话语内容。然而，如果没有其他背景，说话者的讽刺意图并不总是显而易见的。关注社交媒体讨论，我们调查了三个问题：（1）建模对话上下文有助于讽刺检测; （2）我们能否识别会话上下文的哪一部分触发了讽刺回复; （3）如果给出一个包含多个句子的讽刺帖子，我们能否识别出具有讽刺性的特定句子。为了解决第一个问题，我们研究了几种类型的长期短期记忆（LSTM）网络，它们可以模拟对话上下文和当前回合。我们表明LSTM网络在上下文和当前转向上具有句子级关注，以及条件LSTM网络（Rocktaschel等人2016），优于仅读取当前转向的LSTM模型。作为对话上下文，我们考虑前一轮，后一轮或两者。我们的计算模型在两种社交媒体平台上进行测试：Twitter和论坛。我们讨论了这些数据集之间的几个差异，从它们的大小到金标注释的性质。为了解决最后两个问题，我们提出了LSTM模型产生的注意力量的定性分析（注意），并讨论了与人类在任务上的表现相比较的结果。

##### URL
[http://arxiv.org/abs/1808.07531](http://arxiv.org/abs/1808.07531)

##### PDF
[http://arxiv.org/pdf/1808.07531](http://arxiv.org/pdf/1808.07531)

