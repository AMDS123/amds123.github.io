---
layout: post
title: "WEST: Word Encoded Sequence Transducers"
date: 2018-11-20 18:47:50
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding Inference Classification Recognition
author: Ehsan Variani, Ananda Theertha Suresh, Mitchel Weintraub
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the parameters in large vocabulary models are used in embedding layer to map categorical features to vectors and in softmax layer for classification weights. This is a bottle-neck in memory constraint on-device training applications like federated learning and on-device inference applications like automatic speech recognition (ASR). One way of compressing the embedding and softmax layers is to substitute larger units such as words with smaller sub-units such as characters. However, often the sub-unit models perform poorly compared to the larger unit models. We propose WEST, an algorithm for encoding categorical features and output classes with a sequence of random or domain dependent sub-units and demonstrate that this transduction can lead to significant compression without compromising performance. WEST bridges the gap between larger unit and sub-unit models and can be interpreted as a MaxEnt model over sub-unit features, which can be of independent interest.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08417](http://arxiv.org/abs/1811.08417)

##### PDF
[http://arxiv.org/pdf/1811.08417](http://arxiv.org/pdf/1811.08417)

