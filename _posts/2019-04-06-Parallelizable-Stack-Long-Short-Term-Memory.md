---
layout: post
title: "Parallelizable Stack Long Short-Term Memory"
date: 2019-04-06 10:12:27
categories: arXiv_CL
tags: arXiv_CL RNN
author: Shuoyang Ding, Philipp Koehn
mathjax: true
---

* content
{:toc}

##### Abstract
Stack Long Short-Term Memory (StackLSTM) is useful for various applications such as parsing and string-to-tree neural machine translation, but it is also known to be notoriously difficult to parallelize for GPU training due to the fact that the computations are dependent on discrete operations. In this paper, we tackle this problem by utilizing state access patterns of StackLSTM to homogenize computations with regard to different discrete operations. Our parsing experiments show that the method scales up almost linearly with increasing batch size, and our parallelized PyTorch implementation trains significantly faster compared to the Dynet C++ implementation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03409](http://arxiv.org/abs/1904.03409)

##### PDF
[http://arxiv.org/pdf/1904.03409](http://arxiv.org/pdf/1904.03409)

