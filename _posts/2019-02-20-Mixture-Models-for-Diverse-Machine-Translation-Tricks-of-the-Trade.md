---
layout: post
title: "Mixture Models for Diverse Machine Translation: Tricks of the Trade"
date: 2019-02-20 23:57:35
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Tianxiao Shen, Myle Ott, Michael Auli, Marc&#x27;Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
Mixture models trained via EM are among the simplest, most widely used and well understood latent variable models in the machine learning literature. Surprisingly, these models have been hardly explored in text generation applications such as machine translation. In principle, they provide a latent variable to control generation and produce a diverse set of hypotheses. In practice, however, mixture models are prone to degeneracies---often only one component gets trained or the latent variable is simply ignored. We find that disabling dropout noise in responsibility computation is critical to successful training. In addition, the design choices of parameterization, prior distribution, hard versus soft EM and online versus offline assignment can dramatically affect model performance. We develop an evaluation protocol to assess both quality and diversity of generations against multiple references, and provide an extensive empirical study of several mixture model variants. Our analysis shows that certain types of mixture models are more robust and offer the best trade-off between translation quality and diversity compared to variational models and diverse decoding approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07816](http://arxiv.org/abs/1902.07816)

##### PDF
[http://arxiv.org/pdf/1902.07816](http://arxiv.org/pdf/1902.07816)

