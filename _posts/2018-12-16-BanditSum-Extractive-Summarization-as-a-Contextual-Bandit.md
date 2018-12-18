---
layout: post
title: "BanditSum: Extractive Summarization as a Contextual Bandit"
date: 2018-12-16 21:59:30
categories: arXiv_CL
tags: arXiv_CL Summarization Reinforcement_Learning
author: Yue Dong, Yikang Shen, Eric Crawford, Herke van Hoof, Jackie Chi Kit Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel method for training neural networks to perform single-document extractive summarization without heuristically-generated extractive labels. We call our approach BanditSum as it treats extractive summarization as a contextual bandit (CB) problem, where the model receives a document to summarize (the context), and chooses a sequence of sentences to include in the summary (the action). A policy gradient reinforcement learning algorithm is used to train the model to select sequences of sentences that maximize ROUGE score. We perform a series of experiments demonstrating that BanditSum is able to achieve ROUGE scores that are better than or comparable to the state-of-the-art for extractive summarization, and converges using significantly fewer update steps than competing approaches. In addition, we show empirically that BanditSum performs significantly better than competing approaches when good summary sentences appear late in the source document.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09672](http://arxiv.org/abs/1809.09672)

##### PDF
[http://arxiv.org/pdf/1809.09672](http://arxiv.org/pdf/1809.09672)

