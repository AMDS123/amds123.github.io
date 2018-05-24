---
layout: post
title: "Enhancing Chinese Intent Classification by Dynamically Integrating Character Features into Word Embeddings with Ensemble Techniques"
date: 2018-05-23 00:18:42
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Deep_Learning Prediction
author: Ruixi Lin, Charles Costello, Charles Jankowski
mathjax: true
---

* content
{:toc}

##### Abstract
Intent classification has been widely researched on English data with deep learning approaches that are based on neural networks and word embeddings. The challenge for Chinese intent classification stems from the fact that, unlike English where most words are made up of 26 phonologic alphabet letters, Chinese is logographic, where a Chinese character is a more basic semantic unit that can be informative and its meaning does not vary too much in contexts. Chinese word embeddings alone can be inadequate for representing words, and pre-trained embeddings can suffer from not aligning well with the task at hand. To account for the inadequacy and leverage Chinese character information, we propose a low-effort and generic way to dynamically integrate character embedding based feature maps with word embedding based inputs, whose resulting word-character embeddings are stacked with a contextual information extraction module to further incorporate context information for predictions. On top of the proposed model, we employ an ensemble method to combine single models and obtain the final result. The approach is data-independent without relying on external sources like pre-trained word embeddings. The proposed model outperforms baseline models and existing methods.

##### Abstract (translated by Google)
Intent分类已经广泛地应用于基于神经网络和词嵌入的深度学习方法对英语数据进行研究。中国意图分类所面临的挑战源于这样的事实：与大多数单词由26个音韵字母组成的英语不同，汉语是符号的，其中汉字是更基本的语义单元，其可以是信息性的并且其含义不变在上下文中太多了。单独使用中文单词嵌入可能不足以表示单词，并且预先训练的嵌入可能会因与目前的任务不一致而受到影响。为了解决不足和影响汉字信息的问题，我们提出了一种低效，通用的方法，将基于字符嵌入的特征映射与基于词嵌入的输入进行动态集成，其结果字 - 字符嵌入与上下文信息提取模块堆叠以进一步结合上下文信息进行预测。在所提出的模型之上，我们采用集合方法来组合单个模型并获得最终结果。该方法独立于数据而不依赖于像预先训练的词嵌入这样的外部来源。所提出的模型优于基准模型和现有方法。

##### URL
[http://arxiv.org/abs/1805.08914](http://arxiv.org/abs/1805.08914)

##### PDF
[http://arxiv.org/pdf/1805.08914](http://arxiv.org/pdf/1805.08914)

