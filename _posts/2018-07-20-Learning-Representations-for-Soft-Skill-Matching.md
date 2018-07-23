---
layout: post
title: "Learning Representations for Soft Skill Matching"
date: 2018-07-20 08:40:10
categories: arXiv_CL
tags: arXiv_CL Attention Text_Classification RNN Classification Prediction
author: Luiza Sayfullina, Eric Malmi, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
Employers actively look for talents having not only specific hard skills but also various soft skills. To analyze the soft skill demands on the job market, it is important to be able to detect soft skill phrases from job advertisements automatically. However, a naive matching of soft skill phrases can lead to false positive matches when a soft skill phrase, such as friendly, is used to describe a company, a team, or another entity, rather than a desired candidate. 
 In this paper, we propose a phrase-matching-based approach which differentiates between soft skill phrases referring to a candidate vs. something else. The disambiguation is formulated as a binary text classification problem where the prediction is made for the potential soft skill based on the context where it occurs. To inform the model about the soft skill for which the prediction is made, we develop several approaches, including soft skill masking and soft skill tagging. 
 We compare several neural network based approaches, including CNN, LSTM and Hierarchical Attention Model. The proposed tagging-based input representation using LSTM achieved the highest recall of 83.92% on the job dataset when fixing a precision to 95%.

##### Abstract (translated by Google)
雇主积极寻找不仅具有特定硬技能而且具有各种软技能的人才。为了分析就业市场上的软技能需求，能够自动检测来自招聘广告的软技能短语是很重要的。然而，当使用诸如友好的软技能短语来描述公司，团队或其他实体而不是期望的候选者时，软技能短语的天真匹配可导致假阳性匹配。
 在本文中，我们提出了一种基于短语匹配的方法，该方法区分了涉及候选人与其他人的软技能短语。消歧被表述为二元文本分类问题，其中基于其发生的上下文对潜在的软技能进行预测。为了告知模型有关预测的软技能，我们开发了几种方法，包括软技能掩蔽和软技能标记。
 我们比较了几种基于神经网络的方法，包括CNN，LSTM和分层注意模型。当将精度固定为95％时，使用LSTM建议的基于标记的输入表示在作业数据集上实现了83.92％的最高召回率。

##### URL
[http://arxiv.org/abs/1807.07741](http://arxiv.org/abs/1807.07741)

##### PDF
[http://arxiv.org/pdf/1807.07741](http://arxiv.org/pdf/1807.07741)

