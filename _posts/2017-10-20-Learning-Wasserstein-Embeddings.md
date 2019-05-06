---
layout: post
title: "Learning Wasserstein Embeddings"
date: 2017-10-20 09:09:34
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Optimization
author: Nicolas Courty, Rémi Flamary, Mélanie Ducoffe
mathjax: true
---

* content
{:toc}

##### Abstract
The Wasserstein distance received a lot of attention recently in the community of machine learning, especially for its principled way of comparing distributions. It has found numerous applications in several hard problems, such as domain adaptation, dimensionality reduction or generative models. However, its use is still limited by a heavy computational cost. Our goal is to alleviate this problem by providing an approximation mechanism that allows to break its inherent complexity. It relies on the search of an embedding where the Euclidean distance mimics the Wasserstein distance. We show that such an embedding can be found with a siamese architecture associated with a decoder network that allows to move from the embedding space back to the original input space. Once this embedding has been found, computing optimization problems in the Wasserstein space (e.g. barycenters, principal directions or even archetypes) can be conducted extremely fast. Numerical experiments supporting this idea are conducted on image datasets, and show the wide potential benefits of our method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.07457](https://arxiv.org/abs/1710.07457)

##### PDF
[https://arxiv.org/pdf/1710.07457](https://arxiv.org/pdf/1710.07457)

