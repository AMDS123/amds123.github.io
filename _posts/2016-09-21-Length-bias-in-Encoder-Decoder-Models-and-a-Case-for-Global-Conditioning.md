---
layout: post
title: "Length bias in Encoder Decoder Models and a Case for Global Conditioning"
date: 2016-09-21 17:33:58
categories: arXiv_CV
tags: arXiv_CV Inference RNN
author: Pavel Sountsov, Sunita Sarawagi
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder networks are popular for modeling sequences probabilistically in many applications. These models use the power of the Long Short-Term Memory (LSTM) architecture to capture the full dependence among variables, unlike earlier models like CRFs that typically assumed conditional independence among non-adjacent variables. However in practice encoder-decoder models exhibit a bias towards short sequences that surprisingly gets worse with increasing beam size. In this paper we show that such phenomenon is due to a discrepancy between the full sequence margin and the per-element margin enforced by the locally conditioned training objective of a encoder-decoder model. The discrepancy more adversely impacts long sequences, explaining the bias towards predicting short sequences. For the case where the predicted sequences come from a closed set, we show that a globally conditioned model alleviates the above problems of encoder-decoder models. From a practical point of view, our proposed model also eliminates the need for a beam-search during inference, which reduces to an efficient dot-product based search in a vector-space.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.03402](https://arxiv.org/abs/1606.03402)

##### PDF
[https://arxiv.org/pdf/1606.03402](https://arxiv.org/pdf/1606.03402)

