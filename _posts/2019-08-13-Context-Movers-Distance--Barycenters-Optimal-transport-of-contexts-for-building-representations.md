---
layout: post
title: "Context Mover's Distance & Barycenters: Optimal transport of contexts for building representations"
date: 2019-08-13 15:45:32
categories: arXiv_CL
tags: arXiv_CL Embedding Represenation_Learning Quantitative
author: Sidak Pal Singh, Andreas Hug, Aymeric Dieuleveut, Martin Jaggi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for building unsupervised representations of entities and their compositions, where each entity is viewed as a probability distribution rather than a vector embedding. In particular, this distribution is supported over the contexts which co-occur with the entity and are embedded in a suitable low-dimensional space. This enables us to consider representation learning from the perspective of Optimal Transport and take advantage of its tools such as Wasserstein distance and barycenters. We elaborate how the method can be applied for obtaining unsupervised representations of text and illustrate the performance (quantitatively as well as qualitatively) on tasks such as measuring sentence similarity, word entailment and similarity, where we empirically observe significant gains (e.g., 4.1% relative improvement over Sent2vec, GenSen). 
 The key benefits of the proposed approach include: (a) capturing uncertainty and polysemy via modeling the entities as distributions, (b) utilizing the underlying geometry of the particular task (with the ground cost), (c) simultaneously providing interpretability with the notion of optimal transport between contexts and (d) easy applicability on top of existing point embedding methods. The code, as well as prebuilt histograms, are available under https://github.com/context-mover/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.09663](http://arxiv.org/abs/1808.09663)

##### PDF
[http://arxiv.org/pdf/1808.09663](http://arxiv.org/pdf/1808.09663)

