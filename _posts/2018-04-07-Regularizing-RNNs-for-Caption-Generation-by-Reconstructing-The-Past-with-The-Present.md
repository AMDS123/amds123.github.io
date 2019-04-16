---
layout: post
title: "Regularizing RNNs for Caption Generation by Reconstructing The Past with The Present"
date: 2018-04-07 01:49:44
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference RNN
author: Xinpeng Chen, Lin Ma, Wenhao Jiang, Jian Yao, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, caption generation with an encoder-decoder framework has been extensively studied and applied in different domains, such as image captioning, code captioning, and so on. In this paper, we propose a novel architecture, namely Auto-Reconstructor Network (ARNet), which, coupling with the conventional encoder-decoder framework, works in an end-to-end fashion to generate captions. ARNet aims at reconstructing the previous hidden state with the present one, besides behaving as the input-dependent transition operator. Therefore, ARNet encourages the current hidden state to embed more information from the previous one, which can help regularize the transition dynamics of recurrent neural networks (RNNs). Extensive experimental results show that our proposed ARNet boosts the performance over the existing encoder-decoder models on both image captioning and source code captioning tasks. Additionally, ARNet remarkably reduces the discrepancy between training and inference processes for caption generation. Furthermore, the performance on permuted sequential MNIST demonstrates that ARNet can effectively regularize RNN, especially on modeling long-term dependencies. Our code is available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.11439](https://arxiv.org/abs/1803.11439)

##### PDF
[https://arxiv.org/pdf/1803.11439](https://arxiv.org/pdf/1803.11439)

