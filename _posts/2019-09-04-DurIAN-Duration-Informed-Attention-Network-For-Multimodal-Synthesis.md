---
layout: post
title: "DurIAN: Duration Informed Attention Network For Multimodal Synthesis"
date: 2019-09-04 11:35:48
categories: arXiv_CL
tags: arXiv_CL Attention Face RNN
author: Chengzhu Yu, Heng Lu, Na Hu, Meng Yu, Chao Weng, Kun Xu, Peng Liu, Deyi Tuo, Shiyin Kang, Guangzhi Lei, Dan Su, Dong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a generic and robust multimodal synthesis system that produces highly natural speech and facial expression simultaneously. The key component of this system is the Duration Informed Attention Network (DurIAN), an autoregressive model in which the alignments between the input text and the output acoustic features are inferred from a duration model. This is different from the end-to-end attention mechanism used, and accounts for various unavoidable artifacts, in existing end-to-end speech synthesis systems such as Tacotron. Furthermore, DurIAN can be used to generate high quality facial expression which can be synchronized with generated speech with/without parallel speech and face data. To improve the efficiency of speech generation, we also propose a multi-band parallel generation strategy on top of the WaveRNN model. The proposed Multi-band WaveRNN effectively reduces the total computational complexity from 9.8 to 5.5 GFLOPS, and is able to generate audio that is 6 times faster than real time on a single CPU core. We show that DurIAN could generate highly natural speech that is on par with current state of the art end-to-end systems, while at the same time avoid word skipping/repeating errors in those systems. Finally, a simple yet effective approach for fine-grained control of expressiveness of speech and facial expression is introduced.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01700](http://arxiv.org/abs/1909.01700)

##### PDF
[http://arxiv.org/pdf/1909.01700](http://arxiv.org/pdf/1909.01700)

