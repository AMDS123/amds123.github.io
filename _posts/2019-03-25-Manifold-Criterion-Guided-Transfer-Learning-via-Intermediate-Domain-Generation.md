---
layout: post
title: "Manifold Criterion Guided Transfer Learning via Intermediate Domain Generation"
date: 2019-03-25 09:58:51
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Lei Zhang, Shanshan Wang, Guang-Bin Huang, Wangmeng Zuo, Jian Yang, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In many practical transfer learning scenarios, the feature distribution is different across the source and target domains (i.e. non-i.i.d.). Maximum mean discrepancy (MMD), as a domain discrepancy metric, has achieved promising performance in unsupervised domain adaptation (DA). We argue that MMD-based DA methods ignore the data locality structure, which, to some extent, would cause the negative transfer effect. The locality plays an important role in minimizing the nonlinear local domain discrepancy underlying the marginal distributions. For better exploiting the domain locality, a novel local generative discrepancy metric (LGDM) based intermediate domain generation learning called Manifold Criterion guided Transfer Learning (MCTL) is proposed in this paper. The merits of the proposed MCTL are four-fold: 1) the concept of manifold criterion (MC) is first proposed as a measure validating the distribution matching across domains, and domain adaptation is achieved if the MC is satisfied; 2) the proposed MC can well guide the generation of the intermediate domain sharing similar distribution with the target domain, by minimizing the local domain discrepancy; 3) a global generative discrepancy metric (GGDM) is presented, such that both the global and local discrepancy can be effectively and positively reduced; 4) a simplified version of MCTL called MCTL-S is presented under a perfect domain generation assumption for more generic learning scenario. Experiments on a number of benchmark visual transfer tasks demonstrate the superiority of the proposed manifold criterion guided generative transfer method, by comparing with other state-of-the-art methods. The source code is available in https://github.com/wangshanshanCQU/MCTL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10211](http://arxiv.org/abs/1903.10211)

##### PDF
[http://arxiv.org/pdf/1903.10211](http://arxiv.org/pdf/1903.10211)

