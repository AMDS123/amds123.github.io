---
layout: post
title: "Towards Controlled Transformation of Sentiment in Sentences"
date: 2019-01-31 16:51:49
categories: arXiv_AI
tags: arXiv_AI Sentiment Attention
author: Wouter Leeftink, Gerasimos Spanakis
mathjax: true
---

* content
{:toc}

##### Abstract
An obstacle to the development of many natural language processing products is the vast amount of training examples necessary to get satisfactory results. The generation of these examples is often a tedious and time-consuming task. This paper this paper proposes a method to transform the sentiment of sentences in order to limit the work necessary to generate more training data. This means that one sentence can be transformed to an opposite sentiment sentence and should reduce by half the work required in the generation of text. The proposed pipeline consists of a sentiment classifier with an attention mechanism to highlight the short phrases that determine the sentiment of a sentence. Then, these phrases are changed to phrases of the opposite sentiment using a baseline model and an autoencoder approach. Experiments are run on both the separate parts of the pipeline as well as on the end-to-end model. The sentiment classifier is tested on its accuracy and is found to perform adequately. The autoencoder is tested on how well it is able to change the sentiment of an encoded phrase and it was found that such a task is possible. We use human evaluation to judge the performance of the full (end-to-end) pipeline and that reveals that a model using word vectors outperforms the encoder model. Numerical evaluation shows that a success rate of 54.7% is achieved on the sentiment change.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11467](http://arxiv.org/abs/1901.11467)

##### PDF
[http://arxiv.org/pdf/1901.11467](http://arxiv.org/pdf/1901.11467)

