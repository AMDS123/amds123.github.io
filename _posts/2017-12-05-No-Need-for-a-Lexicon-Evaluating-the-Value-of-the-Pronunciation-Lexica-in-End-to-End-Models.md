---
layout: post
title: "No Need for a Lexicon? Evaluating the Value of the Pronunciation Lexica in End-to-End Models"
date: 2017-12-05 19:02:28
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Tara N. Sainath, Rohit Prabhavalkar, Shankar Kumar, Seungji Lee, Anjuli Kannan, David Rybach, Vlad Schogol, Patrick Nguyen, Bo Li, Yonghui Wu, Zhifeng Chen, Chung-Cheng Chiu
mathjax: true
---

* content
{:toc}

##### Abstract
For decades, context-dependent phonemes have been the dominant sub-word unit for conventional acoustic modeling systems. This status quo has begun to be challenged recently by end-to-end models which seek to combine acoustic, pronunciation, and language model components into a single neural network. Such systems, which typically predict graphemes or words, simplify the recognition process since they remove the need for a separate expert-curated pronunciation lexicon to map from phoneme-based units to words. However, there has been little previous work comparing phoneme-based versus grapheme-based sub-word units in the end-to-end modeling framework, to determine whether the gains from such approaches are primarily due to the new probabilistic model, or from the joint learning of the various components with grapheme-based units. 
 In this work, we conduct detailed experiments which are aimed at quantifying the value of phoneme-based pronunciation lexica in the context of end-to-end models. We examine phoneme-based end-to-end models, which are contrasted against grapheme-based ones on a large vocabulary English Voice-search task, where we find that graphemes do indeed outperform phonemes. We also compare grapheme and phoneme-based approaches on a multi-dialect English task, which once again confirm the superiority of graphemes, greatly simplifying the system for recognizing multiple dialects.

##### Abstract (translated by Google)
数十年来，与上下文有关的音素一直是传统声学建模系统的主要分词单元。这种现状最近已经开始受到端到端模式的挑战，这种模式试图将声学，语音和语言模型组件结合到单一的神经网络中。这种典型地预测字形或单词的系统简化了识别过程，因为它们不需要单独的专家策划的发音词典来从基于音素的单元映射到单词。然而，在端对端建模框架中，比较基于音素的和基于字形的子单位单元，以前的工作很少，以确定这种方法的收益是主要归因于新的概率模型，还是来自以字素为单位联合学习各个组件。
 在这项工作中，我们进行了详细的实验，旨在量化基于音素的语音词汇在端到端模型中的价值。我们研究了基于音素的端到端模型，这与基于字形的基于大词汇量的英语语音搜索任务中的基于字形的模型形成对比，其中我们发现字形确实优于音素。我们还比较了在多方言英语任务中使用字形和基于音素的方法，这再次证实了字形的优越性，极大地简化了识别多种方言的系统。

##### URL
[http://arxiv.org/abs/1712.01864](http://arxiv.org/abs/1712.01864)

##### PDF
[http://arxiv.org/pdf/1712.01864](http://arxiv.org/pdf/1712.01864)

