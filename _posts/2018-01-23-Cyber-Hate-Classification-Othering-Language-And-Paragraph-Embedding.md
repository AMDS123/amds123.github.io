---
layout: post
title: "Cyber Hate Classification: 'Othering' Language And Paragraph Embedding"
date: 2018-01-23 11:43:54
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Detection
author: Wafa Alorainy, Pete Burnap, Han Liu, Matthew Williams
mathjax: true
---

* content
{:toc}

##### Abstract
Hateful and offensive language (also known as hate speech or cyber hate) posted and widely circulated via the World Wide Web can be considered as a key risk factor for individual and societal tension linked to regional instability. Automated Web-based hate speech detection is important for the observation and understanding trends of societal tension. In this research, we improve on existing research by proposing different data mining feature extraction methods. While previous work has involved using lexicons, bags-of-words or probabilistic parsing approach (e.g. using Typed Dependencies), they all suffer from a similar issue which is that hate speech can often be subtle and indirect, and depending on individual words or phrases can lead to a significant number of false negatives. This problem motivated us to conduct new experiments to identify subtle language use, such as references to immigration or job prosperity in a hateful context. We propose a novel 'Othering Lexicon' to identify these subtleties and we incorporate our lexicon with embedding learning for feature extraction and subsequent classification using a neural network approach. Our method first explores the context around othering terms in a corpus, and identifies context patterns that are relevant to the othering context. These patterns are used along with the othering pronoun and hate speech terms to build our 'Othering Lexicon'. Embedding algorithm has the superior characteristic that the similar words have a closer distance, which is helpful to train our classifier on the negative and positive classes. For validation, several experiments were conducted on different types of hate speech, namely religion, disability, race and sexual orientation, with F-measure scores for classifying hateful instances obtained through applying our model of 0.93, 0.95, 0.97 and 0.92 respective.

##### Abstract (translated by Google)
通过万维网张贴并广泛传播的仇恨和攻击性语言（也称为仇恨言论或网络仇恨）可被视为与地区不稳定有关的个人和社会紧张的关键风险因素。自动化的基于网络的仇恨言语检测对于观察和理解社会紧张的趋势非常重要。在这项研究中，我们通过提出不同的数据挖掘特征提取方法来改进现有的研究。尽管以前的工作涉及使用词汇，词汇或概率分析方法（例如使用类型化依赖），但他们都遭受类似的问题，即仇恨言论通常是微妙的和间接的，并取决于单个词或短语可能会导致大量的错误否定。这个问题促使我们进行新的实验，以确定微妙的语言使用，如在一个可恶的背景下提到移民或工作繁荣。我们提出了一个新颖的“其他词典”来识别这些细微差别，我们把我们的词典与嵌入学习结合起来进行特征提取和随后的分类，使用神经网络方法。我们的方法首先探讨围绕语料库中其他术语的上下文，并确定与其他语境相关的语境模式。这些模式与其他代词和仇恨言语术语一起使用来构建我们的“其他词典”。嵌入算法具有类似词汇距离较近的优越特性，有利于在正负类别上训练分类器。为了进行验证，我们对不同类型的仇恨言论进行了多次实验，这些仇恨言论包括宗教，残疾，种族和性取向，以及通过应用我们的0.93,0.95,0.97和0.92模型获得的用于分类仇恨实例的F-measure分数。

##### URL
[http://arxiv.org/abs/1801.07495](http://arxiv.org/abs/1801.07495)

##### PDF
[http://arxiv.org/pdf/1801.07495](http://arxiv.org/pdf/1801.07495)

