---
layout: post
title: "Detecting egregious responses in neural sequence-to-sequence models"
date: 2018-09-11 19:11:51
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Tianxing He, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we attempt to answer a critical question: whether there exists some input sequence that will cause a well-trained discrete-space neural network sequence-to-sequence (seq2seq) model to generate egregious outputs (aggressive, malicious, attacking, etc.). And if such inputs exist, how to find them efficiently. We adopt an empirical methodology, in which we first create lists of egregious outputs, and then design a discrete optimization algorithm to find input sequences that will generate them. Moreover, the optimization algorithm is enhanced for large vocabulary search and constrained to search for input sequences that are likely to appear in real-world settings. In our experiments, we apply this approach to a dialogue response generation model for two real-world dialogue datasets: Ubuntu and Switchboard, testing whether the model can generate malicious responses. We demonstrate that given the trigger inputs our algorithm finds, a significant number of malicious sentences are assigned a large probability by the model.

##### Abstract (translated by Google)
在这项工作中，我们试图回答一个关键问题：是否存在一些输入序列将导致训练有素的离散空间神经网络序列到序列（seq2seq）模型生成恶劣的输出（攻击性，恶意，攻击，等等。）。如果存在这样的输入，如何有效地找到它们。我们采用经验方法，我们首先创建极端输出列表，然后设计离散优化算法以找到将生成它们的输入序列。此外，优化算法针对大词汇量搜索而增强，并且被约束以搜索可能出现在真实世界设置中的输入序列。在我们的实验中，我们将此方法应用于两个真实世界对话数据集的对话响应生成模型：Ubuntu和Switchboard，测试模型是否可以生成恶意响应。我们证明，给定我们的算法发现的触发输入，模型大量分配了大量的恶意句子。

##### URL
[http://arxiv.org/abs/1809.04113](http://arxiv.org/abs/1809.04113)

##### PDF
[http://arxiv.org/pdf/1809.04113](http://arxiv.org/pdf/1809.04113)

