---
layout: post
title: "Hybrid Oracle: Making Use of Ambiguity in Transition-based Chinese Dependency Parsing"
date: 2018-02-06 01:33:57
categories: arXiv_CL
tags: arXiv_CL
author: Xuancheng Ren, Xu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In the training of transition-based dependency parsers, an oracle is used to predict a transition sequence for a sentence and its gold tree. However, the transition system may exhibit ambiguity, that is, there can be multiple correct transition sequences that form the gold tree. We propose to make use of the property in the training of neural dependency parsers, and present the Hybrid Oracle. The new oracle gives all the correct transitions for a parsing state, which are used in the cross entropy loss function to provide better supervisory signal. It is also used to generate different transition sequences for a sentence to better explore the training data and improve the generalization ability of the parser. Evaluations show that the parsers trained using the hybrid oracle outperform the parsers using the traditional oracle in Chinese dependency parsing. We provide analysis from a linguistic view. The code is available at https://github.com/lancopku/nndep .

##### Abstract (translated by Google)
在基于转换的依赖分析器的训练中，使用预言器来预测句子及其黄金树的转换序列。然而，转换系统可能表现出模糊性，也就是说，可能有多个正确的转换序列组成金树。我们建议在神经依赖解析器的训练中利用这个属性，并提出Hybrid Oracle。新的预言器为解析状态提供了所有正确的转换，用于交叉熵损失函数中以提供更好的监督信号。也用于为句子生成不同的转换序列，以更好地探索训练数据，提高解析器的泛化能力。评估结果显示，使用混合式Oracle进行训练的解析器优于使用传统的中文依赖解析中的oracle的解析器。我们从语言角度提供分析。代码可在https://github.com/lancopku/nndep上找到。

##### URL
[http://arxiv.org/abs/1711.10163](http://arxiv.org/abs/1711.10163)

##### PDF
[http://arxiv.org/pdf/1711.10163](http://arxiv.org/pdf/1711.10163)

