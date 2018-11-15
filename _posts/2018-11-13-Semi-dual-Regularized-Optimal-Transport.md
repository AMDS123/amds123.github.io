---
layout: post
title: "Semi-dual Regularized Optimal Transport"
date: 2018-11-13 20:56:14
categories: arXiv_AI
tags: arXiv_AI Regularization Optimization Inference
author: Marco Cuturi, Gabriel Peyr&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
Variational problems that involve Wasserstein distances and more generally optimal transport (OT) theory are playing an increasingly important role in data sciences. Such problems can be used to form an examplar measure out of various probability measures, as in the Wasserstein barycenter problem, or to carry out parametric inference and density fitting, where the loss is measured in terms of an optimal transport cost to the measure of observations. Despite being conceptually simple, such problems are computationally challenging because they involve minimizing over quantities (Wasserstein distances) that are themselves hard to compute. Entropic regularization has recently emerged as an efficient tool to approximate the solution of such variational Wasserstein problems. In this paper, we give a thorough duality tour of these regularization techniques. In particular, we show how important concepts from classical OT such as c-transforms and semi-discrete approaches translate into similar ideas in a regularized setting. These dual formulations lead to smooth variational problems, which can be solved using smooth, differentiable and convex optimization problems that are simpler to implement and numerically more stable that their un-regularized counterparts. We illustrate the versatility of this approach by applying it to the computation of Wasserstein barycenters and gradient flows of spatial regularization functionals.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05527](http://arxiv.org/abs/1811.05527)

##### PDF
[http://arxiv.org/pdf/1811.05527](http://arxiv.org/pdf/1811.05527)

