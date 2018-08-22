---
layout: post
title: "Semi-Supervised Learning for Neural Keyphrase Generation"
date: 2018-08-21 05:38:32
categories: arXiv_CL
tags: arXiv_CL
author: Hai Ye, Lu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of generating keyphrases that summarize the key points for a given document. While sequence-to-sequence (seq2seq) models have achieved remarkable performance on this task (Meng et al., 2017), model training often relies on large amounts of labeled data, which is only applicable to resource-rich domains. In this paper, we propose semi-supervised keyphrase generation methods by leveraging both labeled data and large-scale unlabeled samples for learning. Two strategies are proposed. First, unlabeled documents are first tagged with synthetic keyphrases obtained from unsupervised keyphrase extraction methods or a selflearning algorithm, and then combined with labeled samples for training. Furthermore, we investigate a multi-task learning framework to jointly learn to generate keyphrases as well as the titles of the articles. Experimental results show that our semi-supervised learning-based methods outperform a state-of-the-art model trained with labeled data only.

##### Abstract (translated by Google)
我们研究生成关键短语的问题，该关键短语总结了给定文档的关键点。虽然序列到序列（seq2seq）模型在此任务上取得了显着的性能（Meng等，2017），但模型训练通常依赖于大量标记数据，这仅适用于资源丰富的域。在本文中，我们通过利用标记数据和大规模未标记样本进行学习来提出半监督密钥短语生成方法。提出了两种策略。首先，首先用从无监督的关键短语提取方法或自学习算法获得的合成关键短语来标记未标记的文档，然后将其与标记的样本组合用于训练。此外，我们研究了一个多任务学习框架，共同学习生成关键短语以及文章的标题。实验结果表明，我们的半监督学习方法优于仅使用标记数据训练的最先进模型。

##### URL
[http://arxiv.org/abs/1808.06773](http://arxiv.org/abs/1808.06773)

##### PDF
[http://arxiv.org/pdf/1808.06773](http://arxiv.org/pdf/1808.06773)

