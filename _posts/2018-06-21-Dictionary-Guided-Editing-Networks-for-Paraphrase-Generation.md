---
layout: post
title: "Dictionary-Guided Editing Networks for Paraphrase Generation"
date: 2018-06-21 06:21:14
categories: arXiv_CL
tags: arXiv_CL Attention
author: Shaohan Huang, Yu Wu, Furu Wei, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
An intuitive way for a human to write paraphrase sentences is to replace words or phrases in the original sentence with their corresponding synonyms and make necessary changes to ensure the new sentences are fluent and grammatically correct. We propose a novel approach to modeling the process with dictionary-guided editing networks which effectively conduct rewriting on the source sentence to generate paraphrase sentences. It jointly learns the selection of the appropriate word level and phrase level paraphrase pairs in the context of the original sentence from an off-the-shelf dictionary as well as the generation of fluent natural language sentences. Specifically, the system retrieves a set of word level and phrase level araphrased pairs derived from the Paraphrase Database (PPDB) for the original sentence, which is used to guide the decision of which the words might be deleted or inserted with the soft attention mechanism under the sequence-to-sequence framework. We conduct experiments on two benchmark datasets for paraphrase generation, namely the MSCOCO and Quora dataset. The evaluation results demonstrate that our dictionary-guided editing networks outperforms the baseline methods.

##### Abstract (translated by Google)
人类写出释义句的直观方式是用原来的句子中的单词或短语替换为相应的同义词，并进行必要的修改，以确保新句子的流利性和语法正确性。我们提出了一种新颖的方法，用字典引导的编辑网络来建模该过程，从而有效地对源句子进行重写以生成释义句子。它共同学习从现成的字典中选择适当的单词级别和短语级别的复述对，以及生成流利的自然语言句子。具体来说，系统从原始句子中检索从解释数据库（PPDB）导出的一组词语级和短语级语法对，其被用来指导可以使用软关注机制来删除或插入单词的决定序列到序列框架。我们针对释义生成的两个基准数据集进行实验，即MSCOCO和Quora数据集。评估结果表明，我们的字典指导编辑网络优于基准方法。

##### URL
[http://arxiv.org/abs/1806.08077](http://arxiv.org/abs/1806.08077)

##### PDF
[http://arxiv.org/pdf/1806.08077](http://arxiv.org/pdf/1806.08077)

