---
layout: post
title: "A principled approach for generating adversarial images under non-smooth dissimilarity metrics"
date: 2019-08-05 14:57:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse Classification
author: Aram-Alexandre Pooladian, Chris Finlay, Tim Hoheisel, Adam Oberman
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are vulnerable to adversarial perturbations: small changes in the input easily lead to misclassification. In this work, we propose an attack methodology catered not only for cases where the perturbations are measured by $\ell_p$ norms, but in fact any adversarial dissimilarity metric with a closed proximal form. This includes, but is not limited to, $\ell_1$, $\ell_2$, $\ell_\infty$ perturbations, and the $\ell_0$ counting "norm", i.e. true sparseness. Our approach to generating perturbations is a natural extension of our recent work, the LogBarrier attack, which previously required the metric to be differentiable. We demonstrate our new algorithm, ProxLogBarrier, on the MNIST, CIFAR10, and ImageNet-1k datasets. We attack undefended and defended models, and show that our algorithm transfers to various datasets with little parameter tuning. In particular, in the $\ell_0$ case, our algorithm finds significantly smaller perturbations compared to multiple existing methods

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01667](http://arxiv.org/abs/1908.01667)

##### PDF
[http://arxiv.org/pdf/1908.01667](http://arxiv.org/pdf/1908.01667)

