---
layout: post
title: "Finding Good Representations of Emotions for Text Classification"
date: 2018-08-22 06:07:24
categories: arXiv_CL
tags: arXiv_CL Sentiment Weakly_Supervised Text_Classification CNN Classification Language_Model Detection
author: Ji Ho Park
mathjax: true
---

* content
{:toc}

##### Abstract
It is important for machines to interpret human emotions properly for better human-machine communications, as emotion is an essential part of human-to-human communications. One aspect of emotion is reflected in the language we use. How to represent emotions in texts is a challenge in natural language processing (NLP). Although continuous vector representations like word2vec have become the new norm for NLP problems, their limitations are that they do not take emotions into consideration and can unintentionally contain bias toward certain identities like different genders. 
 This thesis focuses on improving existing representations in both word and sentence levels by explicitly taking emotions inside text and model bias into account in their training process. Our improved representations can help to build more robust machine learning models for affect-related text classification like sentiment/emotion analysis and abusive language detection. 
 We first propose representations called emotional word vectors (EVEC), which is learned from a convolutional neural network model with an emotion-labeled corpus, which is constructed using hashtags. Secondly, we extend to learning sentence-level representations with a huge corpus of texts with the pseudo task of recognizing emojis. Our results show that, with the representations trained from millions of tweets with weakly supervised labels such as hashtags and emojis, we can solve sentiment/emotion analysis tasks more effectively. 
 Lastly, as examples of model bias in representations of existing approaches, we explore a specific problem of automatic detection of abusive language. We address the issue of gender bias in various neural network models by conducting experiments to measure and reduce those biases in the representations in order to build more robust classification models.

##### Abstract (translated by Google)
由于情感是人与人之间通信的重要组成部分，因此机器能够恰当地解释人类情感以获得更好的人机交流非常重要。情绪的一个方面反映在我们使用的语言中。如何在文本中表达情感是自然语言处理（NLP）中的一个挑战。尽管像word2vec这样的连续向量表示已成为NLP问题的新规范，但它们的局限性在于它们不考虑情绪，并且可能无意中包含对不同性别等某些身份的偏见。
 本文着重于通过在训练过程中明确考虑文本内部的情感和模型偏差来改进单词和句子级别的现有表示。我们改进的表示可以帮助构建更强大的机器学习模型，用于与情感相关的文本分类，如情绪/情绪分析和滥用语言检测。
 我们首先提出称为情绪词向量（EVEC）的表示，其是从具有情感标记语料库的卷积神经网络模型中学习的，其使用主题标签构建。其次，我们扩展到学习句子级表示，其中包含大量文本语料库，其中包含识别表情符号的伪任务。我们的结果表明，通过数百万条带有弱监督标签（如标签和表情符号）的推文进行训练，我们可以更有效地解决情绪/情绪分析任务。
 最后，作为现有方法表示中模型偏差的例子，我们探讨了滥用语言自动检测的具体问题。我们通过进行实验来测量和减少表示中的偏差，以便建立更强大的分类模型，从而解决各种神经网络模型中的性别偏差问题。

##### URL
[http://arxiv.org/abs/1808.07235](http://arxiv.org/abs/1808.07235)

##### PDF
[http://arxiv.org/pdf/1808.07235](http://arxiv.org/pdf/1808.07235)

