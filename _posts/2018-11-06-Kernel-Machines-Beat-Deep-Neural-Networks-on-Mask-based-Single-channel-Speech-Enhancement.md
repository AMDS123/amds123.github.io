---
layout: post
title: "Kernel Machines Beat Deep Neural Networks on Mask-based Single-channel Speech Enhancement"
date: 2018-11-06 00:04:55
categories: arXiv_SD
tags: arXiv_SD Relation
author: Like Hui, Siyuan Ma, Mikhail Belkin
mathjax: true
---

* content
{:toc}

##### Abstract
We apply a fast kernel method for mask-based single-channel speech enhancement. Specifically, our method solves a kernel regression problem associated to a non-smooth kernel function (exponential power kernel) with a highly efficient iterative method (EigenPro). Due to the simplicity of this method, its hyper-parameters such as kernel bandwidth can be automatically and efficiently selected using line search with subsamples of training data. We observe an empirical correlation between the regression loss (mean square error) and regular metrics for speech enhancement. This observation justifies our training target and motivates us to achieve lower regression loss by training separate kernel model per frequency subband. We compare our method with the state-of-the-art deep neural networks on mask-based HINT and TIMIT. Experimental results show that our kernel method consistently outperforms deep neural networks while requiring less training time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02095](http://arxiv.org/abs/1811.02095)

##### PDF
[http://arxiv.org/pdf/1811.02095](http://arxiv.org/pdf/1811.02095)

