---
layout: post
title: "Topic Aware Neural Response Generation"
date: 2016-09-19 02:09:13
categories: arXiv_CL
tags: arXiv_CL Knowledge QA Attention
author: Chen Xing, Wei Wu, Yu Wu, Jie Liu, Yalou Huang, Ming Zhou, Wei-Ying Ma
mathjax: true
---

* content
{:toc}

##### Abstract
We consider incorporating topic information into the sequence-to-sequence framework to generate informative and interesting responses for chatbots. To this end, we propose a topic aware sequence-to-sequence (TA-Seq2Seq) model. The model utilizes topics to simulate prior knowledge of human that guides them to form informative and interesting responses in conversation, and leverages the topic information in generation by a joint attention mechanism and a biased generation probability. The joint attention mechanism summarizes the hidden vectors of an input message as context vectors by message attention, synthesizes topic vectors by topic attention from the topic words of the message obtained from a pre-trained LDA model, and let these vectors jointly affect the generation of words in decoding. To increase the possibility of topic words appearing in responses, the model modifies the generation probability of topic words by adding an extra probability item to bias the overall distribution. Empirical study on both automatic evaluation metrics and human annotations shows that TA-Seq2Seq can generate more informative and interesting responses, and significantly outperform the-state-of-the-art response generation models.

##### Abstract (translated by Google)
我们考虑将主题信息纳入顺序到顺序框架，以便为聊天机器人生成丰富而有趣的回复。为此，我们提出了一个主题感知序列到序列（TA-Seq2Seq）模型。该模型利用主题模拟人类的先验知识，引导他们在对话中形成丰富而有趣的反应，并通过联合注意机制和偏倚生成概率来利用生成中的主题信息。联合关注机制通过消息关注将输入消息的隐藏向量作为上下文向量进行汇总，并根据预先训练的LDA模型得到的消息的主题词合成主题关注的主题向量，使这些向量共同影响单词在解码。为了增加主题词出现在响应中的可能性，模型通过增加一个额外的概率项来修改主题词的生成概率，以偏离整体分布。自动评估指标和人类注释的实证研究表明，TA-Seq2Seq可以产生更多的信息和有趣的反应，并且明显优于最先进的响应生成模型。

##### URL
[https://arxiv.org/abs/1606.08340](https://arxiv.org/abs/1606.08340)

##### PDF
[https://arxiv.org/pdf/1606.08340](https://arxiv.org/pdf/1606.08340)

