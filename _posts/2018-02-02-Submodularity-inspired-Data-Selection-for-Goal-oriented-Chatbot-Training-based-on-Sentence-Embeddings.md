---
layout: post
title: "Submodularity-inspired Data Selection for Goal-oriented Chatbot Training based on Sentence Embeddings"
date: 2018-02-02 16:26:39
categories: arXiv_CL
tags: arXiv_CL QA Embedding
author: Mladen Dimovski, Vladimir Ilievski, Claudiu Musat, Andreea Hossmann, Michael Baeriswyl
mathjax: true
---

* content
{:toc}

##### Abstract
Goal-oriented (GO) dialogue systems rely on an initial natural language understanding (NLU) module to determine the user's intention and parameters thereof - also known as slots. Since the systems, also known as bots, help the users with solving problems in relatively narrow domains, they require training data within those domains. This leads to significant data availability issues that inhibit the development of successful bots. To alleviate this problem, we propose a technique of data selection in the low-data regime that allows training with significantly fewer labeled sentences, thus smaller labelling costs. We create a submodularity-inspired data ranking function, the ratio penalty marginal gain, to select data points to label based solely on the information extracted from the textual embedding space. We show that the distances in the embedding space are a viable source of information for data selection. This method outperforms several known active learning techniques, without using the label information. This allows for cost-efficient training of NLU units for goal-oriented bots. Moreover, our proposed selection technique does not need the retraining of the model in between the selection steps, making it time-efficient as well.

##### Abstract (translated by Google)
目标导向（GO）对话系统依赖于初始自然语言理解（NLU）模块来确定用户的意图和参数 - 也被称为插槽。由于系统（也称为漫游器）帮助用户解决相对狭窄的领域中的问题，因此需要这些领域内的训练数据。这导致显着的数据可用性问题，抑制成功的机器人的发展。为了缓解这个问题，我们提出了一种在低数据情况下进行数据选择的技术，允许使用明显较少的标签句子进行训练，从而减少标签成本。我们创建一个子模块性灵感的数据排序函数，比率惩罚边际收益，选择数据点来标签的基础上，从文本嵌入空间提取的信息。我们表明，嵌入空间中的距离是数据选择的一个可行的信息来源。这种方法胜过几种已知的主动学习技术，而不使用标签信息。这样可以为面向目标的机器人提供经济高效的NLU单元培训。而且，我们提出的选择技术不需要在选择步骤之间对模型进行再训练，使得它也是有效的。

##### URL
[https://arxiv.org/abs/1802.00757](https://arxiv.org/abs/1802.00757)

##### PDF
[https://arxiv.org/pdf/1802.00757](https://arxiv.org/pdf/1802.00757)

