---
layout: post
title: "An Automatic Machine Translation Evaluation Metric Based on Dependency Parsing Model"
date: 2016-11-04 14:13:04
categories: arXiv_CL
tags: arXiv_CL
author: Hui Yu, Xiaofeng Wu, Wenbin Jiang, Qun Liu, ShouXun Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the syntax-based metrics obtain the similarity by comparing the sub-structures extracted from the trees of hypothesis and reference. These sub-structures are defined by human and can't express all the information in the trees because of the limited length of sub-structures. In addition, the overlapped parts between these sub-structures are computed repeatedly. To avoid these problems, we propose a novel automatic evaluation metric based on dependency parsing model, with no need to define sub-structures by human. First, we train a dependency parsing model by the reference dependency tree. Then we generate the hypothesis dependency tree and the corresponding probability by the dependency parsing model. The quality of the hypothesis can be judged by this probability. In order to obtain the lexicon similarity, we also introduce the unigram F-score to the new metric. Experiment results show that the new metric gets the state-of-the-art performance on system level, and is comparable with METEOR on sentence level.

##### Abstract (translated by Google)
大多数基于语法的度量通过比较从假设和参考树中提取的子结构来获得相似度。这些子结构是由人定义的，由于子结构的长度有限，不能在树上表示所有的信息。另外，重复计算这些子结构之间的重叠部分。为了避免这些问题，本文提出了一种基于依赖关系解析模型的自动评估度量方法，不需要人工定义子结构。首先，我们通过引用依赖树来训练依赖关系解析模型。然后我们通过依赖分析模型生成假设依赖树和相应的概率。假设的质量可以通过这个概率来判断。为了获得词典的相似度，我们还引入了新的度量的单调F-分数。实验结果表明，新的度量在系统层次上得到了最新的性能，并且与句子层面的METEOR相当。

##### URL
[https://arxiv.org/abs/1508.01996](https://arxiv.org/abs/1508.01996)

##### PDF
[https://arxiv.org/pdf/1508.01996](https://arxiv.org/pdf/1508.01996)

