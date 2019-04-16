---
layout: post
title: "Fast and Simple Mixture of Softmaxes with BPE and Hybrid-LightRNN for Language Generation"
date: 2018-09-25 03:02:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Xiang Kong, Qizhe Xie, Zihang Dai, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
Mixture of Softmaxes (MoS) has been shown to be effective at addressing the expressiveness limitation of Softmax-based models. Despite the known advantage, MoS is practically sealed by its large consumption of memory and computational time due to the need of computing multiple Softmaxes. In this work, we set out to unleash the power of MoS in practical applications by investigating improved word coding schemes, which could effectively reduce the vocabulary size and hence relieve the memory and computation burden. We show both BPE and our proposed Hybrid-LightRNN lead to improved encoding mechanisms that can halve the time and memory consumption of MoS without performance losses. With MoS, we achieve an improvement of 1.5 BLEU scores on IWSLT 2014 German-to-English corpus and an improvement of 0.76 CIDEr score on image captioning. Moreover, on the larger WMT 2014 machine translation dataset, our MoS-boosted Transformer yields 29.5 BLEU score for English-to-German and 42.1 BLEU score for English-to-French, outperforming the single-Softmax Transformer by 0.8 and 0.4 BLEU scores respectively and achieving the state-of-the-art result on WMT 2014 English-to-German task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.09296](https://arxiv.org/abs/1809.09296)

##### PDF
[https://arxiv.org/pdf/1809.09296](https://arxiv.org/pdf/1809.09296)

