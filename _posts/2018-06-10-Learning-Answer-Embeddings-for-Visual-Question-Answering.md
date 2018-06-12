---
layout: post
title: "Learning Answer Embeddings for Visual Question Answering"
date: 2018-06-10 21:01:24
categories: arXiv_CV
tags: arXiv_CV QA Embedding Transfer_Learning Optimization Classification Relation VQA
author: Hexiang Hu, Wei-Lun Chao, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel probabilistic model for visual question answering (Visual QA). The key idea is to infer two sets of embeddings: one for the image and the question jointly and the other for the answers. The learning objective is to learn the best parameterization of those embeddings such that the correct answer has higher likelihood among all possible answers. In contrast to several existing approaches of treating Visual QA as multi-way classification, the proposed approach takes the semantic relationships (as characterized by the embeddings) among answers into consideration, instead of viewing them as independent ordinal numbers. Thus, the learned embedded function can be used to embed unseen answers (in the training dataset). These properties make the approach particularly appealing for transfer learning for open-ended Visual QA, where the source dataset on which the model is learned has limited overlapping with the target dataset in the space of answers. We have also developed large-scale optimization techniques for applying the model to datasets with a large number of answers, where the challenge is to properly normalize the proposed probabilistic models. We validate our approach on several Visual QA datasets and investigate its utility for transferring models across datasets. The empirical results have shown that the approach performs well not only on in-domain learning but also on transfer learning.

##### Abstract (translated by Google)
我们提出了一种新颖的视觉问答概率模型（Visual QA）。关键的想法是推断两组嵌入：一个是图像和问题联合，另一个是答案。学习目标是学习这些嵌入的最佳参数化，以便在所有可能的答案中正确的答案有更高的可能性。与将视觉QA视为多路分类的几种现有方法相比，所提出的方法考虑了答案中的语义关系（如嵌入所表征的），而不是将其视为独立的序数。因此，学习的嵌入函数可以用来嵌入看不见的答案（在训练数据集中）。这些性质使得这种方法对于开放式视觉QA的转移学习特别有吸引力，其中模型学习的源数据集与答案空间中的目标数据集重叠有限。我们还开发了大规模优化技术，用于将模型应用于具有大量答案的数据集，其挑战在于对建议的概率模型进行适当归一化。我们在几个Visual QA数据集上验证了我们的方法，并研究了它在数据集间传输模型的实用性。实证结果表明，该方法不仅在域内学习方面表现良好，而且在转移学习方面表现良好。

##### URL
[http://arxiv.org/abs/1806.03724](http://arxiv.org/abs/1806.03724)

##### PDF
[http://arxiv.org/pdf/1806.03724](http://arxiv.org/pdf/1806.03724)

