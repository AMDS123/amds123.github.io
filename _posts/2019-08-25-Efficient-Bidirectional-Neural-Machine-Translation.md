---
layout: post
title: "Efficient Bidirectional Neural Machine Translation"
date: 2019-08-25 13:59:03
categories: arXiv_CL
tags: arXiv_CL Inference
author: Xu Tan, Yingce Xia, Lijun Wu, Tao Qin
mathjax: true
---

* content
{:toc}

##### Abstract
The encoder-decoder based neural machine translation usually generates a target sequence token by token from left to right. Due to error propagation, the tokens in the right side of the generated sequence are usually of poorer quality than those in the left side. In this paper, we propose an efficient method to generate a sequence in both left-to-right and right-to-left manners using a single encoder and decoder, combining the advantages of both generation directions. Experiments on three translation tasks show that our method achieves significant improvements over conventional unidirectional approach. Compared with ensemble methods that train and combine two models with different generation directions, our method saves 50% model parameters and about 40% training time, and also improve inference speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09329](http://arxiv.org/abs/1908.09329)

##### PDF
[http://arxiv.org/pdf/1908.09329](http://arxiv.org/pdf/1908.09329)

