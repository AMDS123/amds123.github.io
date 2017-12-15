---
layout: post
title: "Data Distillation for Controlling Specificity in Dialogue Generation"
date: 2017-02-22 08:32:47
categories: arXiv_SD
tags: arXiv_SD Knowledge Reinforcement_Learning
author: Jiwei Li, Will Monroe, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
People speak at different levels of specificity in different situations. Depending on their knowledge, interlocutors, mood, etc.} A conversational agent should have this ability and know when to be specific and when to be general. We propose an approach that gives a neural network--based conversational agent this ability. Our approach involves alternating between \emph{data distillation} and model training : removing training examples that are closest to the responses most commonly produced by the model trained from the last round and then retrain the model on the remaining dataset. Dialogue generation models trained with different degrees of data distillation manifest different levels of specificity. We then train a reinforcement learning system for selecting among this pool of generation models, to choose the best level of specificity for a given input. Compared to the original generative model trained without distillation, the proposed system is capable of generating more interesting and higher-quality responses, in addition to appropriately adjusting specificity depending on the context. Our research constitutes a specific case of a broader approach involving training multiple subsystems from a single dataset distinguished by differences in a specific property one wishes to model. We show that from such a set of subsystems, one can use reinforcement learning to build a system that tailors its output to different input contexts at test time.

##### Abstract (translated by Google)
人们在不同的情况下以不同的特殊程度说话。根据他们的知识，对话者，情绪等。}一个会话代理人应该有这个能力，知道什么时候是具体的，什么时候是一般的。我们提出一种方法，给出一个基于神经网络的会话代理这种能力。我们的方法涉及数据蒸馏和模型训练之间的交替：去除最接近最后一轮训练模型产生的反应的训练样本，然后再训练剩余数据集的模型。用不同程度的数据蒸馏训练的对话生成模型表现出不同程度的特异性。然后，我们训练一个强化学习系统，用于在这一代的模型中进行选择，以便为给定的输入选择最佳的特异性水平。与未经蒸馏训练的原始生成模型相比，所提出的系统能够产生更有趣和更高质量的响应，此外根据情况适当调整特异性。我们的研究构成了一个更广泛方法的具体案例，涉及从单个数据集中训练多个子系统，通过区分某个特定属性的差异来进行区分。我们证明，从这样一组子系统中，可以使用强化学习来构建一个系统，在测试时刻将输出定制到不同的输入上下文中。

##### URL
[https://arxiv.org/abs/1702.06703](https://arxiv.org/abs/1702.06703)

##### PDF
[https://arxiv.org/pdf/1702.06703](https://arxiv.org/pdf/1702.06703)

