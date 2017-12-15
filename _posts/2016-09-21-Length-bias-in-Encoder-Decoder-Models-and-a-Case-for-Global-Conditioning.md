---
layout: post
title: "Length bias in Encoder Decoder Models and a Case for Global Conditioning"
date: 2016-09-21 17:33:58
categories: arXiv_CL
tags: arXiv_CL Inference RNN
author: Pavel Sountsov, Sunita Sarawagi
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder networks are popular for modeling sequences probabilistically in many applications. These models use the power of the Long Short-Term Memory (LSTM) architecture to capture the full dependence among variables, unlike earlier models like CRFs that typically assumed conditional independence among non-adjacent variables. However in practice encoder-decoder models exhibit a bias towards short sequences that surprisingly gets worse with increasing beam size. In this paper we show that such phenomenon is due to a discrepancy between the full sequence margin and the per-element margin enforced by the locally conditioned training objective of a encoder-decoder model. The discrepancy more adversely impacts long sequences, explaining the bias towards predicting short sequences. For the case where the predicted sequences come from a closed set, we show that a globally conditioned model alleviates the above problems of encoder-decoder models. From a practical point of view, our proposed model also eliminates the need for a beam-search during inference, which reduces to an efficient dot-product based search in a vector-space.

##### Abstract (translated by Google)
编码器 - 解码器网络在许多应用中是概率性建模序列的流行。这些模型使用长期短期记忆（LSTM）体系结构的能力来捕捉变量之间的完全依赖关系，而不像早期的模型，如通常假定非相邻变量之间有条件独立性的CRF。然而，在实践中，编码器 - 解码器模型表现出对短序列的偏差，随着光束尺寸的增加，令人惊讶地变差。在本文中，我们表明，这种现象是由于编码器 - 解码器模型的局部条件训练目标强制执行的全部序列边界和每个元素边缘之间的差异造成的。这种差异会对长序列产生更大的不利影响，解释了预测短序列的偏见。对于预测序列来自封闭集合的情况，我们表明全局条件模型减轻了编码器 - 解码器模型的上述问题。从实际的角度来看，我们提出的模型也消除了推理期间的波束搜索的需要，这减少了在向量空间中基于点积的高效搜索。

##### URL
[https://arxiv.org/abs/1606.03402](https://arxiv.org/abs/1606.03402)

##### PDF
[https://arxiv.org/pdf/1606.03402](https://arxiv.org/pdf/1606.03402)

