---
layout: post
title: "Data Sketching for Faster Training of Machine Learning Models"
date: 2019-06-05 05:10:37
categories: arXiv_AI
tags: arXiv_AI
author: Baharan Mirzasoleiman, Jeff Bilmes, Jure Leskovec
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning problems reduce to the problem of minimizing an expected risk, defined as the sum of a large number of, often convex, component functions. Iterative gradient methods are popular techniques for the above problems. However, they are in general slow to converge, in particular for large data sets. In this work, we develop analysis for selecting a subset (or sketch) of training data points with their corresponding learning rates in order to provide faster convergence to a close neighbordhood of the optimal solution. We show that subsets that minimize the upper-bound on the estimation error of the full gradient, maximize a submodular facility location function. As a result, by greedily maximizing the facility location function we obtain subsets that yield faster convergence to a close neighborhood of the optimum solution. We demonstrate the real-world effectiveness of our algorithm, SIG, confirming our analysis, through an extensive set of experiments on several applications, including logistic regression and training neural networks. We also include a method that provides a deliberate deterministic ordering of the data subset that is quite effective in practice. We observe that our method, while achieving practically the same loss, speeds up gradient methods by up to 10x for convex and 3x for non-convex (deep) functions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01827](http://arxiv.org/abs/1906.01827)

##### PDF
[http://arxiv.org/pdf/1906.01827](http://arxiv.org/pdf/1906.01827)

