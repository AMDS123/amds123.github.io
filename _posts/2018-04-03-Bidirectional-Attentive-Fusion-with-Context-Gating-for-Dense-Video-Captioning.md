---
layout: post
title: "Bidirectional Attentive Fusion with Context Gating for Dense Video Captioning"
date: 2018-04-03 08:29:53
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Prediction
author: Jingwen Wang, Wenhao Jiang, Lin Ma, Wei Liu, Yong Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Dense video captioning is a newly emerging task that aims at both localizing and describing all events in a video. We identify and tackle two challenges on this task, namely, (1) how to utilize both past and future contexts for accurate event proposal predictions, and (2) how to construct informative input to the decoder for generating natural event descriptions. First, previous works predominantly generate temporal event proposals in the forward direction, which neglects future video context. We propose a bidirectional proposal method that effectively exploits both past and future contexts to make proposal predictions. Second, different events ending at (nearly) the same time are indistinguishable in the previous works, resulting in the same captions. We solve this problem by representing each event with an attentive fusion of hidden states from the proposal module and video contents (e.g., C3D features). We further propose a novel context gating mechanism to balance the contributions from the current event and its surrounding contexts dynamically. We empirically show that our attentively fused event representation is superior to the proposal hidden states or video contents alone. By coupling proposal and captioning modules into one unified framework, our model outperforms the state-of-the-arts on the ActivityNet Captions dataset with a relative gain of over 100% (Meteor score increases from 4.82 to 9.65).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.00100](https://arxiv.org/abs/1804.00100)

##### PDF
[https://arxiv.org/pdf/1804.00100](https://arxiv.org/pdf/1804.00100)

