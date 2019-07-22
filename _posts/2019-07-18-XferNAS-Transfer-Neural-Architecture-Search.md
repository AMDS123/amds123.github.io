---
layout: post
title: "XferNAS: Transfer Neural Architecture Search"
date: 2019-07-18 22:05:49
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Martin Wistuba
mathjax: true
---

* content
{:toc}

##### Abstract
The term Neural Architecture Search (NAS) refers to the automatic optimization of network architectures for a new, previously unknown task. Since testing an architecture is computationally very expensive, many optimizers need days or even weeks to find suitable architectures. However, this search time can be significantly reduced if knowledge from previous searches on different tasks is reused. In this work, we propose a generally applicable framework that introduces only minor changes to existing optimizers to leverage this feature. As an example, we select an existing optimizer and demonstrate the complexity of the integration of the framework as well as its impact. In experiments on CIFAR-10 and CIFAR-100, we observe a reduction in the search time from 200 to only 6 GPU days, a speed up by a factor of 33. In addition, we observe new records of 1.99 and 14.06 for NAS optimizers on the CIFAR benchmarks, respectively. In a separate study, we analyze the impact of the amount of source and target data. Empirically, we demonstrate that the proposed framework generally gives better results and, in the worst case, is just as good as the unmodified optimizer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08307](http://arxiv.org/abs/1907.08307)

##### PDF
[http://arxiv.org/pdf/1907.08307](http://arxiv.org/pdf/1907.08307)

