---
layout: post
title: "Unfolding and Shrinking Neural Machine Translation Ensembles"
date: 2017-07-21 13:04:22
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Felix Stahlberg, Bill Byrne
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembling is a well-known technique in neural machine translation (NMT) to improve system performance. Instead of a single neural net, multiple neural nets with the same topology are trained separately, and the decoder generates predictions by averaging over the individual models. Ensembling often improves the quality of the generated translations drastically. However, it is not suitable for production systems because it is cumbersome and slow. This work aims to reduce the runtime to be on par with a single system without compromising the translation quality. First, we show that the ensemble can be unfolded into a single large neural network which imitates the output of the ensemble system. We show that unfolding can already improve the runtime in practice since more work can be done on the GPU. We proceed by describing a set of techniques to shrink the unfolded network by reducing the dimensionality of layers. On Japanese-English we report that the resulting network has the size and decoding speed of a single NMT network but performs on the level of a 3-ensemble system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.03279](https://arxiv.org/abs/1704.03279)

##### PDF
[https://arxiv.org/pdf/1704.03279](https://arxiv.org/pdf/1704.03279)

