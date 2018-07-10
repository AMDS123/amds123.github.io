---
layout: post
title: "Submodularity-Inspired Data Selection for Goal-Oriented Chatbot Training Based on Sentence Embeddings"
date: 2018-07-08 16:27:47
categories: arXiv_CL
tags: arXiv_CL QA Embedding
author: Mladen Dimovski, Claudiu Musat, Vladimir Ilievski, Andreea Hossmann, Michael Baeriswyl
mathjax: true
---

* content
{:toc}

##### Abstract
Spoken language understanding (SLU) systems, such as goal-oriented chatbots or personal assistants, rely on an initial natural language understanding (NLU) module to determine the intent and to extract the relevant information from the user queries they take as input. SLU systems usually help users to solve problems in relatively narrow domains and require a large amount of in-domain training data. This leads to significant data availability issues that inhibit the development of successful systems. To alleviate this problem, we propose a technique of data selection in the low-data regime that enables us to train with fewer labeled sentences, thus smaller labelling costs. 
 We propose a submodularity-inspired data ranking function, the ratio-penalty marginal gain, for selecting data points to label based only on the information extracted from the textual embedding space. We show that the distances in the embedding space are a viable source of information that can be used for data selection. Our method outperforms two known active learning techniques and enables cost-efficient training of the NLU unit. Moreover, our proposed selection technique does not need the model to be retrained in between the selection steps, making it time efficient as well.

##### Abstract (translated by Google)
口语理解（SLU）系统，例如面向目标的聊天机器人或个人助理，依赖于初始自然语言理解（NLU）模块来确定意图并从他们作为输入的用户查询中提取相关信息。 SLU系统通常可以帮助用户解决相对狭窄的域中的问题，并且需要大量的域内训练数据。这导致严重的数据可用性问题，这些问题阻碍了成功系统的开发。为了缓解这个问题，我们提出了一种在低数据体系中进行数据选择的技术，使我们能够用较少的标记句子进行训练，从而降低标签成本。
 我们提出了一种子模块启发的数据排序函数，比率 - 惩罚边际增益，用于仅根据从文本嵌入空间提取的信息选择要标记的数据点。我们证明嵌入空间中的距离是可用于数据选择的可行信息源。我们的方法优于两种已知的主动学习技术，可以实现NLU单元的低成本培训。此外，我们提出的选择技术不需要在选择步骤之间重新训练模型，使其也具有时间效率。

##### URL
[http://arxiv.org/abs/1802.00757](http://arxiv.org/abs/1802.00757)

##### PDF
[http://arxiv.org/pdf/1802.00757](http://arxiv.org/pdf/1802.00757)

