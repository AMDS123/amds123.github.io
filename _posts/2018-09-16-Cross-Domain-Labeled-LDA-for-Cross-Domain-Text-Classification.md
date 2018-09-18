---
layout: post
title: "Cross-Domain Labeled LDA for Cross-Domain Text Classification"
date: 2018-09-16 06:02:37
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification Quantitative Detection
author: Baoyu Jing, Chenwei Lu, Deqing Wang, Fuzhen Zhuang, Cheng Niu
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-domain text classification aims at building a classifier for a target domain which leverages data from both source and target domain. One promising idea is to minimize the feature distribution differences of the two domains. Most existing studies explicitly minimize such differences by an exact alignment mechanism (aligning features by one-to-one feature alignment, projection matrix etc.). Such exact alignment, however, will restrict models' learning ability and will further impair models' performance on classification tasks when the semantic distributions of different domains are very different. To address this problem, we propose a novel group alignment which aligns the semantics at group level. In addition, to help the model learn better semantic groups and semantics within these groups, we also propose a partial supervision for model's learning in source domain. To this end, we embed the group alignment and a partial supervision into a cross-domain topic model, and propose a Cross-Domain Labeled LDA (CDL-LDA). On the standard 20Newsgroup and Reuters dataset, extensive quantitative (classification, perplexity etc.) and qualitative (topic detection) experiments are conducted to show the effectiveness of the proposed group alignment and partial supervision.

##### Abstract (translated by Google)
跨域文本分类旨在为目标域构建分类器，该分类器利用来自源域和目标域的数据。一个有希望的想法是最小化两个域的特征分布差异。大多数现有研究通过精确对齐机制（通过一对一特征对齐，投影矩阵等对齐特征）明确地最小化这种差异。然而，这种精确对齐将限制模型的学习能力，并且当不同域的语义分布非常不同时，将进一步损害模型在分类任务上的表现。为了解决这个问题，我们提出了一种新的组对齐方式，它在组级别上对齐语义。此外，为了帮助模型在这些组中学习更好的语义组和语义，我们还提出了对源域中模型学习的部分监督。为此，我们将组对齐和部分监督嵌入到跨域主题模型中，并提出跨域标记LDA（CDL-LDA）。在标准的20Newsgroup和Reuters数据集上，进行了广泛的定量（分类，困惑等）和定性（主题检测）实验，以显示提议的组对齐和部分监督的有效性。

##### URL
[http://arxiv.org/abs/1809.05820](http://arxiv.org/abs/1809.05820)

##### PDF
[http://arxiv.org/pdf/1809.05820](http://arxiv.org/pdf/1809.05820)

