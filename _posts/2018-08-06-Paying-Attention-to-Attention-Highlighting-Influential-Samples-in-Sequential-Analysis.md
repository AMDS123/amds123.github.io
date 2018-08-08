---
layout: post
title: "Paying Attention to Attention: Highlighting Influential Samples in Sequential Analysis"
date: 2018-08-06 21:05:55
categories: arXiv_CL
tags: arXiv_CL Review Attention Classification Prediction
author: Cynthia Freeman, Jonathan Merriman, Abhinav Aggarwal, Ian Beaver, Abdullah Mueen
mathjax: true
---

* content
{:toc}

##### Abstract
In (Yang et al. 2016), a hierarchical attention network (HAN) is created for document classification. The attention layer can be used to visualize text influential in classifying the document, thereby explaining the model's prediction. We successfully applied HAN to a sequential analysis task in the form of real-time monitoring of turn taking in conversations. However, we discovered instances where the attention weights were uniform at the stopping point (indicating all turns were equivalently influential to the classifier), preventing meaningful visualization for real-time human review or classifier improvement. We observed that attention weights for turns fluctuated as the conversations progressed, indicating turns had varying influence based on conversation state. Leveraging this observation, we develop a method to create more informative real-time visuals (as confirmed by human reviewers) in cases of uniform attention weights using the changes in turn importance as a conversation progresses over time.

##### Abstract (translated by Google)
在（Yang等人，2016）中，创建了用于文档分类的分层关注网络（HAN）。关注层可用于可视化在分类文档时有影响的文本，从而解释模型的预测。我们成功地将HAN应用于顺序分析任务，其形式是实时监控对话中的转向。然而，我们发现了在停止点处注意权重均匀的情况（表明所有转弯对分类器具有相同的影响），阻碍了实时人工审查或分类器改进的有意义可视化。我们观察到随着对话的进行，转弯的注意力量会发生波动，表明转弯对话的状态有不同的影响。利用这一观察结果，我们开发了一种方法，可以在均匀注意力量的情况下创建更具信息性的实时视觉效果（由人类评论者确认），随着对话的进展，随着时间的推移，使用轮流重要性的变化。

##### URL
[http://arxiv.org/abs/1808.02113](http://arxiv.org/abs/1808.02113)

##### PDF
[http://arxiv.org/pdf/1808.02113](http://arxiv.org/pdf/1808.02113)

