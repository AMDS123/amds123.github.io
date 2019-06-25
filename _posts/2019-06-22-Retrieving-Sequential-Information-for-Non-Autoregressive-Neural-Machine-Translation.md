---
layout: post
title: "Retrieving Sequential Information for Non-Autoregressive Neural Machine Translation"
date: 2019-06-22 13:20:57
categories: arXiv_AI
tags: arXiv_AI
author: Chenze Shao, Yang Feng, Jinchao Zhang, Fandong Meng, Xilin Chen, Jie Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Non-Autoregressive Transformer (NAT) aims to accelerate the Transformer model through discarding the autoregressive mechanism and generating target words independently, which fails to exploit the target sequential information. Over-translation and under-translation errors often occur for the above reason, especially in the long sentence translation scenario. In this paper, we propose two approaches to retrieve the target sequential information for NAT to enhance its translation ability while preserving the fast-decoding property. Firstly, we propose a sequence-level training method based on a novel reinforcement algorithm for NAT (Reinforce-NAT) to reduce the variance and stabilize the training procedure. Secondly, we propose an innovative Transformer decoder named FS-decoder to fuse the target sequential information into the top layer of the decoder. Experimental results on three translation tasks show that the Reinforce-NAT surpasses the baseline NAT system by a significant margin on BLEU without decelerating the decoding speed and the FS-decoder achieves comparable translation performance to the autoregressive Transformer with considerable speedup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09444](http://arxiv.org/abs/1906.09444)

##### PDF
[http://arxiv.org/pdf/1906.09444](http://arxiv.org/pdf/1906.09444)

