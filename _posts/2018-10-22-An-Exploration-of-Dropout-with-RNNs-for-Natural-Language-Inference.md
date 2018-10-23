---
layout: post
title: "An Exploration of Dropout with RNNs for Natural Language Inference"
date: 2018-10-22 17:48:21
categories: arXiv_CL
tags: arXiv_CL Regularization Embedding Inference RNN
author: Amit Gajbhiye, Sardar Jaf, Noura Al Moubayed, A. Stephen McGough, Steven Bradley
mathjax: true
---

* content
{:toc}

##### Abstract
Dropout is a crucial regularization technique for the Recurrent Neural Network (RNN) models of Natural Language Inference (NLI). However, dropout has not been evaluated for the effectiveness at different layers and dropout rates in NLI models. In this paper, we propose a novel RNN model for NLI and empirically evaluate the effect of applying dropout at different layers in the model. We also investigate the impact of varying dropout rates at these layers. Our empirical evaluation on a large (Stanford Natural Language Inference (SNLI)) and a small (SciTail) dataset suggest that dropout at each feed-forward connection severely affects the model accuracy at increasing dropout rates. We also show that regularizing the embedding layer is efficient for SNLI whereas regularizing the recurrent layer improves the accuracy for SciTail. Our model achieved an accuracy 86.14% on the SNLI dataset and 77.05% on SciTail.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08606](http://arxiv.org/abs/1810.08606)

##### PDF
[http://arxiv.org/pdf/1810.08606](http://arxiv.org/pdf/1810.08606)

