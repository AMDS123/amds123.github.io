---
layout: post
title: "Hybrid Self-Attention Network for Machine Translation"
date: 2018-11-01 06:35:21
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Kaitao Song, Tan Xu, Furong Peng, Jianfeng Lu
mathjax: true
---

* content
{:toc}

##### Abstract
The encoder-decoder is the typical framework for Neural Machine Translation (NMT), and different structures have been developed for improving the translation performance. Transformer is one of the most promising structures, which can leverage the self-attention mechanism to capture the semantic dependency from global view. However, it cannot distinguish the relative position of different tokens very well, such as the tokens located at the left or right of the current token, and cannot focus on the local information around the current token either. To alleviate these problems, we propose a novel attention mechanism named Hybrid Self-Attention Network (HySAN) which accommodates some specific-designed masks for self-attention network to extract various semantic, such as the global/local information, the left/right part context. Finally, a squeeze gate is introduced to combine different kinds of SANs for fusion. Experimental results on three machine translation tasks show that our proposed framework outperforms the Transformer baseline significantly and achieves superior results over state-of-the-art NMT systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00253](http://arxiv.org/abs/1811.00253)

##### PDF
[http://arxiv.org/pdf/1811.00253](http://arxiv.org/pdf/1811.00253)

