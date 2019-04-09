---
layout: post
title: "Differentiable Sampling with Flexible Reference Word Order for Neural Machine Translation"
date: 2019-04-04 04:48:07
categories: arXiv_CL
tags: arXiv_CL
author: Weijia Xu, Xing Niu, Marine Carpuat
mathjax: true
---

* content
{:toc}

##### Abstract
Despite some empirical success at correcting exposure bias in machine translation, scheduled sampling algorithms suffer from a major drawback: they incorrectly assume that words in the reference translations and in sampled sequences are aligned at each time step. Our new differentiable sampling algorithm addresses this issue by optimizing the probability that the reference can be aligned with the sampled output, based on a soft alignment predicted by the model itself. As a result, the output distribution at each time step is evaluated with respect to the whole predicted sequence. Experiments on IWSLT translation tasks show that our approach improves BLEU compared to maximum likelihood and scheduled sampling baselines. In addition, our approach is simpler to train with no need for sampling schedule and yields models that achieve larger improvements with smaller beam sizes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04079](http://arxiv.org/abs/1904.04079)

##### PDF
[http://arxiv.org/pdf/1904.04079](http://arxiv.org/pdf/1904.04079)

