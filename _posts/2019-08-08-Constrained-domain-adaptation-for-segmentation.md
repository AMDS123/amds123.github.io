---
layout: post
title: "Constrained domain adaptation for segmentation"
date: 2019-08-08 10:07:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation Optimization Prediction Gradient_Descent
author: Mathilde Bateson, Jose Dolz, Hoel Kervadec, Herv&#xe9; Lombaert, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to adapt segmentation networks with a constrained formulation, which embeds domain-invariant prior knowledge about the segmentation regions. Such knowledge may take the form of simple anatomical information, e.g., structure size or shape, estimated from source samples or known a priori. Our method imposes domain-invariant inequality constraints on the network outputs of unlabeled target samples. It implicitly matches prediction statistics between target and source domains with permitted uncertainty of prior knowledge. We address our constrained problem with a differentiable penalty, fully suited for standard stochastic gradient descent approaches, removing the need for computationally expensive Lagrangian optimization with dual projections. Unlike current two-step adversarial training, our formulation is based on a single loss in a single network, which simplifies adaptation by avoiding extra adversarial steps, while improving convergence and quality of training. 
 The comparison of our approach with state-of-the-art adversarial methods reveals substantially better performance on the challenging task of adapting spine segmentation across different MRI modalities. Our results also show a robustness to imprecision of size priors, approaching the accuracy of a fully supervised model trained directly in a target domain.Our method can be readily used for various constraints and segmentation problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02996](http://arxiv.org/abs/1908.02996)

##### PDF
[http://arxiv.org/pdf/1908.02996](http://arxiv.org/pdf/1908.02996)

