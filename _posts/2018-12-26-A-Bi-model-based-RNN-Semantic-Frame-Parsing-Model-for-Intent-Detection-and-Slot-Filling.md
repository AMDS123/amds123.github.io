---
layout: post
title: "A Bi-model based RNN Semantic Frame Parsing Model for Intent Detection and Slot Filling"
date: 2018-12-26 05:55:42
categories: arXiv_AI
tags: arXiv_AI RNN Deep_Learning Detection
author: Yu Wang, Yilin Shen, Hongxia Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Intent detection and slot filling are two main tasks for building a spoken language understanding(SLU) system. Multiple deep learning based models have demonstrated good results on these tasks . The most effective algorithms are based on the structures of sequence to sequence models (or "encoder-decoder" models), and generate the intents and semantic tags either using separate models or a joint model. Most of the previous studies, however, either treat the intent detection and slot filling as two separate parallel tasks, or use a sequence to sequence model to generate both semantic tags and intent. Most of these approaches use one (joint) NN based model (including encoder-decoder structure) to model two tasks, hence may not fully take advantage of the cross-impact between them. In this paper, new Bi-model based RNN semantic frame parsing network structures are designed to perform the intent detection and slot filling tasks jointly, by considering their cross-impact to each other using two correlated bidirectional LSTMs (BLSTM). Our Bi-model structure with a decoder achieves state-of-the-art result on the benchmark ATIS data, with about 0.5$\%$ intent accuracy improvement and 0.9 $\%$ slot filling improvement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10235](http://arxiv.org/abs/1812.10235)

##### PDF
[http://arxiv.org/pdf/1812.10235](http://arxiv.org/pdf/1812.10235)

