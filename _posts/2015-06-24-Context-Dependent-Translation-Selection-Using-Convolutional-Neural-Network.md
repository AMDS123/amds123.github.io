---
layout: post
title: "Context-Dependent Translation Selection Using Convolutional Neural Network"
date: 2015-06-24 01:07:40
categories: arXiv_CL
tags: arXiv_CL CNN
author: Zhaopeng Tu, Baotian Hu, Zhengdong Lu, Hang Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for translation selection in statistical machine translation, in which a convolutional neural network is employed to judge the similarity between a phrase pair in two languages. The specifically designed convolutional architecture encodes not only the semantic similarity of the translation pair, but also the context containing the phrase in the source language. Therefore, our approach is able to capture context-dependent semantic similarities of translation pairs. We adopt a curriculum learning strategy to train the model: we classify the training examples into easy, medium, and difficult categories, and gradually build the ability of representing phrase and sentence level context by using training examples from easy to difficult. Experimental results show that our approach significantly outperforms the baseline system by up to 1.4 BLEU points.

##### Abstract (translated by Google)
我们提出了一种统计机器翻译中翻译选择的新方法，利用卷积神经网络来判断两种语言中短语对之间的相似度。专门设计的卷积体系结构不仅对翻译对的语义相似性进行编码，而且对源语言中包含该短语的上下文进行编码。因此，我们的方法能够捕捉翻译对的语境相关语义相似性。采用课程学习策略对模型进行训练：将训练样本分为易，中，难三类，逐步建立词汇和句子的语境表达能力，用容易到难的训练样例。实验结果表明，我们的方法明显优于基准系统高达1.4 BLEU点。

##### URL
[https://arxiv.org/abs/1503.02357](https://arxiv.org/abs/1503.02357)

##### PDF
[https://arxiv.org/pdf/1503.02357](https://arxiv.org/pdf/1503.02357)

