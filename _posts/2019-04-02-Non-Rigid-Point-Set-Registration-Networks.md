---
layout: post
title: "Non-Rigid Point Set Registration Networks"
date: 2019-04-02 14:01:59
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Relation
author: Lingjing Wang, Jianchun Chen, Xiang Li, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Point set registration is defined as a process to determine the spatial transformation from the source point set to the target one. Existing methods often iteratively search for the optimal geometric transformation to register a given pair of point sets, driven by minimizing a predefined alignment loss function. In contrast, the proposed point registration neural network (PR-Net) actively learns the registration pattern as a parametric function from a training dataset, consequently predict the desired geometric transformation to align a pair of point sets. PR-Net can transfer the learned knowledge (i.e. registration pattern) from registering training pairs to testing ones without additional iterative optimization. Specifically, in this paper, we develop novel techniques to learn shape descriptors from point sets that help formulate a clear correlation between source and target point sets. With the defined correlation, PR-Net tends to predict the transformation so that the source and target point sets can be statistically aligned, which in turn leads to an optimal spatial geometric registration. PR-Net achieves robust and superior performance for non-rigid registration of point sets, even in presence of Gaussian noise, outliers, and missing points, but requires much less time for registering large number of pairs. More importantly, for a new pair of point sets, PR-Net is able to directly predict the desired transformation using the learned model without repetitive iterative optimization routine. Our code is available at https://github.com/Lingjing324/PR-Net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01428](http://arxiv.org/abs/1904.01428)

##### PDF
[http://arxiv.org/pdf/1904.01428](http://arxiv.org/pdf/1904.01428)

