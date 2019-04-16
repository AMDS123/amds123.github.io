---
layout: post
title: "A theory of sequence indexing and working memory in recurrent neural networks"
date: 2018-02-28 17:54:24
categories: arXiv_CV
tags: arXiv_CV RNN
author: E. Paxon Frady, Denis Kleyko, Friedrich T. Sommer
mathjax: true
---

* content
{:toc}

##### Abstract
To accommodate structured approaches of neural computation, we propose a class of recurrent neural networks for indexing and storing sequences of symbols or analog data vectors. These networks with randomized input weights and orthogonal recurrent weights implement coding principles previously described in vector symbolic architectures (VSA), and leverage properties of reservoir computing. In general, the storage in reservoir computing is lossy and crosstalk noise limits the retrieval accuracy and information capacity. A novel theory to optimize memory performance in such networks is presented and compared with simulation experiments. The theory describes linear readout of analog data, and readout with winner-take-all error correction of symbolic data as proposed in VSA models. We find that diverse VSA models from the literature have universal performance properties, which are superior to what previous analyses predicted. Further, we propose novel VSA models with the statistically optimal Wiener filter in the readout that exhibit much higher information capacity, in particular for storing analog data. The presented theory also applies to memory buffers, networks with gradual forgetting, which can operate on infinite data streams without memory overflow. Interestingly, we find that different forgetting mechanisms, such as attenuating recurrent weights or neural nonlinearities, produce very similar behavior if the forgetting time constants are aligned. Such models exhibit extensive capacity when their forgetting time constant is optimized for given noise conditions and network size. These results enable the design of new types of VSA models for the online processing of data streams.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.00412](https://arxiv.org/abs/1803.00412)

##### PDF
[https://arxiv.org/pdf/1803.00412](https://arxiv.org/pdf/1803.00412)

