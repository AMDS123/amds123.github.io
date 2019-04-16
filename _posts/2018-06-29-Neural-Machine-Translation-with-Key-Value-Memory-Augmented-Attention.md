---
layout: post
title: "Neural Machine Translation with Key-Value Memory-Augmented Attention"
date: 2018-06-29 02:06:00
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Fandong Meng, Zhaopeng Tu, Yong Cheng, Haiyang Wu, Junjie Zhai, Yuekui Yang, Di Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Although attention-based Neural Machine Translation (NMT) has achieved remarkable progress in recent years, it still suffers from issues of repeating and dropping translations. To alleviate these issues, we propose a novel key-value memory-augmented attention model for NMT, called KVMEMATT. Specifically, we maintain a timely updated keymemory to keep track of attention history and a fixed value-memory to store the representation of source sentence throughout the whole translation process. Via nontrivial transformations and iterative interactions between the two memories, the decoder focuses on more appropriate source word(s) for predicting the next target word at each decoding step, therefore can improve the adequacy of translations. Experimental results on Chinese=>English and WMT17 German<=>English translation tasks demonstrate the superiority of the proposed model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.11249](https://arxiv.org/abs/1806.11249)

##### PDF
[https://arxiv.org/pdf/1806.11249](https://arxiv.org/pdf/1806.11249)

