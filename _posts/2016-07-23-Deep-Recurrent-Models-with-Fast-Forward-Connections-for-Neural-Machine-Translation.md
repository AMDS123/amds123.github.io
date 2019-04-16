---
layout: post
title: "Deep Recurrent Models with Fast-Forward Connections for Neural Machine Translation"
date: 2016-07-23 13:14:17
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN
author: Jie Zhou, Ying Cao, Xuguang Wang, Peng Li, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) aims at solving machine translation (MT) problems using neural networks and has exhibited promising results in recent years. However, most of the existing NMT models are shallow and there is still a performance gap between a single NMT model and the best conventional MT system. In this work, we introduce a new type of linear connections, named fast-forward connections, based on deep Long Short-Term Memory (LSTM) networks, and an interleaved bi-directional architecture for stacking the LSTM layers. Fast-forward connections play an essential role in propagating the gradients and building a deep topology of depth 16. On the WMT'14 English-to-French task, we achieve BLEU=37.7 with a single attention model, which outperforms the corresponding single shallow model by 6.2 BLEU points. This is the first time that a single NMT model achieves state-of-the-art performance and outperforms the best conventional model by 0.7 BLEU points. We can still achieve BLEU=36.3 even without using an attention mechanism. After special handling of unknown words and model ensembling, we obtain the best score reported to date on this task with BLEU=40.4. Our models are also validated on the more difficult WMT'14 English-to-German task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.04199](https://arxiv.org/abs/1606.04199)

##### PDF
[https://arxiv.org/pdf/1606.04199](https://arxiv.org/pdf/1606.04199)

