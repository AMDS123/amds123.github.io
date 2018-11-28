---
layout: post
title: "Efficient Image Retrieval via Decoupling Diffusion into Online and Offline Processing"
date: 2018-11-27 10:52:26
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention
author: Fan Yang, Ryota Hinami, Yusuke Matsui, Steven Ly, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion is commonly used as a ranking or re-ranking method in retrieval tasks to achieve higher retrieval performance, and has attracted lots of attention in recent years. A downside to diffusion is that it performs slowly in comparison to the naive k-NN search, which causes a non-trivial online computational cost on large datasets. To overcome this weakness, we propose a novel diffusion technique in this paper. In our work, instead of applying diffusion to the query, we pre-compute the diffusion results of each element in the database, making the online search a simple linear combination on top of the k-NN search process. Our proposed method becomes 10~ times faster in terms of online search speed. Moreover, we propose to use late truncation instead of early truncation in previous works to achieve better retrieval performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10907](http://arxiv.org/abs/1811.10907)

##### PDF
[http://arxiv.org/pdf/1811.10907](http://arxiv.org/pdf/1811.10907)

