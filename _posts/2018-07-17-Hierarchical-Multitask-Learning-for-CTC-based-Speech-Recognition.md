---
layout: post
title: "Hierarchical Multitask Learning for CTC-based Speech Recognition"
date: 2018-07-17 06:05:00
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Classification Relation Recognition
author: Kalpesh Krishna, Shubham Toshniwal, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work has shown that neural encoder-decoder speech recognition can be improved with hierarchical multitask learning, where auxiliary tasks are added at intermediate layers of a deep encoder. We explore the effect of hierarchical multitask learning in the context of connectionist temporal classification (CTC)-based speech recognition, and investigate several aspects of this approach. Consistent with previous work, we observe performance improvements on telephone conversational speech recognition (specifically the Eval2000 test sets) when training a subword-level CTC model with an auxiliary phone loss at an intermediate layer. We analyze the effects of a number of experimental variables (like interpolation constant and position of the auxiliary loss function), performance in lower-resource settings, and the relationship between pretraining and multitask learning. We observe that the hierarchical multitask approach improves over standard multitask training in our higher-data experiments, while in the low-resource settings standard multitask training works well. The best results are obtained by combining hierarchical multitask learning and pretraining, which improves word error rates by 3.4% absolute on the Eval2000 test sets.

##### Abstract (translated by Google)
先前的工作已经表明，神经编码器 - 解码器语音识别可以通过分层多任务学习来改进，其中辅助任务被添加在深编码器的中间层。我们在基于联系主义时间分类（CTC）的语音识别的背景下探讨了分层多任务学习的效果，并研究了该方法的几个方面。与之前的工作一致，我们观察到在中间层辅助电话丢失的情况下训练具有辅助电话丢失的子字级CTC模型时电话会话语音识别（特别是Eval2000测试集）的性能改进。我们分析了许多实验变量的影响（如插值常数和辅助损失函数的位置），资源较低的设置中的性能，以及预训练和多任务学习之间的关系。我们观察到，在我们的高数据实验中，分层多任务方法改进了标准多任务训练，而在资源较低的情况下，标准多任务训练效果很好。通过组合分层多任务学习和预训练获得最佳结果，这在Eval2000测试集上将字错误率提高了3.4％绝对值。

##### URL
[http://arxiv.org/abs/1807.06234](http://arxiv.org/abs/1807.06234)

##### PDF
[http://arxiv.org/pdf/1807.06234](http://arxiv.org/pdf/1807.06234)

