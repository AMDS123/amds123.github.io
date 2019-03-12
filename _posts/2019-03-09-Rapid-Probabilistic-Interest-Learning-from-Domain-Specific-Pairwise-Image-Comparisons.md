---
layout: post
title: "Rapid Probabilistic Interest Learning from Domain-Specific Pairwise Image Comparisons"
date: 2019-03-09 15:54:57
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Deep_Learning
author: Michael Burke
mathjax: true
---

* content
{:toc}

##### Abstract
A great deal of work aims to discover general purpose models of image interest or memorability for visual search and information retrieval. This paper argues that image interest is often domain and user specific, and that mechanisms for learning about this domain-specific image interest as quickly as possible, while limiting the amount of data-labelling required, are often more useful to end-users. Specifically, this paper is concerned with the small to medium-sized data regime regularly faced by practising data scientists, who are often required to build turnkey models for end-users with domain-specific challenges. This work uses pairwise image comparisons to reduce the labelling burden on these users, and shows that Gaussian process smoothing in image feature space can be used to build probabilistic models of image interest extremely quickly for a wide range of problems, and performs similarly to recent deep learning approaches trained using pairwise ranking losses. The Gaussian process model used in this work interpolates image interest inferred using a Bayesian ranking approach over image features extracted using a pre-trained convolutional neural network. This probabilistic approach produces image interests paired with uncertainties that can be used to identify images for which additional labelling is required and measure inference convergence. Results obtained on five distinct datasets reinforce recent findings that pre-trained convolutional neural networks can be used to extract useful representations applicable across multiple domains, and highlight the fact that domain-specific image interest does not always correlate with concepts like image memorability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1706.05850](http://arxiv.org/abs/1706.05850)

##### PDF
[http://arxiv.org/pdf/1706.05850](http://arxiv.org/pdf/1706.05850)

