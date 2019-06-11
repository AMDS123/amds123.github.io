---
layout: post
title: "Effective Use of Variational Embedding Capacity in Expressive End-to-End Speech Synthesis"
date: 2019-06-08 06:59:56
categories: arXiv_CL
tags: arXiv_CL Style_Transfer Embedding
author: Eric Battenberg, Soroosh Mariooryad, Daisy Stanton, RJ Skerry-Ryan, Matt Shannon, David Kao, Tom Bagby
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has explored sequence-to-sequence latent variable models for expressive speech synthesis (supporting control and transfer of prosody and style), but has not presented a coherent framework for understanding the trade-offs between the competing methods. In this paper, we propose embedding capacity as a unified method of analyzing the behavior of latent variable models of speech, comparing existing heuristic (non-variational) methods to variational methods that are able to explicitly constrain capacity using an upper bound on representational mutual information. In our proposed model, we show that by adding conditional dependencies to the variational posterior such that it matches the form of the true posterior, the same model can be used for high-precision prosody transfer, text-agnostic style transfer, and generation of natural-sounding prior samples. For multi-speaker models, the proposed model is able to preserve target speaker identity during inter-speaker prosody transfer and when drawing samples from the latent prior. Lastly, we introduce a method for decomposing embedding capacity hierarchically across two sets of latents, allowing a portion of the latent variability to be specified and the remaining variability sampled from a learned prior.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03402](http://arxiv.org/abs/1906.03402)

##### PDF
[http://arxiv.org/pdf/1906.03402](http://arxiv.org/pdf/1906.03402)

