---
layout: post
title: "Imitation Learning as $f$-Divergence Minimization"
date: 2019-05-30 07:19:13
categories: arXiv_RO
tags: arXiv_RO
author: Liyiming Ke, Matt Barnes, Wen Sun, Gilwoo Lee, Sanjiban Choudhury, Siddhartha Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of imitation learning with multi-modal demonstrations. Instead of attempting to learn all modes, we argue that in many tasks it is sufficient to imitate any one of them. We show that the state-of-the-art methods such as GAIL and behavior cloning, due to their choice of loss function, often incorrectly interpolate between such modes. Our key insight is to minimize the right divergence between the learner and the expert state-action distributions, namely the reverse KL divergence or I-projection. We propose a general imitation learning framework for estimating and minimizing any f-Divergence. By plugging in different divergences, we are able to recover existing algorithms such as Behavior Cloning (Kullback-Leibler), GAIL (Jensen Shannon) and Dagger (Total Variation). Empirical results show that our approximate I-projection technique is able to imitate multi-modal behaviors more reliably than GAIL and behavior cloning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12888](http://arxiv.org/abs/1905.12888)

##### PDF
[http://arxiv.org/pdf/1905.12888](http://arxiv.org/pdf/1905.12888)

