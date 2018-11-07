---
layout: post
title: "DAPPER: Scaling Dynamic Author Persona Topic Model to Billion Word Corpora"
date: 2018-11-03 21:27:56
categories: arXiv_CL
tags: arXiv_CL Optimization Inference
author: Robert Giaquinto, Arindam Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting common narratives from multi-author dynamic text corpora requires complex models, such as the Dynamic Author Persona (DAP) topic model. However, such models are complex and can struggle to scale to large corpora, often because of challenging non-conjugate terms. To overcome such challenges, in this paper we adapt new ideas in approximate inference to the DAP model, resulting in the DAP Performed Exceedingly Rapidly (DAPPER) topic model. Specifically, we develop Conjugate-Computation Variational Inference (CVI) based variational Expectation-Maximization (EM) for learning the model, yielding fast, closed form updates for each document, replacing iterative optimization in earlier work. Our results show significant improvements in model fit and training time without needing to compromise the model's temporal structure or the application of Regularized Variation Inference (RVI). We demonstrate the scalability and effectiveness of the DAPPER model by extracting health journeys from the CaringBridge corpus --- a collection of 9 million journals written by 200,000 authors during health crises.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01931](http://arxiv.org/abs/1811.01931)

##### PDF
[http://arxiv.org/pdf/1811.01931](http://arxiv.org/pdf/1811.01931)

