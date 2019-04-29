---
layout: post
title: "SWALP : Stochastic Weight Averaging in Low-Precision Training"
date: 2019-04-26 17:22:06
categories: arXiv_AI
tags: arXiv_AI
author: Guandao Yang, Tianyi Zhang, Polina Kirichenko, Junwen Bai, Andrew Gordon Wilson, Christopher De Sa
mathjax: true
---

* content
{:toc}

##### Abstract
Low precision operations can provide scalability, memory savings, portability, and energy efficiency. This paper proposes SWALP, an approach to low precision training that averages low-precision SGD iterates with a modified learning rate schedule. SWALP is easy to implement and can match the performance of full-precision SGD even with all numbers quantized down to 8 bits, including the gradient accumulators. Additionally, we show that SWALP converges arbitrarily close to the optimal solution for quadratic objectives, and to a noise ball asymptotically smaller than low precision SGD in strongly convex settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11943](http://arxiv.org/abs/1904.11943)

##### PDF
[http://arxiv.org/pdf/1904.11943](http://arxiv.org/pdf/1904.11943)

