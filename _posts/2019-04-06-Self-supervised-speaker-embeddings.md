---
layout: post
title: "Self-supervised speaker embeddings"
date: 2019-04-06 16:32:12
categories: arXiv_CV
tags: arXiv_CV Embedding Classification
author: Themos Stafylakis, Johan Rohdin, Oldrich Plchot, Petr Mizera, Lukas Burget
mathjax: true
---

* content
{:toc}

##### Abstract
Contrary to i-vectors, speaker embeddings such as x-vectors are incapable of leveraging unlabelled utterances, due to the classification loss over training speakers. In this paper, we explore an alternative training strategy to enable the use of unlabelled utterances in training. We propose to train speaker embedding extractors via reconstructing the frames of a target speech segment, given the inferred embedding of another speech segment of the same utterance. We do this by attaching to the standard speaker embedding extractor a decoder network, which we feed not merely with the speaker embedding, but also with the estimated phone sequence of the target frame sequence. The reconstruction loss can be used either as a single objective, or be combined with the standard speaker classification loss. In the latter case, it acts as a regularizer, encouraging generalizability to speakers unseen during training. In all cases, the proposed architectures are trained from scratch and in an end-to-end fashion. We demonstrate the benefits from the proposed approach on VoxCeleb and Speakers in the wild, and we report notable improvements over the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03486](http://arxiv.org/abs/1904.03486)

##### PDF
[http://arxiv.org/pdf/1904.03486](http://arxiv.org/pdf/1904.03486)

