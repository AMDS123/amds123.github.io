---
layout: post
title: "Unbabel's Submission to the WMT2019 APE Shared Task: BERT-based Encoder-Decoder for Automatic Post-Editing"
date: 2019-05-30 14:17:39
categories: arXiv_CL
tags: arXiv_CL
author: Ant&#xf3;nio V. Lopes, M. Amin Farajian, Gon&#xe7;alo M. Correia, Jonay Trenous, Andr&#xe9; F. T. Martins
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes Unbabel's submission to the WMT2019 APE Shared Task for the English-German language pair. Following the recent rise of large, powerful, pre-trained models, we adapt the BERT pretrained model to perform Automatic Post-Editing in an encoder-decoder framework. Analogously to dual-encoder architectures we develop a BERT-based encoder-decoder (BED) model in which a single pretrained BERT encoder receives both the source src and machine translation tgt strings. Furthermore, we explore a conservativeness factor to constrain the APE system to perform fewer edits. As the official results show, when trained on a weighted combination of in-domain and artificial training data, our BED system with the conservativeness penalty improves significantly the translations of a strong Neural Machine Translation system by $-0.78$ and $+1.23$ in terms of TER and BLEU, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13068](http://arxiv.org/abs/1905.13068)

##### PDF
[http://arxiv.org/pdf/1905.13068](http://arxiv.org/pdf/1905.13068)

