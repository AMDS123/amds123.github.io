---
layout: post
title: "A Call for Prudent Choice of Subword Merge Operations in Neural Machine Translation"
date: 2019-06-24 19:52:08
categories: arXiv_CL
tags: arXiv_CL RNN
author: Shuoyang Ding, Adithya Renduchintala, Kevin Duh
mathjax: true
---

* content
{:toc}

##### Abstract
Most neural machine translation systems are built upon subword units extracted by methods such as Byte-Pair Encoding (BPE) or wordpiece. However, the choice of number of merge operations is generally made by following existing recipes. In this paper, we conduct a systematic exploration on different numbers of BPE merge operations to understand how it interacts with the model architecture, the strategy to build vocabularies and the language pair. Our exploration could provide guidance for selecting proper BPE configurations in the future. Most prominently: we show that for LSTM-based architectures, it is necessary to experiment with a wide range of different BPE operations as there is no typical optimal BPE configuration, whereas for Transformer architectures, smaller BPE size tends to be a typically optimal choice. We urge the community to make prudent choices with subword merge operations, as our experiments indicate that a sub-optimal BPE configuration alone could easily reduce the system performance by 3-4 BLEU points.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10453](http://arxiv.org/abs/1905.10453)

##### PDF
[http://arxiv.org/pdf/1905.10453](http://arxiv.org/pdf/1905.10453)

