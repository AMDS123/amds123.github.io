---
layout: post
title: "OpenTag: Open Attribute Value Extraction from Product Profiles"
date: 2018-06-01 19:41:07
categories: arXiv_AI
tags: arXiv_AI Attention RNN
author: Guineng Zheng, Subhabrata Mukherjee, Xin Luna Dong, Feifei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Extraction of missing attribute values is to find values describing an attribute of interest from a free text input. Most past related work on extraction of missing attribute values work with a closed world assumption with the possible set of values known beforehand, or use dictionaries of values and hand-crafted features. How can we discover new attribute values that we have never seen before? Can we do this with limited human annotation or supervision? We study this problem in the context of product catalogs that often have missing values for many attributes of interest. 
 In this work, we leverage product profile information such as titles and descriptions to discover missing values of product attributes. We develop a novel deep tagging model OpenTag for this extraction problem with the following contributions: (1) we formalize the problem as a sequence tagging task, and propose a joint model exploiting recurrent neural networks (specifically, bidirectional LSTM) to capture context and semantics, and Conditional Random Fields (CRF) to enforce tagging consistency, (2) we develop a novel attention mechanism to provide interpretable explanation for our model's decisions, (3) we propose a novel sampling strategy exploring active learning to reduce the burden of human annotation. OpenTag does not use any dictionary or hand-crafted features as in prior works. Extensive experiments in real-life datasets in different domains show that OpenTag with our active learning strategy discovers new attribute values from as few as 150 annotated samples (reduction in 3.3x amount of annotation effort) with a high F-score of 83%, outperforming state-of-the-art models.

##### Abstract (translated by Google)
提取缺少的属性值是从自由文本输入中找到描述感兴趣属性的值。过去大多数关于提取缺失属性值的相关工作都是在一个封闭的世界假设下进行的，这些假设都是事先知道可能的一组值，或者使用值和手工特征的字典。我们如何发现我们以前从未见过的新属性值？我们可以用有限的人类注释或监督来做到这一点吗？我们在产品目录的背景下研究这个问题，这些产品目录经常缺少许多感兴趣的属性值。
 在这项工作中，我们利用产品配置文件信息（如标题和描述）来发现产品属性的缺失值。我们为这个提取问题开发了一个新的深度标注模型OpenTag，其贡献如下：（1）我们将问题形式化为序列标记任务，并提出一个利用递归神经网络（特别是双向LSTM）来捕获上下文和语义的联合模型，和条件随机场（CRF）来强化标注一致性，（2）我们开发了一种新颖的注意机制，为我们模型的决策提供可解释的解释，（3）我们提出了一种新的抽样策略，探索主动学习以减轻人类注释的负担。 OpenTag不像以前的作品那样使用任何字典或手工制作的功能。在不同领域的实际数据集中进行的大量实验表明，使用我们的主动学习策略的OpenTag可以从少至150个注释样本中发现新的属性值（减少3.3倍的注释量），其F值高达83％，性能优于最先进的模型。

##### URL
[http://arxiv.org/abs/1806.01264](http://arxiv.org/abs/1806.01264)

##### PDF
[http://arxiv.org/pdf/1806.01264](http://arxiv.org/pdf/1806.01264)

