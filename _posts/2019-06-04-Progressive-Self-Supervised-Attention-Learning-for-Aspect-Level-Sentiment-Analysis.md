---
layout: post
title: "Progressive Self-Supervised Attention Learning for Aspect-Level Sentiment Analysis"
date: 2019-06-04 06:07:56
categories: arXiv_CL
tags: arXiv_CL Regularization Sentiment Attention Sentiment_Classification Classification Prediction
author: Jialong Tang, Ziyao Lu, Jinsong Su, Yubin Ge, Linfeng Song, Le Sun, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In aspect-level sentiment classification (ASC), it is prevalent to equip dominant neural models with attention mechanisms, for the sake of acquiring the importance of each context word on the given aspect. However, such a mechanism tends to excessively focus on a few frequent words with sentiment polarities, while ignoring infrequent ones. In this paper, we propose a progressive self-supervised attention learning approach for neural ASC models, which automatically mines useful attention supervision information from a training corpus to refine attention mechanisms. Specifically, we iteratively conduct sentiment predictions on all training instances. Particularly, at each iteration, the context word with the maximum attention weight is extracted as the one with active/misleading influence on the correct/incorrect prediction of every instance, and then the word itself is masked for subsequent iterations. Finally, we augment the conventional training objective with a regularization term, which enables ASC models to continue equally focusing on the extracted active context words while decreasing weights of those misleading ones. Experimental results on multiple datasets show that our proposed approach yields better attention mechanisms, leading to substantial improvements over the two state-of-the-art neural ASC models. Source code and trained models are available at https://github.com/DeepLearnXMU/PSSAttention.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01213](http://arxiv.org/abs/1906.01213)

##### PDF
[http://arxiv.org/pdf/1906.01213](http://arxiv.org/pdf/1906.01213)

