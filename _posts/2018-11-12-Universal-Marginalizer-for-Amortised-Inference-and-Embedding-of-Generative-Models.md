---
layout: post
title: "Universal Marginalizer for Amortised Inference and Embedding of Generative Models"
date: 2018-11-12 13:55:15
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Inference Classification Relation
author: Robert Walecki, Albert Buchard, Kostis Gourgoulias, Chris Hart, Maria Lomeli, A. K. W. Navarro, Max Zwiessele, Yura Perov, Saurabh Johri
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic graphical models are powerful tools which allow us to formalise our knowledge about the world and reason about its inherent uncertainty. There exist a considerable number of methods for performing inference in probabilistic graphical models; however, they can be computationally costly due to significant time burden and/or storage requirements; or they lack theoretical guarantees of convergence and accuracy when applied to large scale graphical models. To this end, we propose the Universal Marginaliser Importance Sampler (UM-IS) -- a hybrid inference scheme that combines the flexibility of a deep neural network trained on samples from the model and inherits the asymptotic guarantees of importance sampling. We show how combining samples drawn from the graphical model with an appropriate masking function allows us to train a single neural network to approximate any of the corresponding conditional marginal distributions, and thus amortise the cost of inference. We also show that the graph embeddings can be applied for tasks such as: clustering, classification and interpretation of relationships between the nodes. Finally, we benchmark the method on a large graph (&gt;1000 nodes), showing that UM-IS outperforms sampling-based methods by a large margin while being computationally efficient.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04727](http://arxiv.org/abs/1811.04727)

##### PDF
[http://arxiv.org/pdf/1811.04727](http://arxiv.org/pdf/1811.04727)

