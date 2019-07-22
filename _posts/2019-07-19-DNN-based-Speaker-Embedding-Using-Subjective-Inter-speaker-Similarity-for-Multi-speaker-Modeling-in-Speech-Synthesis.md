---
layout: post
title: "DNN-based Speaker Embedding Using Subjective Inter-speaker Similarity for Multi-speaker Modeling in Speech Synthesis"
date: 2019-07-19 09:11:35
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Yuki Saito, Shinnosuke Takamichi, Hiroshi Saruwatari
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes novel algorithms for speaker embedding using subjective inter-speaker similarity based on deep neural networks (DNNs). Although conventional DNN-based speaker embedding such as a $d$-vector can be applied to multi-speaker modeling in speech synthesis, it does not correlate with the subjective inter-speaker similarity and is not necessarily appropriate speaker representation for open speakers whose speech utterances are not included in the training data. We propose two training algorithms for DNN-based speaker embedding model using an inter-speaker similarity matrix obtained by large-scale subjective scoring. One is based on similarity vector embedding and trains the model to predict a vector of the similarity matrix as speaker representation. The other is based on similarity matrix embedding and trains the model to minimize the squared Frobenius norm between the similarity matrix and the Gram matrix of $d$-vectors, i.e., the inter-speaker similarity derived from the $d$-vectors. We crowdsourced the inter-speaker similarity scores of 153 Japanese female speakers, and the experimental results demonstrate that our algorithms learn speaker embedding that is highly correlated with the subjective similarity. We also apply the proposed speaker embedding to multi-speaker modeling in DNN-based speech synthesis and reveal that the proposed similarity vector embedding improves synthetic speech quality for open speakers whose speech utterances are unseen during the training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08294](http://arxiv.org/abs/1907.08294)

##### PDF
[http://arxiv.org/pdf/1907.08294](http://arxiv.org/pdf/1907.08294)

