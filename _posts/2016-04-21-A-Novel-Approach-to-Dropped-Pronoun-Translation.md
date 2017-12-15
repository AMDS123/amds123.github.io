---
layout: post
title: "A Novel Approach to Dropped Pronoun Translation"
date: 2016-04-21 12:55:29
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning Prediction Detection
author: Longyue Wang, Zhaopeng Tu, Xiaojun Zhang, Hang Li, Andy Way, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Dropped Pronouns (DP) in which pronouns are frequently dropped in the source language but should be retained in the target language are challenge in machine translation. In response to this problem, we propose a semi-supervised approach to recall possibly missing pronouns in the translation. Firstly, we build training data for DP generation in which the DPs are automatically labelled according to the alignment information from a parallel corpus. Secondly, we build a deep learning-based DP generator for input sentences in decoding when no corresponding references exist. More specifically, the generation is two-phase: (1) DP position detection, which is modeled as a sequential labelling task with recurrent neural networks; and (2) DP prediction, which employs a multilayer perceptron with rich features. Finally, we integrate the above outputs into our translation system to recall missing pronouns by both extracting rules from the DP-labelled training data and translating the DP-generated input sentences. Experimental results show that our approach achieves a significant improvement of 1.58 BLEU points in translation performance with 66% F-score for DP generation accuracy.

##### Abstract (translated by Google)
用源语言代词经常掉落但应该保留在目标语言中的代词（DP）是机器翻译的挑战。针对这个问题，我们提出了一种半监督的方法来回忆翻译中可能缺失的代词。首先，根据平行语料库中的对齐信息，为DP生成DP数据，并自动标注DP数据。其次，在没有相应的参考文献的情况下，我们为解码的输入句子构建了一个深度学习型DP生成器。更具体地，生成是两阶段的：（1）DP位置检测，其被建模为具有递归神经网络的顺序标记任务;和（2）DP预测，其采用具有丰富特征的多层感知器。最后，我们将上述输出结合到我们的翻译系统中，通过从DP标注的训练数据中提取规则并翻译DP生成的输入句子来回忆失踪的代词。实验结果表明，我们的方法在翻译性能方面达到1.58BLEU点，DP生成精度为66％F-score。

##### URL
[https://arxiv.org/abs/1604.06285](https://arxiv.org/abs/1604.06285)

##### PDF
[https://arxiv.org/pdf/1604.06285](https://arxiv.org/pdf/1604.06285)

