---
layout: post
title: "Constructing Narrative Event Evolutionary Graph for Script Event Prediction"
date: 2018-05-14 09:23:26
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference Prediction
author: Zhongyang Li, Xiao Ding, Ting Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Script event prediction requires a model to predict the subsequent event given an existing event context. Previous models based on event pairs or event chains cannot make full use of dense event connections, which may limit their capability of event prediction. To remedy this, we propose constructing an event graph to better utilize the event network information for script event prediction. In particular, we first extract narrative event chains from large quantities of news corpus, and then construct a narrative event evolutionary graph (NEEG) based on the extracted chains. NEEG can be seen as a knowledge base that describes event evolutionary principles and patterns. To solve the inference problem on NEEG, we present a scaled graph neural network (SGNN) to model event interactions and learn better event representations. Instead of computing the representations on the whole graph, SGNN processes only the concerned nodes each time, which makes our model feasible to large-scale graphs. By comparing the similarity between input context event representations and candidate event representations, we can choose the most reasonable subsequent event. Experimental results on widely used New York Times corpus demonstrate that our model significantly outperforms state-of-the-art baseline methods, by using standard multiple choice narrative cloze evaluation.

##### Abstract (translated by Google)
脚本事件预测需要一个模型来预测给定现有事件上下文的后续事件。基于事件对或事件链的先前模型不能充分利用密集事件连接，这可能会限制事件预测的能力。为了解决这个问题，我们建议构建一个事件图，以更好地利用事件网络信息进行脚本事件预测。特别是，我们首先从大量的新闻语料中提取叙事事件链，然后基于提取的链构建叙事事件进化图（NEEG）。 NEEG可以被看作是描述事件演化原理和模式的知识库。为了解决NEEG的推理问题，我们提出了一个缩放图神经网络（SGNN）来模拟事件交互并学习更好的事件表示。 SGNN并不是在整个图上计算表示，而是每次只处理相关节点，这使得我们的模型对于大规模图是可行的。通过比较输入上下文事件表示和候选事件表示之间的相似性，我们可以选择最合理的后续事件。广泛使用的纽约时报语料库的实验结果表明，我们的模型通过使用标准多项选择叙述完整性评估，显着优于最先进的基线方法。

##### URL
[https://arxiv.org/abs/1805.05081](https://arxiv.org/abs/1805.05081)

##### PDF
[https://arxiv.org/pdf/1805.05081](https://arxiv.org/pdf/1805.05081)

