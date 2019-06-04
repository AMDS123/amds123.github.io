---
layout: post
title: "Masked Non-Autoregressive Image Captioning"
date: 2019-06-03 11:34:41
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference
author: Junlong Gao, Xi Meng, Shiqi Wang, Xia Li, Shanshe Wang, Siwei Ma, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Existing captioning models often adopt the encoder-decoder architecture, where the decoder uses autoregressive decoding to generate captions, such that each token is generated sequentially given the preceding generated tokens. However, autoregressive decoding results in issues such as sequential error accumulation, slow generation, improper semantics and lack of diversity. Non-autoregressive decoding has been proposed to tackle slow generation for neural machine translation but suffers from multimodality problem due to the indirect modeling of the target distribution. In this paper, we propose masked non-autoregressive decoding to tackle the issues of both autoregressive decoding and non-autoregressive decoding. In masked non-autoregressive decoding, we mask several kinds of ratios of the input sequences during training, and generate captions parallelly in several stages from a totally masked sequence to a totally non-masked sequence in a compositional manner during inference. Experimentally our proposed model can preserve semantic content more effectively and can generate more diverse captions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00717](http://arxiv.org/abs/1906.00717)

##### PDF
[http://arxiv.org/pdf/1906.00717](http://arxiv.org/pdf/1906.00717)

