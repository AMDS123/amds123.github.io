---
layout: post
title: "Projecting Embeddings for Domain Adaptation: Joint Modeling of Sentiment Analysis in Diverse Domains"
date: 2018-06-13 22:51:12
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Embedding Classification
author: Jeremy Barnes, Roman Klinger, Sabine Schulte im Walde
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation for sentiment analysis is challenging due to the fact that supervised classifiers are very sensitive to changes in domain. The two most prominent approaches to this problem are structural correspondence learning and autoencoders. However, they either require long training times or suffer greatly on highly divergent domains. Inspired by recent advances in cross-lingual sentiment analysis, we provide a novel perspective and cast the domain adaptation problem as an embedding projection task. Our model takes as input two mono-domain embedding spaces and learns to project them to a bi-domain space, which is jointly optimized to (1) project across domains and to (2) predict sentiment. We perform domain adaptation experiments on 20 source-target domain pairs for sentiment classification and report novel state-of-the-art results on 11 domain pairs, including the Amazon domain adaptation datasets and SemEval 2013 and 2016 datasets. Our analysis shows that our model performs comparably to state-of-the-art approaches on domains that are similar, while performing significantly better on highly divergent domains. Our code is available at this https URL

##### Abstract (translated by Google)
由于受监督的分类器对域中的变化非常敏感，所以用于情感分析的域适应是具有挑战性的。解决这个问题的两个最突出的方法是结构对应学习和自编码器。然而，他们要么需要很长的训练时间，要么在高度不同的领域遭受很大的痛苦受近期跨语言情感分析的进展启发，我们提供了一种新颖的视角，并将领域适应问题作为嵌入投影任务进行投射。我们的模型将输入的两个单域嵌入空间作为输入，并学习将它们投影到一个双域空间，该空间经过共同优化以（1）跨域项目和（2）预测情绪。我们针对情感分类对20个源 - 目标域对进行域适应性实验，并在11个域对（包括亚马逊域适应数据集和SemEval 2013和2016数据集）上报告新颖的最新结果。我们的分析表明，我们的模型在类似的领域表现出与最先进的方法相当的表现，同时在高度不同的领域表现更好。我们的代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1806.04381](https://arxiv.org/abs/1806.04381)

##### PDF
[https://arxiv.org/pdf/1806.04381](https://arxiv.org/pdf/1806.04381)

