---
layout: post
title: "Differentiable Supervector Extraction for Encoding Speaker and Phrase Information in Text Dependent Speaker Verification"
date: 2018-12-22 09:25:59
categories: arXiv_SD
tags: arXiv_SD Embedding CNN
author: Victoria Mingote, Antonio Miguel, Alfonso Ortega, Eduardo Lleida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new differentiable neural network alignment mechanism for text-dependent speaker verification which uses alignment models to produce a supervector representation of an utterance. Unlike previous works with similar approaches, we do not extract the embedding of an utterance from the mean reduction of the temporal dimension. Our system replaces the mean by a phrase alignment model to keep the temporal structure of each phrase which is relevant in this application since the phonetic information is part of the identity in the verification task. Moreover, we can apply a convolutional neural network as front-end, and thanks to the alignment process being differentiable, we can train the whole network to produce a supervector for each utterance which will be discriminative with respect to the speaker and the phrase simultaneously. As we show, this choice has the advantage that the supervector encodes the phrase and speaker information providing good performance in text-dependent speaker verification tasks. In this work, the process of verification is performed using a basic similarity metric, due to simplicity, compared to other more elaborate models that are commonly used. The new model using alignment to produce supervectors was tested on the RSR2015-Part I database for text-dependent speaker verification, providing competitive results compared to similar size networks using the mean to extract embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09484](http://arxiv.org/abs/1812.09484)

##### PDF
[http://arxiv.org/pdf/1812.09484](http://arxiv.org/pdf/1812.09484)

