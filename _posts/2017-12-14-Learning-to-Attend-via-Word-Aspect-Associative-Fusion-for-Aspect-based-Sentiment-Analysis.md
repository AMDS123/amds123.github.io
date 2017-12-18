---
layout: post
title: "Learning to Attend via Word-Aspect Associative Fusion for Aspect-based Sentiment Analysis"
date: 2017-12-14 12:46:44
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention GAN RNN Relation
author: Yi Tay, Anh Tuan Luu, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
Aspect-based sentiment analysis (ABSA) tries to predict the polarity of a given document with respect to a given aspect entity. While neural network architectures have been successful in predicting the overall polarity of sentences, aspect-specific sentiment analysis still remains as an open problem. In this paper, we propose a novel method for integrating aspect information into the neural model. More specifically, we incorporate aspect information into the neural model by modeling word-aspect relationships. Our novel model, \textit{Aspect Fusion LSTM} (AF-LSTM) learns to attend based on associative relationships between sentence words and aspect which allows our model to adaptively focus on the correct words given an aspect term. This ameliorates the flaws of other state-of-the-art models that utilize naive concatenations to model word-aspect similarity. Instead, our model adopts circular convolution and circular correlation to model the similarity between aspect and words and elegantly incorporates this within a differentiable neural attention framework. Finally, our model is end-to-end differentiable and highly related to convolution-correlation (holographic like) memories. Our proposed neural model achieves state-of-the-art performance on benchmark datasets, outperforming ATAE-LSTM by $4\%-5\%$ on average across multiple datasets.

##### Abstract (translated by Google)
基于方面的情感分析（ABSA）试图预测给定文档相对于给定方面实体的极性。虽然神经网络架构已经成功地预测了句子的整体极性，但是针对方面的情感分析仍然是一个悬而未决的问题。在本文中，我们提出了一种将方面信息整合到神经模型中的新方法。更具体地说，我们通过对字面关系进行建模，将方面信息结合到神经模型中。我们的新模型“Aspect Fusion LSTM”（AF-LSTM）基于句子和方面之间的联想关系学习参加，这使得我们的模型能够适应性地关注给定方面术语中的正确单词。这改善了其他最先进的模型，利用天真的连接模型字面相似性的缺陷。相反，我们的模型采用循环卷积和循环相关来模拟方面和词语之间的相似性，并将其优雅地结合在可微的神经关注框架内。最后，我们的模型是端到端可微的，并且与卷积相关（全息样）存储高度相关。我们提出的神经模型在基准数据集上实现了最新的性能，在多个数据集上的平均性能比ATAE-LSTM平均高出$ 4 \％ -  5 \％$。

##### URL
[http://arxiv.org/abs/1712.05403](http://arxiv.org/abs/1712.05403)

##### PDF
[http://arxiv.org/pdf/1712.05403](http://arxiv.org/pdf/1712.05403)

