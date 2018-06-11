---
layout: post
title: "A Simple Method for Commonsense Reasoning"
date: 2018-06-07 18:13:08
categories: arXiv_AI
tags: arXiv_AI Knowledge RNN Deep_Learning Language_Model
author: Trieu H. Trinh, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Commonsense reasoning is a long-standing challenge for deep learning. For example, it is difficult to use neural networks to tackle the Winograd Schema dataset~\cite{levesque2011winograd}. In this paper, we present a simple method for commonsense reasoning with neural networks, using unsupervised learning. Key to our method is the use of language models, trained on a massive amount of unlabled data, to score multiple choice questions posed by commonsense reasoning tests. On both Pronoun Disambiguation and Winograd Schema challenges, our models outperform previous state-of-the-art methods by a large margin, without using expensive annotated knowledge bases or hand-engineered features. We train an array of large RNN language models that operate at word or character level on LM-1-Billion, CommonCrawl, SQuAD, Gutenberg Books, and a customized corpus for this task and show that diversity of training data plays an important role in test performance. Further analysis also shows that our system successfully discovers important features of the context that decide the correct answer, indicating a good grasp of commonsense knowledge.

##### Abstract (translated by Google)
常识推理是深度学习的长期挑战。例如，使用神经网络很难处理Winograd Schema数据集〜\ cite {levesque2011winograd}。在本文中，我们提出了一种使用无监督学习的神经网络常识推理的简单方法。我们方法的关键是使用训练了大量非标记数据的语言模型对常识推理测试提出的多项选择问题进行评分。在代词消歧和Winograd模式挑战上，我们的模型大大优于先前的最先进的方法，而不需要使用昂贵的注释知识库或手工设计特征。我们训练一系列在LM-1-Billion，CommonCrawl，SQuAD，Gutenberg Books以及用于此任务的定制语料库上运行的大型RNN语言模型，并显示培训数据的多样性在测试中扮演着重要角色性能。进一步分析还表明，我们的系统成功发现了决定正确答案的上下文的重要特征，表明了对常识性知识的良好把握。

##### URL
[http://arxiv.org/abs/1806.02847](http://arxiv.org/abs/1806.02847)

##### PDF
[http://arxiv.org/pdf/1806.02847](http://arxiv.org/pdf/1806.02847)

