---
layout: post
title: "Language-Independent Representor for Neural Machine Translation"
date: 2018-11-01 06:47:23
categories: arXiv_CL
tags: arXiv_CL NMT
author: Long Zhou, Yuchen Liu, Jiajun Zhang, Chengqing Zong, Guoping Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Current Neural Machine Translation (NMT) employs a language-specific encoder to represent the source sentence and adopts a language-specific decoder to generate target translation. This language-dependent design leads to large-scale network parameters and makes the duality of the parallel data underutilized. To address the problem, we propose in this paper a language-independent representor to replace the encoder and decoder by using weight sharing. This shared representor can not only reduce large portion of network parameters, but also facilitate us to fully explore the language duality by jointly training source-to-target, target-to-source, left-to-right and right-to-left translations within a multi-task learning framework. Experiments show that our proposed framework can obtain significant improvements over conventional NMT models on resource-rich and low-resource translation tasks with only a quarter of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00258](http://arxiv.org/abs/1811.00258)

##### PDF
[http://arxiv.org/pdf/1811.00258](http://arxiv.org/pdf/1811.00258)

