---
layout: post
title: "Aspect Specific Opinion Expression Extraction using Attention based LSTM-CRF Network"
date: 2019-02-07 16:12:41
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention RNN Detection
author: Abhishek Laddha, Arjun Mukherjee
mathjax: true
---

* content
{:toc}

##### Abstract
Opinion phrase extraction is one of the key tasks in fine-grained sentiment analysis. While opinion expressions could be generic subjective expressions, aspect specific opinion expressions contain both the aspect as well as the opinion expression within the original sentence context. In this work, we formulate the task as an instance of token-level sequence labeling. When multiple aspects are present in a sentence, detection of opinion phrase boundary becomes difficult and label of each word depend not only upon the surrounding words but also with the concerned aspect. We propose a neural network architecture with bidirectional LSTM (Bi-LSTM) and a novel attention mechanism. Bi-LSTM layer learns the various sequential pattern among the words without requiring any hand-crafted features. The attention mechanism captures the importance of context words on a particular aspect opinion expression when multiple aspects are present in a sentence via location and content based memory. A Conditional Random Field (CRF) model is incorporated in the final layer to explicitly model the dependencies among the output labels. Experimental results on Hotel dataset from Tripadvisor.com showed that our approach outperformed several state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02709](http://arxiv.org/abs/1902.02709)

##### PDF
[http://arxiv.org/pdf/1902.02709](http://arxiv.org/pdf/1902.02709)

