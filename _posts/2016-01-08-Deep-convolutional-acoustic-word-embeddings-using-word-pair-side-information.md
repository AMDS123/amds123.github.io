---
layout: post
title: "Deep convolutional acoustic word embeddings using word-pair side information"
date: 2016-01-08 14:54:44
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding CNN Recognition
author: Herman Kamper, Weiran Wang, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have been revisiting whole words as the basic modelling unit in speech recognition and query applications, instead of phonetic units. Such whole-word segmental systems rely on a function that maps a variable-length speech segment to a vector in a fixed-dimensional space; the resulting acoustic word embeddings need to allow for accurate discrimination between different word types, directly in the embedding space. We compare several old and new approaches in a word discrimination task. Our best approach uses side information in the form of known word pairs to train a Siamese convolutional neural network (CNN): a pair of tied networks that take two speech segments as input and produce their embeddings, trained with a hinge loss that separates same-word pairs and different-word pairs by some margin. A word classifier CNN performs similarly, but requires much stronger supervision. Both types of CNNs yield large improvements over the best previously published results on the word discrimination task.

##### Abstract (translated by Google)
最近的研究已经将整个单词作为语音识别和查询应用中的基本建模单元，而不是语音单元。这样的全字分段系统依赖于将固定维空间中的可变长度的语音片段映射到矢量的功能;得到的声学词汇嵌入需要允许直接在嵌入空间中的不同词类型之间的准确区分。我们比较几个新旧方法在一个字歧视任务。我们最好的方法是以已知单词对的形式使用边信息来训练一个连体卷积神经网络（CNN）：一对绑定网络，以两个语音段作为输入并产生嵌入，用铰链损失进行训练，字对和不同的字对有一定的差距。单词分类器CNN表现相似，但需要更强的监督。这两种类型的有线电视新闻网（CNN）都比之前发表的有关单词歧视任务的最佳结果有很大的改进

##### URL
[https://arxiv.org/abs/1510.01032](https://arxiv.org/abs/1510.01032)

##### PDF
[https://arxiv.org/pdf/1510.01032](https://arxiv.org/pdf/1510.01032)

