---
layout: post
title: "Globally Normalized Reader"
date: 2017-09-08 18:27:50
categories: arXiv_CL
tags: arXiv_CL Knowledge QA Attention
author: Jonathan Raiman, John Miller
mathjax: true
---

* content
{:toc}

##### Abstract
Rapid progress has been made towards question answering (QA) systems that can extract answers from text. Existing neural approaches make use of expensive bi-directional attention mechanisms or score all possible answer spans, limiting scalability. We propose instead to cast extractive QA as an iterative search problem: select the answer's sentence, start word, and end word. This representation reduces the space of each search step and allows computation to be conditionally allocated to promising search paths. We show that globally normalizing the decision process and back-propagating through beam search makes this representation viable and learning efficient. We empirically demonstrate the benefits of this approach using our model, Globally Normalized Reader (GNR), which achieves the second highest single model performance on the Stanford Question Answering Dataset (68.4 EM, 76.21 F1 dev) and is 24.7x faster than bi-attention-flow. We also introduce a data-augmentation method to produce semantically valid examples by aligning named entities to a knowledge base and swapping them with new entities of the same type. This method improves the performance of all models considered in this work and is of independent interest for a variety of NLP tasks.

##### Abstract (translated by Google)
对于可以从文本中提取答案的问答系统（QA）已经取得了迅速的进展。现有的神经方法利用昂贵的双向关注机制或者评分所有可能的答案跨度，限制了可伸缩性。我们建议将抽取的QA作为迭代搜索问题：选择答案的句子，开始单词和结束单词。这种表示减少了每个搜索步骤的空间，并允许将计算有条件地分配给有前途的搜索路径。我们表明，全球正常化的决策过程和反向传播通过波束搜索使这种表示可行和学习效率。我们使用我们的模型，全球标准化阅读器（GNR），在斯坦福问答数据集（68.4 EM，76.21 F1 dev）上获得了第二高的单模型性能，比双注意快了24.7倍-流。我们还引入了一种数据增强方法，通过将命名实体与知识库对齐，并将它们与相同类型的新实体进行交换，从而生成语义上有效的示例。这种方法提高了本文所考虑的所有模型的性能，并且对于各种NLP任务具有独立的兴趣。

##### URL
[https://arxiv.org/abs/1709.02828](https://arxiv.org/abs/1709.02828)

##### PDF
[https://arxiv.org/pdf/1709.02828](https://arxiv.org/pdf/1709.02828)

