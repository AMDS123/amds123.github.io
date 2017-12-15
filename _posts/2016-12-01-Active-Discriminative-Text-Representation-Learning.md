---
layout: post
title: "Active Discriminative Text Representation Learning"
date: 2016-12-01 18:53:32
categories: arXiv_CL
tags: arXiv_CL Knowledge Text_Classification Embedding CNN Represenation_Learning Classification
author: Ye Zhang, Matthew Lease, Byron C. Wallace
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new active learning (AL) method for text classification with convolutional neural networks (CNNs). In AL, one selects the instances to be manually labeled with the aim of maximizing model performance with minimal effort. Neural models capitalize on word embeddings as representations (features), tuning these to the task at hand. We argue that AL strategies for multi-layered neural models should focus on selecting instances that most affect the embedding space (i.e., induce discriminative word representations). This is in contrast to traditional AL approaches (e.g., entropy-based uncertainty sampling), which specify higher level objectives. We propose a simple approach for sentence classification that selects instances containing words whose embeddings are likely to be updated with the greatest magnitude, thereby rapidly learning discriminative, task-specific embeddings. We extend this approach to document classification by jointly considering: (1) the expected changes to the constituent word representations; and (2) the model's current overall uncertainty regarding the instance. The relative emphasis placed on these criteria is governed by a stochastic process that favors selecting instances likely to improve representations at the outset of learning, and then shifts toward general uncertainty sampling as AL progresses. Empirical results show that our method outperforms baseline AL approaches on both sentence and document classification tasks. We also show that, as expected, the method quickly learns discriminative word embeddings. To the best of our knowledge, this is the first work on AL addressing neural models for text classification.

##### Abstract (translated by Google)
我们提出了一种新的主​​动学习（AL）方法用于卷积神经网络（CNN）的文本分类。在AL中，选择要手动标记的实例，以便尽可能减少模型性能的最大化。神经模型利用单词嵌入作为表示（特征），将其调整为手边的任务。我们认为，多层神经模型的AL策略应该集中在选择最能影响嵌入空间的实例（即引发歧义词表示）。这与传统的AL方法（例如，基于熵的不确定性抽样）相反，其指定更高级别的目标。我们提出了一种简单的句子分类方法，用于选择包含可能以最大幅度更新嵌入的词的实例，从而快速地学习区分性，特定任务的嵌入。我们将这种方法扩展到文档分类中，共同考虑：（1）组成词语表示的预期变化;和（2）模型当前的整体不确定性。对这些标准的相对重视是受随机过程的支配，该过程倾向于选择可能在学习开始时改善表示的实例，然后随着AL进展转向一般的不确定性抽样。实证结果显示，我们的方法在句子和文档分类任务上均优于基线AL方法。我们还表明，如预期的那样，该方法快速学习歧视性词嵌入。据我们所知，这是AL处理文本分类神经模型的第一个工作。

##### URL
[https://arxiv.org/abs/1606.04212](https://arxiv.org/abs/1606.04212)

##### PDF
[https://arxiv.org/pdf/1606.04212](https://arxiv.org/pdf/1606.04212)

