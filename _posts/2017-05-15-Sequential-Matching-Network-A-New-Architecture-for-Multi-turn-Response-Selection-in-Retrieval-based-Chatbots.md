---
layout: post
title: "Sequential Matching Network: A New Architecture for Multi-turn Response Selection in Retrieval-based Chatbots"
date: 2017-05-15 01:50:55
categories: arXiv_CL
tags: arXiv_CL QA RNN Relation
author: Yu Wu, Wei Wu, Chen Xing, Ming Zhou, Zhoujun Li
mathjax: true
---

* content
{:toc}

##### Abstract
We study response selection for multi-turn conversation in retrieval-based chatbots. Existing work either concatenates utterances in context or matches a response with a highly abstract context vector finally, which may lose relationships among utterances or important contextual information. We propose a sequential matching network (SMN) to address both problems. SMN first matches a response with each utterance in the context on multiple levels of granularity, and distills important matching information from each pair as a vector with convolution and pooling operations. The vectors are then accumulated in a chronological order through a recurrent neural network (RNN) which models relationships among utterances. The final matching score is calculated with the hidden states of the RNN. An empirical study on two public data sets shows that SMN can significantly outperform state-of-the-art methods for response selection in multi-turn conversation.

##### Abstract (translated by Google)
我们研究基于检索的聊天机器人中多回合对话的回答选择。现有的工作要么将上下文中的话语串联起来，要么将响应与高度抽象的上下文向量进行匹配，这可能会失去话语或重要上下文信息之间的关系。我们提出一个顺序匹配网络（SMN）来解决这两个问题。 SMN首先在多个粒度级上匹配上下文中的每个话语的响应，并且利用卷积和合并操作将来自每一对的重要匹配信息作为向量提取出来。然后通过循环的神经网络（RNN）按照时间顺序累积矢量，该循环的神经网络模拟话语之间的关系。最终的匹配分数是用RNN的隐藏状态计算的。对两个公共数据集的实证研究表明，SMN在多回合对话中可以显着优于最先进的响应选择方法。

##### URL
[https://arxiv.org/abs/1612.01627](https://arxiv.org/abs/1612.01627)

##### PDF
[https://arxiv.org/pdf/1612.01627](https://arxiv.org/pdf/1612.01627)

