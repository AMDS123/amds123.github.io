---
layout: post
title: "Effective Use of Bidirectional Language Modeling for Transfer Learning in Biomedical Named Entity Recognition"
date: 2018-08-15 03:31:30
categories: arXiv_CL
tags: arXiv_CL Attention Transfer_Learning Deep_Learning Language_Model Recognition
author: Devendra Singh Sachan, Pengtao Xie, Mrinmaya Sachan, Eric P Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Biomedical named entity recognition (NER) is a fundamental task in text mining of medical documents and has many applications. Deep learning based approaches to this task have been gaining increasing attention in recent years as their parameters can be learned end-to-end without the need for hand-engineered features. However, these approaches rely on high-quality labeled data, which is expensive to obtain. To address this issue, we investigate how to use unlabeled text data to improve the performance of NER models. Specifically, we train a bidirectional language model (BiLM) on unlabeled data and transfer its weights to "pretrain" an NER model with the same architecture as the BiLM, which results in a better parameter initialization of the NER model. We evaluate our approach on four benchmark datasets for biomedical NER and show that it leads to a substantial improvement in the F1 scores compared with the state-of-the-art approaches. We also show that BiLM weight transfer leads to a faster model training and the pretrained model requires fewer training examples to achieve a particular F1 score.

##### Abstract (translated by Google)
生物医学命名实体识别（NER）是医学文献文本挖掘中的基本任务，具有许多应用。近年来，基于深度学习的方法越来越受到关注，因为它们的参数可以在不需要手工设计功能的情况下端到端地学习。然而，这些方法依赖于高质量的标记数据，这些数据很难获得。为解决此问题，我们研究了如何使用未标记的文本数据来提高NER模型的性能。具体而言，我们在未标记数据上训练双向语言模型（BiLM）并将其权重转移到“预训练”NER模型，其具有与BiLM相同的体系结构，这导致NER模型的更好的参数初始化。我们在生物医学NER的四个基准数据集上评估我们的方法，并表明与最先进的方法相比，它导致F1得分的显着改善。我们还表明BiLM重量转移导致更快的模型训练，并且预训练模型需要更少的训练样例来实现特定的F1分数。

##### URL
[http://arxiv.org/abs/1711.07908](http://arxiv.org/abs/1711.07908)

##### PDF
[http://arxiv.org/pdf/1711.07908](http://arxiv.org/pdf/1711.07908)

