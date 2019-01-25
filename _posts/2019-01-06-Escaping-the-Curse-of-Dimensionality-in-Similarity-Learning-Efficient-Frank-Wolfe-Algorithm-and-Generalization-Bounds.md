---
layout: post
title: "Escaping the Curse of Dimensionality in Similarity Learning: Efficient Frank-Wolfe Algorithm and Generalization Bounds"
date: 2019-01-06 21:46:38
categories: arXiv_AI
tags: arXiv_AI Sparse Weakly_Supervised
author: Kuan Liu, Aur&#xe9;lien Bellet
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity and metric learning provides a principled approach to construct a task-specific similarity from weakly supervised data. However, these methods are subject to the curse of dimensionality: as the number of features grows large, poor generalization is to be expected and training becomes intractable due to high computational and memory costs. In this paper, we propose a similarity learning method that can efficiently deal with high-dimensional sparse data. This is achieved through a parameterization of similarity functions by convex combinations of sparse rank-one matrices, together with the use of a greedy approximate Frank-Wolfe algorithm which provides an efficient way to control the number of active features. We show that the convergence rate of the algorithm, as well as its time and memory complexity, are independent of the data dimension. We further provide a theoretical justification of our modeling choices through an analysis of the generalization error, which depends logarithmically on the sparsity of the solution rather than on the number of features. Our experiments on datasets with up to one million features demonstrate the ability of our approach to generalize well despite the high dimensionality as well as its superiority compared to several competing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.07789](http://arxiv.org/abs/1807.07789)

##### PDF
[http://arxiv.org/pdf/1807.07789](http://arxiv.org/pdf/1807.07789)

