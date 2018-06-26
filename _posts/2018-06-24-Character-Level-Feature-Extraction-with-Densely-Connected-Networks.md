---
layout: post
title: "Character-Level Feature Extraction with Densely Connected Networks"
date: 2018-06-24 05:54:45
categories: arXiv_CL
tags: arXiv_CL CNN RNN Recognition
author: Chanhee Lee, Young-Bum Kim, Dongyub Lee, HeuiSeok Lim
mathjax: true
---

* content
{:toc}

##### Abstract
Generating character-level features is an important step for achieving good results in various natural language processing tasks. To alleviate the need for human labor in generating hand-crafted features, methods that utilize neural architectures such as Convolutional Neural Network (CNN) or Recurrent Neural Network (RNN) to automatically extract such features have been proposed and have shown great results. However, CNN generates position-independent features, and RNN is slow since it needs to process the characters sequentially. In this paper, we propose a novel method of using a densely connected network to automatically extract character-level features. The proposed method does not require any language or task specific assumptions, and shows robustness and effectiveness while being faster than CNN- or RNN-based methods. Evaluating this method on three sequence labeling tasks - slot tagging, Part-of-Speech (POS) tagging, and Named-Entity Recognition (NER) - we obtain state-of-the-art performance with a 96.62 F1-score and 97.73% accuracy on slot tagging and POS tagging, respectively, and comparable performance to the state-of-the-art 91.13 F1-score on NER.

##### Abstract (translated by Google)
生成字符级特征是在各种自然语言处理任务中取得良好结果的重要步骤。为了减轻人工制作手工特征的需要，已经提出了利用诸如卷积神经网络（CNN）或递归神经网络（RNN）的神经架构来自动提取这些特征的方法，并且已经显示出很好的结果。但是，CNN生成与位置无关的特征，并且由于RNN需要按顺序处理字符，所以RNN较慢。在本文中，我们提出了一种使用密集连接网络自动提取字符级特征的新方法。所提出的方法不需要任何语言或任务特定的假设，并且显示出鲁棒性和有效性，同时比基于CNN或RNN的方法更快。在三个序列标注任务（槽标记，词性标注（Part-of-Speech，POS）标记和命名实体识别（NER））上评估此方法，我们获得了96.62 F1分和97.73％精确度分别为插槽标记和POS标记，并与NER的最新91.13 F1分数相媲美。

##### URL
[http://arxiv.org/abs/1806.09089](http://arxiv.org/abs/1806.09089)

##### PDF
[http://arxiv.org/pdf/1806.09089](http://arxiv.org/pdf/1806.09089)

