---
layout: post
title: "Filling Missing Paths: Modeling Co-occurrences of Word Pairs and Dependency Paths for Recognizing Lexical Semantic Relations"
date: 2018-09-10 15:47:37
categories: arXiv_CL
tags: arXiv_CL Relation
author: Koki Washio, Tsuneaki Kato
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing lexical semantic relations between word pairs is an important task for many applications of natural language processing. One of the mainstream approaches to this task is to exploit the lexico-syntactic paths connecting two target words, which reflect the semantic relations of word pairs. However, this method requires that the considered words co-occur in a sentence. This requirement is hardly satisfied because of Zipf's law, which states that most content words occur very rarely. In this paper, we propose novel methods with a neural model of $P(path|w_1, w_2)$ to solve this problem. Our proposed model of $P(path|w_1, w_2)$ can be learned in an unsupervised manner and can generalize the co-occurrences of word pairs and dependency paths. This model can be used to augment the path data of word pairs that do not co-occur in the corpus, and extract features capturing relational information from word pairs. Our experimental results demonstrate that our methods improve on previous neural approaches based on dependency paths and successfully solve the focused problem.

##### Abstract (translated by Google)
识别单词对之间的词汇语义关系是许多自然语言处理应用的重要任务。这项任务的主流方法之一是利用连接两个目标词的词汇 - 句法路径，这反映了词对的语义关系。然而，该方法要求所考虑的单词在句子中共同出现。由于Zipf定律很难满足这一要求，该定律指出大多数内容词很少出现。在本文中，我们提出了一种新的方法，用$ P（path | w_1，w_2）$的神经模型来解决这个问题。我们提出的$ P（path | w_1，w_2）$的模型可以以无监督的方式学习，并且可以推广单词对和依赖路径的共现。该模型可用于增加不在语料库中共同出现的单词对的路径数据，并提取从单词对中捕获关系信息的特征。我们的实验结果表明，我们的方法改进了基于依赖路径的先前神经方法并成功解决了焦点问题。

##### URL
[http://arxiv.org/abs/1809.03411](http://arxiv.org/abs/1809.03411)

##### PDF
[http://arxiv.org/pdf/1809.03411](http://arxiv.org/pdf/1809.03411)

