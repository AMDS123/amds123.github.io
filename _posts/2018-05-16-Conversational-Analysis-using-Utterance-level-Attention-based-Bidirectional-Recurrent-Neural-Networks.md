---
layout: post
title: "Conversational Analysis using Utterance-level Attention-based Bidirectional Recurrent Neural Networks"
date: 2018-05-16 10:51:56
categories: arXiv_AI
tags: arXiv_AI Attention RNN Classification Recognition
author: Chandrakant Bothe, Sven Magg, Cornelius Weber, Stefan Wermter
mathjax: true
---

* content
{:toc}

##### Abstract
Recent approaches for dialogue act recognition have shown that context from preceding utterances is important to classify the subsequent one. It was shown that the performance improves rapidly when the context is taken into account. We propose an utterance-level attention-based bidirectional recurrent neural network (Utt-Att-BiRNN) model to analyze the importance of preceding utterances to classify the current one. In our setup, the BiRNN is given the input set of current and preceding utterances. Our model outperforms previous models that use only preceding utterances as context on the used corpus. Another contribution of the article is to discover the amount of information in each utterance to classify the subsequent one and to show that context-based learning not only improves the performance but also achieves higher confidence in the classification. We use character- and word-level features to represent the utterances. The results are presented for character and word feature representations and as an ensemble model of both representations. We found that when classifying short utterances, the closest preceding utterances contributes to a higher degree.

##### Abstract (translated by Google)
最近的对话行为识别方法已经表明来自先前话语的情境对于后续话语的分类很重要。结果表明，当考虑到上下文时，性能会迅速提高。我们提出了一种基于注意的话语双向递归神经网络（Utt-Att-BiRNN）模型来分析之前话语对当前话语分类的重要性。在我们的设置中，BiRNN被赋予当前和前面话语的输入集合。我们的模型胜过以前的模型，只使用前面的话语作为使用语料库的上下文。本文的另一个贡献是发现每个话语中的信息量，以对随后的话语进行分类，并且显示基于情境的学习不仅提高了表现，而且在分类中获得了更高的置信度。我们使用字符和词级特征来表示话语。结果表示为字符和单词特征表示，并作为两个表示的集成模型。我们发现，在对短语进行分类时，最接近的前面的话语有助于提高程度。

##### URL
[http://arxiv.org/abs/1805.06242](http://arxiv.org/abs/1805.06242)

##### PDF
[http://arxiv.org/pdf/1805.06242](http://arxiv.org/pdf/1805.06242)

