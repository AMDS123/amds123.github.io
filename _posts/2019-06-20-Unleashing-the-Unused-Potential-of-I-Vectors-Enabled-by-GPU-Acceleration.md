---
layout: post
title: "Unleashing the Unused Potential of I-Vectors Enabled by GPU Acceleration"
date: 2019-06-20 11:09:39
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Ville Vestman, Kong Aik Lee, Tomi H. Kinnunen, Takafumi Koshinaka
mathjax: true
---

* content
{:toc}

##### Abstract
Speaker embeddings are continuous-value vector representations that allow easy comparison between voices of speakers with simple geometric operations. Among others, i-vector and x-vector have emerged as the mainstream methods for speaker embedding. In this paper, we illustrate the use of modern computation platform to harness the benefit of GPU acceleration for i-vector extraction. In particular, we achieve an acceleration of 3000 times in frame posterior computation compared to real time and 25 times in training the i-vector extractor compared to the CPU baseline from Kaldi toolkit. This significant speed-up allows the exploration of ideas that were hitherto impossible. In particular, we show that it is beneficial to update the universal background model (UBM) and re-compute frame alignments while training the i-vector extractor. Additionally, we are able to study different variations of i-vector extractors more rigorously than before. In this process, we reveal some undocumented details of Kaldi's i-vector extractor and show that it outperforms the standard formulation by a margin of 1 to 2% when tested with VoxCeleb speaker verification protocol. All of our findings are asserted by ensemble averaging the results from multiple runs with random start.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08556](http://arxiv.org/abs/1906.08556)

##### PDF
[http://arxiv.org/pdf/1906.08556](http://arxiv.org/pdf/1906.08556)

