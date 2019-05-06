---
layout: post
title: "Fully Empirical Autotuned QR Factorization For Multicore Architectures"
date: 2011-02-25 20:21:32
categories: arXiv_CV
tags: arXiv_CV
author: Emmanuel Agullo (INRIA Bordeaux - Sud-Ouest, LaBRI), Jack Dongarra (ICL), Rajib Nath (ICL), Stanimire Tomov (ICL)
mathjax: true
---

* content
{:toc}

##### Abstract
Tuning numerical libraries has become more difficult over time, as systems get more sophisticated. In particular, modern multicore machines make the behaviour of algorithms hard to forecast and model. In this paper, we tackle the issue of tuning a dense QR factorization on multicore architectures. We show that it is hard to rely on a model, which motivates us to design a fully empirical approach. We exhibit few strong empirical properties that enable us to efficiently prune the search space. Our method is automatic, fast and reliable. The tuning process is indeed fully performed at install time in less than one and ten minutes on five out of seven platforms. We achieve an average performance varying from 97% to 100% of the optimum performance depending on the platform. This work is a basis for autotuning the PLASMA library and enabling easy performance portability across hardware systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1102.5328](https://arxiv.org/abs/1102.5328)

##### PDF
[https://arxiv.org/pdf/1102.5328](https://arxiv.org/pdf/1102.5328)

