---
layout: post
title: "Modeling Sentiment Dependencies with Graph Convolutional Networks for Aspect-level Sentiment Classification"
date: 2019-06-11 11:26:25
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Sentiment_Classification CNN Classification
author: Pinlong Zhaoa, Linlin Houb, Ou Wua
mathjax: true
---

* content
{:toc}

##### Abstract
Aspect-level sentiment classification aims to distinguish the sentiment polarities over one or more aspect terms in a sentence. Existing approaches mostly model different aspects in one sentence independently, which ignore the sentiment dependencies between different aspects. However, we find such dependency information between different aspects can bring additional valuable information. In this paper, we propose a novel aspect-level sentiment classification model based on graph convolutional networks (GCN) which can effectively capture the sentiment dependencies between multi-aspects in one sentence. Our model firstly introduces bidirectional attention mechanism with position encoding to model aspect-specific representations between each aspect and its context words, then employs GCN over the attention mechanism to capture the sentiment dependencies between different aspects in one sentence. We evaluate the proposed approach on the SemEval 2014 datasets. Experiments show that our model outperforms the state-of-the-art methods. We also conduct experiments to evaluate the effectiveness of GCN module, which indicates that the dependencies between different aspects is highly helpful in aspect-level sentiment classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04501](http://arxiv.org/abs/1906.04501)

##### PDF
[http://arxiv.org/pdf/1906.04501](http://arxiv.org/pdf/1906.04501)

