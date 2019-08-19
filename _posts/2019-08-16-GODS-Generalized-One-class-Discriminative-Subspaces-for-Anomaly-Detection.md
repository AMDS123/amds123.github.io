---
layout: post
title: "GODS: Generalized One-class Discriminative Subspaces for Anomaly Detection"
date: 2019-08-16 08:19:20
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Jue Wang, Anoop Cherian
mathjax: true
---

* content
{:toc}

##### Abstract
One-class learning is the classic problem of fitting a model to data for which annotations are available only for a single class. In this paper, we propose a novel objective for one-class learning. Our key idea is to use a pair of orthonormal frames -- as subspaces -- to "sandwich" the labeled data via optimizing for two objectives jointly: i) minimize the distance between the origins of the two subspaces, and ii) to maximize the margin between the hyperplanes and the data, either subspace demanding the data to be in its positive and negative orthant respectively. Our proposed objective however leads to a non-convex optimization problem, to which we resort to Riemannian optimization schemes and derive an efficient conjugate gradient scheme on the Stiefel manifold. To study the effectiveness of our scheme, we propose a new dataset~\emph{Dash-Cam-Pose}, consisting of clips with skeleton poses of humans seated in a car, the task being to classify the clips as normal or abnormal; the latter is when any human pose is out-of-position with regard to say an airbag deployment. Our experiments on the proposed Dash-Cam-Pose dataset, as well as several other standard anomaly/novelty detection benchmarks demonstrate the benefits of our scheme, achieving state-of-the-art one-class accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05884](https://arxiv.org/abs/1908.05884)

##### PDF
[https://arxiv.org/pdf/1908.05884](https://arxiv.org/pdf/1908.05884)

